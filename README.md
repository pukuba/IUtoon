# 아이유툰
안녕하세요. 아이유를 좋아하는 펜심에서 만들었습니다. 
마치 다음웹툰처럼 아이유의 곡들을 쉽게 볼 수 있는 UI, 머신러닝을 이용한 취향에 따른 아이유 곡 추천까지 해주는 웹애플리케이션입니다. 많은 이용 부탁드립니다. 

# url : http://아이유툰.com

# 개발자 
주홍철(프리랜서), 남승원(선린고1)

# 참고링크
 - https://brunch.co.kr/@kakao-it/279
 - https://twitter.com/allofiu

## 스키마
### popularSong - 10 limit
```
name
album
date
albumImg
```

### song 
```
name
album
date
albumImg
```
태그 추가 예정

### .env
.env 파일은 back-end폴더에 넣으면 된다. 
.env파일의 형식은 다음과 같다. 

### 필요한 쿼리
#### 1. 앨범전체 리스트 : 1 ~ 12집
[{"name" : "1집", "desc" : "1집 Dreamer", "_id" : ""}, ...]

#### 2. 앨범당 리스트 : 예를 들어 1집의 경우, 여러가지 음악들에 대한 정보
album/_id
[{
    name
    album
    date
    albumImg,  
    id
}]

#### 3. song/id
전체다


```js
`
export const GET_ALL_ALBUMLIST = gql`
  query allAlbumList {
    name
    desc
    _id
  }
`
export const GET_ALBUM_SONG = gql`
  query allAlbumSongList {
    name
    album
    date
    albumImg 
  }
` 

export const GET_ALBUM_SONG_NAME = gql`
  query song {
    id
    url
    title
    seecount
    lyrics
    album
    date
    album_info 
  }
`
```