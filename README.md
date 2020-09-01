# SSAFY 3기 2반 공통 프로젝트

- **트랙?** Track 1. 웹 기술 - 개발자 블로그
- **기간?** 2020.07.08 ~ 2020.08.21 (총 7주)
- **팀원?** 곽은정(팀장) 김지윤 김태형 이건수 차보람

<br>

## 🥗 요리 블로그 CookIt 🥗

- 프로젝트 기능 명세서 [ [마크다운 ver.](notes/specification.md) ] [ [엑셀 ver.](notes/specification.xlsx) ]
- [To-do 리스트](notes/to-do.md)
- Front-end : [Mock-up](https://ovenapp.io/view/od8RcDZbTz2JoipOmIimfEljjwdyftTq/)
- Back-end : [ERD](https://www.erdcloud.com/d/JiWq5ZapHeiiuqMjw)
- [Git commit 메시지 및 merge request 규칙](notes/base-rule.md)

<br>

### 👉 https://i3a201.p.ssafy.io

![main](notes/img/main.png)

<br>

<br>

## 🥨 내 블로그

<p><div align="center"><img align="center" src="notes/img/01_blog.gif"></div></p>

  <br>

### 1. 내 레시피와 좋아요한 레시피 모아보기

  <p><div align="center"><img align="center" src="notes/img/10_mine.gif"></div></p>

  블로그의 메인 화면에서 내가 작성한 레시피 뿐만 아니라 좋아요한 레시피를 모아볼 수 있는 기능을 제공합니다.
  
  <br>

### 2. 관심있는 유저를 팔로우 할 수 있는 기능

  <p><div align="center"><img align="center" src="notes/img/12_follow.PNG"></div></p>
  
  레시피 뿐만 아니라 특정 유저를 팔로우하고 싶다면 팔로우할 수도 있습니다.
  
  <br>

### 3. 글쓰기 시 재료 입력 자동 완성

  <p><div align="center"><img align="center" src="notes/img/11_ingr.gif"></div></p>
  
  COOKIT의 메인 기능 중 하나입니다. COOKIT에는 1400개가 넘는 정제된 재료명 데이터가 있습니다. 특히 재료는 대분류, 중분류, 소분류로 나뉘어져 있는데 자동 완성에서는 소분류의 입력만 지원합니다. 단순하게 가나다 순으로 정렬 되는 것이 아닌 적절한 정렬 방법을 도입해서 사용자가 최대한 빠르게 원하는 재료를 입력할 수 있도록 알고리즘을 구현했습니다. 목록에 없는 재료를 입력할 경우 입력되지 않습니다.
  
  <br>

## 🍰 둘러보기

<p><div align="center"><img align="center" src="notes/img/02_recipes.gif"></div></p>

  <br>

### 1. 카테고리별, 제목 및 태그, 최신순, 조회순, 추천순으로 다양하게 검색

  <p><div align="center"><img align="center" src="notes/img/04_category.gif"></div></p>

  <br>

### 2. 재료 필터링으로 원하는 레시피를 보다 쉽고 편하게 검색 가능

  <p><div align="center"><img align="center" src="notes/img/06_filtering.gif"></div></p>
  
  COOKIT의 메인 기능 중 하나입니다. 앞서 말했듯이, 1400개가 넘는 재료 데이터가 정제되어 있고, 레시피를 작성할 때 재료를 입력하기 때문에 찾고 싶은 레시피를 재료에 따라 쉽게 필터링해서 검색할 수 있습니다. 예를 들어, 다른 레시피 사이트에서 김치찌개를 검색하면 돼지고기, 참치, 스팸 등 재료에 구분없이 김치찌개가 모두 나오지만, 특별히 돼지고기 김치찌개를 먹고 싶다면 COOKIT에서 포함할 재료에 `돼지고기`를 입력해서 검색하면 됩니다. 그 외, 알러지가 있는 사람이나 남은 재료를 빨리 사용해야하는 1인 가구 등 다양한 환경에서 편리하게 검색할 수 있습니다.

  <br>

### 3. 나중에 보고 싶은 레시피에 좋아요 누르기

  <p><div align="center"><img align="center" src="notes/img/12_like.gif"></div></p>
  
  좋아요는 해당 레시피에 대한 추천의 의미이자, 스크랩의 의미라고 할 수 있습니다. 

<br>

## 🍤 레시피 뷰어

<p><div align="center"><img align="center" src="notes/img/03_viewer.gif"></div></p>

  <br>

### 1. 시간 부분 자동 인식되는 타이머

  <p><div align="center"><img align="center" src="notes/img/08_timer.gif"></div></p>
  
  COOKIT의 또 다른 메인 기능입니다. 작성자가 레시피에 xx분, xx초, xx~xx분 등 시간을 작성하면 해당 부분을 인식합니다. 시간 부분을 클릭하면 바로 타이머가 시작됩니다. 타이머는 00:00초일 때 종료음을 송출합니다.

  <br>

### 2. 가로보기에서 자동으로 음성 인식 활성화

  <p><div align="center"><img align="center" src="notes/img/09_speech.gif"></div></p>
  
  오른쪽 아래의 가로보기를 누르면 읽기모드 창이 나타납니다. 읽기모드에서는 각 단계별로 페이지를 넘겨서 볼 수 있습니다. 가로보기를 누르면 음성인식이 자동으로 활성화 됩니다. 음성인식 명령으로 다음, 이전, 닫기, 타이머 등을 수행할 수 있습니다.

<br>

<br>

## 🌮 기대효과

<p><div align="center"><img align="center" src="notes/img/expect.PNG"></div></p>

<br>

## 🍩 일정

<p><div align="center"><img align="center" src="notes/img/gantt.PNG"></div></p>

<br>

## 🍭 기술 스택 및 담당

<p><div align="center"><img align="center" src="notes/img/techs.PNG"></div></p>

- Front-end : 곽은정 김태형 차보람
- Back-end : 김지윤 이건수
