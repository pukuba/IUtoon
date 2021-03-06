# 아이유툰
안녕하세요. 아이유를 좋아하는 펜심에서 만들었습니다. 앨범별로, 태그별로 검색이 가능합니다.

마치 다음웹툰처럼 아이유의 곡들을 쉽게 볼 수 있는 UI를 구축했습니다. 많은 이용부탁드립니다. 

# 버전업된 모습
스크롤 했을 때 아이유의 사진이 마치 따라오는 듯한 이펙트를 만들기 위해 고생 좀 했습니다. 
`translateY` 등 애니메이션 최적화해서 버버벅 거리는 현상을 모두 제거했습니다.  
<p align="center"> 
  <img src="https://raw.githubusercontent.com/wnghdcjfe/IUtoon/develop/sample2.gif" width="700">
</p> 

# 구동모습
<p align="center"> 
  <img src="https://raw.githubusercontent.com/wnghdcjfe/IUtoon/develop/example.gif" width="300">
</p> 

# 프론트 메인 기술
 - 패러랙스스크롤
 - fadein Effect
 - sticky CSS
 - debounce search

# 계획
 - 스타수10 이상 : SVG 및 아이유 애니메이션 구현
 - 스타수20 이상 : lSA, KNN, AutoEncoder 등을 이용한 아이유곡 IP 기반 / 컨텐츠기반 추천시스템구현

# 링크
http://kundol.kr

# 담당 
 - 프론트엔드, 코드리팩토링 : 주홍철(큰돌)
 - 백엔드    : 남승원(선린고1) 

# 다음웹툰 UI 
<p align="center"> 
  <img src="https://raw.githubusercontent.com/wnghdcjfe/IUtoon/develop/DAUMUI.gif" width="300">
</p> 
 
## 구동방법
 - 백엔드 : back-end/README.md참조
 - 프론트엔드 : front-backend/README.md참조

### 클라이언트 스펙
 - `React`  
 - `styled-components`
 - `React-apollo`
 - `graphql` 

### 백엔드 스펙  
 - `Node.js`
 - `Express.js`
 - `MongoDB & node.js Driver` 
 - `React-apollo`
 - `graphql`  

# 참고링크
 - https://brunch.co.kr/@kakao-it/279
 - https://twitter.com/allofiu 

# 참고자료
카카오아레나 음악 추천시스템 대회 태그자료 https://arena.kakao.com/