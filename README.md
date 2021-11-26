# 프로젝트팀명 : BUYMESUSHI

## 🌡🌏 BUYMESUSHI('회사조') - 탄소 감축을 위한 인증 SNS 플랫폼

## 프로젝트 시작일 : 2021-11-05

## [**서비스로 이동**](http://주소 미정/)

p.s. 현재 서버를 닫은 관계로 실행이 되지 않습니다

--  
<img width="700" alt="스크린샷 2021-11-05" src="https://user-images.githubusercontent.com/89692626/142747278-39f3f30e-f8d2-4b99-a61f-ceae18ca9d0b.png">

---

Member.

이성재:[깃허브](https://github.com/seongjae-Leee)  
최현석:[깃허브](https://github.com/Hyerin1208)  
김혜린:[깃허브](https://github.com/Tozinoo)  
이소윤:[깃허브](https://github.com/jsoyun)

# 목차

[1.개요](#개요)

[2.목적](#목적)

- 기존 서비스와의 차별점

[3.전체 소스 코드](#전체-소스-코드-click)

[4.디렉토리 설명](#디렉토리-설명)

[5.사용한 기술](#사용한-기술)

[6.주요 기능](#주요-기능)

[7.발생한 이슈 & 해결 방법](#발생한-이슈--해결-방법)

---

### 개요

탄소 감축을 위한 인증 SNS 플랫폼

### 목적

> 탄소 감축을 위한 인증 SNS 플랫폼
>
> 1. SNS 기능 활성화
> 2. 프로젝트 경험
> 3. 블록체인 기반 암호화폐로 대체될 포인트제도 숙달

- **기존 서비스와의 차별점**

  - 커뮤니티 서비스 제공
  - 경제적 유인을 통해 환경보호에 동참하게끔 하는 인증 SNS 플랫폼

### 전체 소스 코드 [소스](https://github.com/buymesushi/BUYMESUSHI.git)

# 디렉토리 설명

전체 코드 : [코드](https://github.com/buymesushi/BUYMESUSHI.git)

    - 폴더 설명
    BUYMESUSHI
    |
    |--node_modules         - 모듈
    |--client               - Front 폴더
    |   |--node_modules     - 모듈
    |   |--public           - Front 정적 폴더
    |   |   |--img          - Front 정적 이미지 폴더
    |   |--src              - source 폴더
    |   |   |--actions      - 액션 메서드 모음 폴더
    |   |   |--components   - 컴포넌트 폴더
    |   |   |   |--views    - 각종 컴포넌트 모음 폴더
    |   |   |--hoc          - 권환 관리 모음 폴더
    |   |   |--reducers     - 리듀서 모음 폴더
    |   |   |--redux        - 상태관리 폴더
    |   |--App.js           - 컴포넌트 모음
    |   |--index.js         - 진입 파일
    |   |--setupProxy.js    - 프록시 설정
    |
    |--server               - Backend 폴더
        |--config           - 각종 환경 설정 관리 폴더
        |--controller       - Req, Res 담당 폴더
        |--data             - seed 데이터 초기 값 관리 폴더
        |--middleware       - 각종 미들웨어
        |--models           - 데이터베이스의 각 컬렉션에 해당하는 파일들 모음
        |--routes           - 각종 라우터 모음
        |
        |--index.js         - 진입 파일

### 사용한 기술

- 웹 화면 구성 : `React` `CSS` `styled-components` `JavaScript XML`
- 데이터 요청 및 출력 : `Ajax` `JSON` `axios`
- DB 액션 처리 : `Mongoose`
- DBMS : `MongoDB`
- 개발 Tool : `Visual Studio Code` `PostMan`
- 날씨 Api : `openweathermap API`
- 프레임워크 : `Express` `NodeJs`
- 프로젝트 관리 Tool : `GitHub` `Google Drive`

- 사용 모듈(server) :  
  "bcrypt": "^5.0.1",  
  "body-parser": "^1.19.0",  
  "concurrently": "^6.3.0",  
  "cookie-parser": "^1.4.5",  
  "cors": "^2.8.5",  
  "express": "^4.17.1",  
  "fs": "^0.0.1-security",  
  "jsonwebtoken": "^8.5.1",  
  "jwt-decode": "^3.1.2",  
  "jwt-token": "^1.0.9",  
  "mongo-seeding": "^3.7.0",  
  "mongoose": "^6.0.12",  
  "mongoose-sequence": "^5.3.1",  
  "multer": "^1.4.3",  
  "path": "^0.12.7"

- 사용 모듈(client) :  
  "@material-ui  
  "@mui  
  "@nivo/core": "^0.74.0",  
  "@nivo/line": "^0.74.0",  
  "@testing-library  
  "@toast-ui/editor-plugin-code-syntax-highlight": "^3.0.0",  
  "@toast-ui/editor-plugin-color-syntax": "^3.0.2",  
  "@toast-ui/react-editor": "^3.1.1",  
  "axios": "^0.24.0",  
  "bulma": "^0.9.3",  
  "chart.js": "^3.6.0",  
  "eslint-plugin-import": "^2.25.2",  
  "http-proxy-middleware": "^2.0.1",  
  "mobx": "^6.3.7",  
  "moment": "^2.29.1",  
  "observer": "0.0.2",  
  "prismjs": "^1.25.0",  
  "prop-types": "^15.7.2",  
  "react": "^17.0.2",  
  "react-chartjs-2": "^3.2.0",  
  "react-modal": "^3.14.3",  
  "react-pretty-carousel": "^1.0.19",  
  "react-redux": "^7.2.6",  
  "react-router-dom": "^5.3.0",  
  "react-slick": "^0.28.1",  
  "react-spring": "^9.3.0",  
  "redux": "^4.1.2",  
  "redux-promise": "^0.6.0",  
  "redux-thunk": "^2.4.0",  
  "slick-carousel": "^1.8.1",  
  "styled-components": "^5.3.3",  
  "swiper": "^7.2.0",  
  "web-vitals": "^1.0.1",  
  "webpack": "4.44.2",

### 주요 기능

- 메인페이지 : `MUI` `styled-components` `modal` `react-slick` `API` `chartjs`
- 로그인 : 일반 로그인, `mongoose` `JWT` `redux` `Token` `bcrypt`
- 회원가입 : `mongoose` `nodeJS` `bcrypt` `validation`
- 소개 : `MUI` `styled-components` `react-scroll` `react-scroll-slider` `Custom Hook`
- 지키미인증 : `mongoose` `multer` `redux` `axios`
- 포인트사용 : `mongoose` `redux` `axios`
- 미니게임 : `Vanilla JS`
- 게시판 : `mongoose` `express` `axios` `modal`
- 마이페이지 : `mongoose` `redux` `axios`

# 발생한 이슈 & 해결 방법

### "리덕스와 db 연결의 어려움 - ## 이소윤 "

- 리덕스,id값 전송 시 수량 값 추가하기

[상황] 미숙한 redux 사용으로 기존 스토어를 통한 상태값과 함수 주입에 어려움을 겪었다.

[문제] 리덕스를 사용해 장바구니에 쇼핑목록값을 저장하고 데이터관계설정으로 User에 products를 추가하였음에도 db연결을 하지 못해 모든
회원의 마이페이지 내용이 동일하였다.

[해결] 쇼핑카트에서 마이페이지로 선택한 products들의 data를 넘겨주도록
하였다. 기존 data에 수량까지 추가해 mypage라우터로 axios.put으로 넘겨주었다.
마이페이지 라우터에서 현재 유저의 아이디에 해당하면 정해진 db설정에 맞게 $push해 주었다.

- 객체값으로 묶어보낸 값을 updateOne와 $pull을 사용해 삭제하기

[상황] 장바구니에 추가한 상품들을 선택해 삭제하려고 하였다.

[문제] 삭제가 되지 않거나 하나의 상품만 선택하여도 모든 products 값이 삭제되었다.

[해결] 선택한 상품만 삭제되도록 선택한 상품의 id를 axios.post로 먼저 보내주었다.
id는 숫자 string값이라 {productId:id}로 객체값으로 묶어 보냈다. 마찬가지로 현재 유저의
아이디에 해당하고, 요청한 productId와 동일하면 Spull을 통해 삭제하도록 했다.

### "react 이해 부족 - ## 최현석 "

- 상태관리 useState useEffect redux

[상황] 초반 redux 사용(user). 이후 useState, useEffect 주로 사용

[문제] redux값 useState에 대입, 렌더링 전 state값 undefined로 출력됨

[해결] if문 사용하여 undefined시 return null, state 값 있을 시 해당 부분 렌더링

- 이미지 업로드

[상황] 이미지 업로드 시 fakepath 경로 오류

[문제] chrome에서는 보안문제 때문에 로컬 전체 경로를 알지 못하게 하는 보안 기능이 있음

[해결] URL.createObjectURL 메소드 사용

- 몽고디비 seeder 생성

[상황] 초기 데이터 생성 위하여 seed Data 설정

[문제] 암호생성을 위하여 bcrypt 사용. 해당 데이터 Object(<promise>)로 출력

[해결] 프로젝트 진행을 위하여 암호화 된 문자열 직접 입력 ( 추후 해결 필요 )

- react if문 사용

[상황] react render 안에서 if문 사용

[문제] render안에서 if문 사용 불가

[해결] render 밖에서 if문 사용 또는 삼항연산자 사용

### "proxy 연결 - ## 최현석"

- route 연결 proxy

[상황] 라우터 연결 시 연결 오류

[문제] [HPM] Error occurred while proxying request 에러 발생

[해결] client와 server 연결 시 RESTful API 지켜줘야함

### "기본 css개념의 중요성과 React - ## 김혜린"

[상황] 팀플 후반 프런트와 백엔드 깃 병합 과정에서 css 충돌

[문제1] 메인디자인이 프론트 브랜치에서 보는거랑 백에서 보는거랑 달라져
시간은 부족하고 그러다보니 병합과정에서 약간의 팀원들과의 의견충돌

[해결] 프런트 파트에서 각 파트에서 진행하고 styled-components를 사용중임을 정확히 설명하고
팀원들과 리액트 컴포넌트 스타일링 방식에서 전역으로 들어가 충돌이 일어나지 않도록 했어야 햇는데
그렇지 못해서 하나하나 나중에 다시 수정해나아갔다.
다음 팀플 진행시 css 부분을 간과하지 말아야 함을 많은 시간을 쏟으며 배움.

### "React 활용 미숙 - ## 이성재"

- 모듈 활용 미숙, 커스터마이징 방식

[상황1] 유효성을 검사하는 함수를 만들어 MUI 를 따온 input에 프론트 단에서 어떻게 유효성 검사를 할 수 있을지 고민되었다.

[문제1] MUI 컴포넌트와 유효성 검사를 합치하는데 boolean 값이 헷갈렸다.

[해결1] MUI의 error 시 적용되는 css와 validation 함수를 합쳐 주어진 유효식과 다른 text가 입력되면 MUI에서도 error로 작성되게하였다.

[상황2] chart-js 적용하는 방식에서 OpenAPI 자료를 원하는 방식으로 정리해서 x축, y축에 띄우고 싶었다.

[문제2] grenn-gas emission api의 년도별 배출량이 하나의 객체 안에 다 들어가 있었다.

[해결2] 증가되는 추세를 보여주기 위해 chart로 보여주고 싶었으므로 하나의 나라의 배출량만을 불러와서 년도별 배출량을 표시했다.

- 모달을 활용한 data 주고받기

[상황] : 게시글 리스트, 게시글 작성, 상세 게시글을 한 페이지에서 모달만을 활용하여 데이터를 주고 받아야 했다.

[문제] : 각각의 page가 있는 것이 아니어서 cannot post/ boardwrite에러가 뜨는 등 route에서 경로 설정해주는게 혼란스럽고 세부 게시글을 불러오는 방식도 헷갈렸다.

[해결] : input마다 value를 주고 route에서 경로만 설정해주면서 post 방식으로 데이터를 전달했고, 상세 게시글에서는 게시글 리스트에서 props로 상위 컴포넌트의 데이터를 받아왔다.

- 훅 활용 및 리덕스, 스토어의 활용 미숙

[상황] : 반복되는 같은 styled-component나 함수가 필요한 파일마다 들어가 있었다.

[문제] : 코드가 길어지면서 가독성이 떨어지고 리덕스의 효능을 제대로 누리지 못했다.

[해결] : 스토어로 바꿀 수 있는 부분은 바꿔보고 props로 그나마 코드를 줄였다. (추가 보완 필요)

- 개발 과정에서 DB 삭제하면서 일어나는 유저 관련 issue

[상황] : 게시판에서 작성한 유저 nickname 띄우는게 갑자기 안 됐다.

[문제] : 유저 DB가 사라지면 게시판에 nickname을 불러올 수가 없어서 게시판이 오류가 났다.

[해결] : 소통의 문제였으므로 공유하고 있는 db에 대해 변화를 줄 때는 서로 소통하기로 하였다.
