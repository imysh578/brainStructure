# 프로젝트팀명 : BrainStructure

## 🧠BrainStructure('뇌구조') - 강동구 맛집 추천 웹사이트

## 프로젝트 기간 : 2021-08-31 ~ 2021-09-08

## [**서비스로 이동**](http://주소 미정/)

p.s. 현재 서버를 닫은 관계로 실행이 되지 않습니다

--  
<img width="1100" alt="스크린샷 2021-11-05" src="https://user-images.githubusercontent.com/89692626/143542856-7d008fc9-d4bf-4808-8338-e09d3744500a.png">

---

Member.

이성재:[깃허브](https://github.com/seongjae-Leee)  
윤석훈:[깃허브](https://github.com/imysh578)  
이민주:[깃허브](https://github.com/codecocos)  
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

## 개요

음식에 진심인 한국인들을 대상으로 강동구 맛집리스트 사이트를 만들고자 했고 기존 맛집사이트와 차별화가 필요하다.

---

## 목적

강동구 음식 맛집을 카테고리화하여 모아볼 수 있게 하는 웹사이트

> 1. HTML5, CSS, JavaScript 활용한 웹페이지 구성
> 2. 로그인 후 찜 기능 활성화
> 3. 팀 프로젝트 경험
> 4. 오픈 API 데이터 불러오기 및 활용

- **기존 서비스와의 차별점**
  - 강동구 한정 맛집 서비스 제공
  - 난수를 활용한 랜덤한 맛집 추천
  - 카카오 API를 이용한 로그인 및 지도 서비스
  - 최근 검색 목록을 모달창에 나열
  - 강동구에 등록된 업체 목록의 중복 제거

---

## 전체 소스 코드  
[코드 바로가기](https://github.com/imysh578/brainStructure.git)


---
## 디렉토리 설명

    - 폴더 설명
    BrainStructure
    |
    |--.vscode              - 포트 번호
    |--images               - 아이콘 등 이미지 폴더
    |--scripts              - 
        |--cookies.js       - 쿠키값 저장 및 불러오기 기능
        |--headers.js       - 상단바(검색, 로그인, 최근검색목록, 내 리뷰 목록)
        |--main.js          - 메인페이지(맛집 추천, 카테고리 링크, 식당 추천)
        |--review_list.js   - 내 리뷰 목록(가입된 사용자에게만 권한 부여)
        |--review_write.js  - 리뷰 작성(날짜 입력, 맛집 점수 기능)
        |--search.js        - 강동구 음식점 API (중복 제거), 카카오 지도 API 활용
    |--styles               - CSS 모음
    |--videos               - 메인페이지 애니메이션 파일
    |
    |--create.html               - 게시판(리뷰) 글 작성 페이지
    |--index.html                - 메인페이지 
    |--map custom.html           - 카카오 지도 API 페이지
    |--process_create.php        - 게시판 글 작성 과정
    |--review_list.html          - 게시판(리뷰) 리스트 페이지
    |--search.html               - 검색 결과 페이지

---

## 사용한 기술

- 웹 화면 구성 : `Html` `CSS` `JavaScript`
- 데이터 요청 및 출력 : `Ajax` `JSON` `fetch`
- DB 액션 처리 : `php`
- DBMS : `MariaDB`
- 개발 Tool : `Visual Studio Code`
- 카카오 지도 Api : `kakao API`
- 강동구 음식점 Api : `강동구 음식점 API`
- 프로젝트 관리 Tool : `GitHub` `Google Drive` `Webex`

---

## 주요 기능

- 메인페이지 : `HTML5` `CSS` `JavaScript` `API`
- 로그인 : 카카오 로그인, `HTML5` `CSS` `JavaScript` `API`
- 음식점 검색 : `HTML5` `CSS` `JavaScript` `API`
- 음식점 렌덤 추천 : `HTML5` `CSS` `JavaScript` `API`
- 음식점 카테고리 검색 : `HTML5` `CSS` `JavaScript` `API` 
- 리뷰게시판 : `php` `mysqli` 
- 최근 검색 목록 : `JavaScript`

---

## 발생한 이슈 & 해결 방법

### "api배열과 함수 사용의 어려움- ## 이소윤 "

- html과 css틀잡기

[상황] 검색 페이지를 맡아 음식리스트가 뜨는 부분과 지도가 뜨는 부분을 나눴다.

[문제] html과 css 틀을 잡는데 어려움을 느꼈다.

[해결] 그리드를 사용해 틀을 나눴다.

- 맛집리스트 api 정보부르기(중복도출 피하기)

[상황] 메인 페이지에서 검색어를 입력하면 쿠키로 넘겨 검색이 되게 하였다. 

[문제] 음식api 배열이 깔끔하지 않아 검색리스트로 부르는데 많은 어려움을 겪었다. 특히 검색이 된다고 해도 업소명이 중복되어 검색되어나왔다.

[해결]  배열이름을 확인하고 list로 데이터의 구체적 배열을 할당해주었다. 중복을 제거하고 업소명을 담아둘 리스트를 따로, 그곳에 포함되지 않은 이름이면 push하도록 했다. for문을 사용해 보여줄 정보에 이름을 붙였다.

- 카카오지도 맛집추천 링크마크 넣기

[상황] 카카오지도 api를 불러오면서 특정 음식점들의 링크를 지도안에 마크로 넣어주고자 했다.

[문제] 한번 마크를 넣을 때마다 코드가 추가되었는데 링크로 넘어가는 모두 같은 역할을 하고 있었지만 지도상 위치값이 달라서 통일하지 못해 쓸데없이 코드가 길어졌다.

[해결]  마커를 표시할 위치와 이름,링크주소를 하나의 position 객체 배열에 모두 담았다. 해당하는 값을 찾아 마크 이름과 링크를 연결했다. 이로써 코드 길이를 줄일 수 있었다.  

***

### " Cookie 사용 및  - ## 윤석훈 "

#### 로그인 상태에 따른 페이지 변환

- [상황] 로그인 상태에 따라 사용자 프로필 삽입 및 최근 검색 목록 데이터를 보여주어야함.

- [문제] 페이지가 새로 랜더링 될 때마다 로그인 데이터가 사라짐.

- [해결] Logined 상태 변수를 Cookie에 담아서 로그인 상태를 체크, 그에 따라 다른 페이지 보여줌.


#### 싱글페이지로 로그인/비로그인 화면 띄우기

- [상황] 페이지 랜더링 없이 로그인/비로그인 상태에 따른 화면을 띄우려고 함.

- [문제] 각각의 html 파일을 만들면 공통된 코드가 반복 됨.

- [해결] Cookie 값을 활용하여 컴포넌트의 hidden 속성을 바꿔줌.


#### 모달 창 구현

- [상황] 로그인 / 최근 검색 목록 / 내 리뷰 목록 을 모달 창으로 구현하려고 함.

- [문제] 모달 창을 새로운 html로 만들면 매번 랜더링 되는 문제 발생

- [해결] 하나의 html 안에 모달 창 div를 만들고 z-index를 상위로 올려줌.


#### Input 태그 안에 Button 태그 넣기

- [상황] 상단 바의 Input 태그 안에 Button 태그를 넣음.

- [문제] Input 태그의 border 라인과 Button의 border 사이에 빈 공간이 생김.

- [해결] box-shadow를 주어 빈 공간을 처리함.

***

### "DB 사용에 미숙 - ## 이민주"

#### 휘발되지 않는 정보의 필요성에 의한 게시글 DB 생성

- [상황] 사용자의 음식점에 대한 리뷰가 DB에 축적되어 타 사용자에게 노출될 수 있도록 하여야 하지만
DB가 없어서 작성된 리뷰글이 휘발되는 상황

- [문제] DB에 저장된 글을 PHP으로 활용하기 위해서는 create 명령어를 정확히 사용하여야 했으나,
create 조건 인지의 미숙으로 생성에 실패

- [해결] input 태그의 name 부분을 DB 테이블의 필드명과 일치 시켜줌으로써 해결.

#### 외부 접속을 위한 server 이용

- [상황] 홈페이지 개발 상황에서는 localhost로 접속만으로 충분하였으나, 사용자들의 리뷰를 수집하기 위해서는 외부접속이 가능해야함.

- [문제] localhost를 통한 홈페이지 접속만이 가능함. 이 외에는 홈페이지에 접급할 수 있는 방법이 없음.

- [해결] bitnami wamp를 활용하여 server 이용을 위한 환경셋팅 후 외부 접속이 가능하게 함.   

***

### "API 활용과 웹디자인 미숙 - ## 이성재"

#### axios 없이 fetch 함수만으로 데이터를 불러오기

- [상황] 강동구 맛집 API를 불러와야 하는데 axios 없이 fetch 함수(GET 방식)로 API를 불러와야 했다.

- [문제] API를 다뤄본 적이 없다보니 기본적으로 데이터를 불러오는 방법조차 모르고 promise에 대해서도 미숙해 데이터값을 불러오기 힘들었다.

- [해결] 주석을 달면서 천천히 로직을 생각하며 then 메서드를 활용해 필요한 정보들을 다뤄볼 수 있었다.

##### 검색 프로세스처럼 클릭했을 때 페이지 이동(1)

- [상황] : 오늘의 추천 식당을 눌렀을 때 해당 식당 정보를 가진 페이지로 넘겨줘야 했다.

- [문제] : 세가지 식당이 뜨게 하면서도 그 세개가 겹치지 않는 난수로 for문에 들어가야 하고 검색 프로세스와 같이 쿠키에 저장까지 해야해서 로직이 헷갈렸다.

- [해결] : addEventLister 메서드와 setCookie 메서드를 통해 클릭했을 때 검색화면으로 넘어가게 하였다.

#### 검색 프로세스처럼 클릭했을 때 페이지 이동(2)

- [상황] : 카테고리를 눌렀을 때 그 카테고리에 해당하는 식당들을 모두 띄워줘야 했다.

- [문제] : 만들고 싶은 카테고리가 있었으나 API의 카테고리에는 정해진 카테고리가 있었기에 괴리감이 생겼다.

- [해결] : 이름까지 똑같이 해서 API에 맞춘 카테고리를 만들었으나 지금 다시 한다면 내가 만든 카테고리에 맞춰 클릭했을 때 원하는 식당들이 뜰 수 있게 할 것 같다. 그리고 또한 API 활용을 메인으로 하는 사이트에서는 API 의 데이터 질이 굉장히 중요하다는 것을 느꼈다.

#### 메인 컨텐츠의 비율 분할 및 배정

- [상황] : flex가 아닌 grid로 카테고리나 추천식당의 자리를 만들고 싶었다.

- [문제] : grid 활용의 미숙과 padding과 margin에 대한 이해 부족으로 인해 원하는 곳에 배정의 어려움을 겪었다.

- [해결] : mozilla 문서와 padding, margin을 활용한 다른 사이트를 참고해 개념을 다시 숙지한 후 재배치했다.

#### 메인페이지 디자인

- [상황] : 유저에게 첫인상을 주는 메인페이지를 디자인해야 했다.

- [문제] : 웹페이지 디자인 자체가 처음이라 우리만의 아이덴티티를 어떻게 보여줄지, 그리고 헤더와 메인컨텐츠의 비율이 고민되었다.

- [해결] : 맛집 소개 페이지인만큼 메인페이지에 음식 관련 애니메이션을 크게 띄우고 추천 음식 하나만을 보여주고 다른 색은 통일하면서 심플하지만 임팩트 있게 만들어 보려 했다.

-----------------------------------------------------------------------------------------------------------------------------
