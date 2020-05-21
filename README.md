# BoostCourse

Full-Stack Developer

- 코드는 비공개입니다.

### [BE 프로젝트1. 나를 소개하는 홈페이지 만들기](https://seokr.tistory.com/545)

- HTML, CSS, Servlet
- **목표**
  - 페이지 네이게이션 구현
  - 현재시간 노출 구현

### [FE 프로젝트1. 나를 소개하는 홈페이지 만들기](https://seokr.tistory.com/545)

- HTML, CSS, Servlet
- **목표**
  - index.html 레이아웃
  - aboutme.html 레이아웃
  - photo.html 레이아웃
  - 현재시간 페이지 레이아웃
  - HTML 태그 구조화 설계
  - CSS Layout, selector 문법

### [BE_프로젝트2. TO-DO LIST 구현 하기](https://seokr.tistory.com/545)

- HTML, CSS, JavaScript, JSP, MySQL, Servlet, Web API
- **목표**
  - 메인페이지 - ToDo 카드노출
  - 메인페이지 - ToDo 카드이동
  - Dao, Servlet 구조화

### [FE_프로젝트2. TO-DO LIST 구현하기](https://seokr.tistory.com/545)

- HTML, CSS, JavaScript, JSP, MySQL, Servlet, Web API
- 목표
  - 메인 페이지 레이아웃 (ToDo, Doing, Done)
  - 할 일 등록 레이아웃
  - HTML 태그의 사용
  - CSS selector
  - CSS Layout
  - Event, DOM, Ajax의 표준 API사용



- **피드백 및 개선**
  - [프로젝트2: To-Do List 구현 피드백](https://seokr.tistory.com/555?category=757303)
  - [프로젝트2: To-Do List 구현 피드백2](https://seokr.tistory.com/563?category=757303)
  - [프로젝트2: To-Do List 구현 피드백3](https://seokr.tistory.com/566?category=757303)



### [BE_프로젝트3. 예약관리 시스템: 메인페이지](https://seokr.tistory.com/572?category=757303)

- HTML, CSS, HTML Templating, JavaScript, Event Delegation, Spring, RestController, Web API
- **목표**
  - 카테고리노출영역(탭UI)
    - 전체리스트가 Ajax를 통해서 화면에 4개의 아이템이 노출
    - 탭별 전체갯수
    - 각 아이템(전시상품)당 이미지/제목/장소/설명이 노출
    - 탭을 누르면 다른 카테고리 콘텐츠 4개가 다시 노출
    - 더보기를 누르면 4개씩 노출, 4개보다 적으면 적은 만큼 노출
    - 더보여줄 데이터가 없다면 더보기는 제거
    - TOP영역이 선택되면, 화면 맨 위로 이동
  - JAVA - 중복된 코드 제거 및 코드 구조화
  - JAVA - 가독성
  - JAVA - 프로젝트 생성 (pom.xml, .gitignore)
  - JAVA - 프로젝트 구조 및 호출 방향 주의 (Controller -> Service -> Repository)
  - JAVA - Web API
    - 전체, 카테고리별 상품정보를 제공하는 Web Api를 제공
    - 전체, 카테고리별 상품 수를 제공하는 Web Api를 제공
    - 프로모션 정보를 알맞게 제공하는 Web Api를 제공
    - SQL 문을 표준에 맞추어 작성하며 각 DBMS 별로 구현된 문법 사용은 최소화
    - 전체, 카테고리별 상품 수는 GROUP BY 구문을 이용
    - 데이터 수를 조회하는 경우 COUNT(*) 를 사용



- **피드백 및 개선**
  - [프로젝트3. 예약관리 시스템: 메인페이지(BE) FAIL](https://seokr.tistory.com/589)
  - [프로젝트3. 예약관리 시스템: 메인페이지(BE) PASS](https://seokr.tistory.com/590)
  - [프로젝트3. 예약관리 시스템: 메인페이지(BE) 개선](https://seokr.tistory.com/595)
  - [프로젝트3. 예약관리 시스템: 메인페이지(BE) API 수정](https://seokr.tistory.com/626)
  - [프로젝트3. 예약관리 시스템: 메인페이지(BE) PASS](https://seokr.tistory.com/627)


### [FE_프로젝트3. 예약관리 시스템: 메인페이지](https://seokr.tistory.com/572?category=757303)

- HTML, CSS, HTML Templating, JavaScript, Event Delegation, Spring, RestController, Web API
- **목표**
  - 메인페이지 레이아웃
    -  GNB영역
    - 프로모션영역
    - 카테고리영역(6개의 메뉴구성)
    - 상품리스트(기본 4개)
    - 더보기 화면
  - 프로모션영역
    - 자동으로 슬라이딩 (무한반복)
    - 슬라이딩 이미지는 애니메이션이 되면서 좌측으로 이동
  - HTML, CSS
    -  TABUI로 구성되는 카테고리 아이템이 노출 되는 영역 재사용
  - CSS3 를 사용한 애니메이션 구현
    - transition과 transform 속성을 JavaScript로 제어
  - 효과적인 브라우저 기반 개발 방식사용
    - DOMContentloaded 이후에 모든 자바스크립트 로직이 동작
    - 카테고리 탭을 선택할 때마다, Ajax요청
    - 탭메뉴 (전시/뮤지컬/콘서트 등)는 Event delegation으로 구현
  - JavaScript 코드 개선
    -  Template 코드를 javascript 함수안에 보관하지 않고, 별도 분리시켜서 사용
    - 함수 하나에 여러개의 기능을 넣지 않고,함수를 여러개로 분리



- **피드백 및 개선**
  - [프로젝트 3. 예약관리 시스템: 메인페이지(FE) PASS](https://seokr.tistory.com/630)



### [BE_프로젝트4. 예약관리 시스템: 상세페이지](https://seokr.tistory.com/584?category=757303)

- HTML, CSS, HTML Templating, JavaScript, Event Delegation, handlebar, Spring, RestController, Web API
- **목표**
  - 상세페이지 메인화면
  - Java - Web API
    - 상품 id를 전달 받아 해당 상품의 상품 정보, 예매자 리뷰 목록을 반환하는 Web API를 작성
    - 예매자 리뷰정보의 경우 전체를 제공


- **피드백 및 개선** 
  - [프로젝트4. 예약관리 시스템: 상세페이지(BE) FAIL](https://seokr.tistory.com/632)
  - [프로젝트4. 예약관리 시스템: 상세페이지(BE) PASS](https://seokr.tistory.com/634)



### [FE_프로젝트4. 예약관리 시스템: 상세페이지](https://www.edwith.org/boostcourse-web/project/109/content/93#evaluation)

- HTML, CSS, HTML Templating, JavaScript, Event Delegation, handlebar, Spring, RestController, Web API
- **목표**
  - 상세페이지 하단 영역
    - 공지 사항과 지도는 일반 이미지를 사용해서 추가
  - 타이틀영역 배경이미지 슬라이딩
    - 서버에 기타(etc)로 존재하는 이미지가 있다면, 좌/우슬라이딩 버튼을 노출
    - 이미지가 슬라이딩 애니메이션 
    - 무한 슬라이딩으로 계속 동작
  - 펼쳐보기
    - 접기/펼치기를 선택하면 레이어의 높이가 변하면서 반응
  - 하단영역의 상세정보와 오시는길
    - 탭UI로 동작
    -  화면새로고침 없이 탭을 통해서 동작
  - JavaScript 객체리터럴 패턴사용
    - 전체 코드는 객체리터럴 패턴으로 구현
    - 전역변수를 최소화
    - 한 개 이상 객체리터럴을 사용 가능
  - JavaScript 라이브러리 사용
    - Templating 작업은 handlebar 라이브러리를 사용해서 구현
    -  접기/펼치기 기능은 jQuery 라이브러리를 사용가능
  - JavaScript 클린코드
    - 함수 하나에 여러개의 기능을 넣지 않고, 함수를 여러개로 분리
    -  중복코드를 제거하고 공통부분을 공통함수 작성



- **피드백 및 개선**
  - [프로젝트4. 예약관리 시스템: 상세페이지(FE) FAIL](https://seokr.tistory.com/640)
  - [프로젝트4. 예약관리 시스템: 상세페이지(FE) PASS](https://seokr.tistory.com/643)



### [BE_프로젝트5. 예약관리 시스템:예약하기](https://seokr.tistory.com/666)

- HTML, CSS, HTML Templating, JavaScript, Regular Expression, Event Delegation, handlebar, Spring, RestController, Web API, Session, Interceptor, Argument Resolver
- **목표**
  - 예매내역확인 (예약확인) - 예약취소기능
    - 취소를 누르면 취소하겠냐는 메시지 레이어가 화면 가운데 뜨고 확인/취소를 통해 즉시 반영
    - 취소된 이후에는 '취소된 예약' 으로 새롭게 화면에 결과 출력
  - Java - Web API
    - 티켓 정보, 예약자정보를 전달받아 저장하는 Web API를 작성
    - email을 입력받아, 해당 email로 예약된 예약정보 목록을 보여주는 Web API를 작성
    - email로 검색된 결과가 1건 이상이 있을 경우 세션에 email정보를 저장
  - Java - JSP
    - 세션에 email이 있을 경우 메인 페이지의 우측 상단의 "예약확인" 은 세션의 email값으로 변경
    - 메인 페이지의 email링크를 클릭하면 해당 email로 예약된 예약 정보 목록을 보여주는 Web API를 호출한 결과



- **피드백 및 개선**
  - [프로젝트5. 예약관리 시스템: 예약하기(BE) PASS](https://seokr.tistory.com/676)


- **프로젝트 주의 사항**

  - *application.properties* 생성 (보안으로 깃에 업로드 안하도록 적용 되어 있음)

```properties
    spring.datasource.driver-class-name={db}
    spring.datasource.url={db url}
    spring.datasource.username={db username}
    spring.datasource.password={db password}
```


### [FE_프로젝트5. 예약관리 시스템:예약하기](https://seokr.tistory.com/666)

- HTML, CSS, HTML Templating, JavaScript, Regular Expression, Event Delegation, handlebar, Spring, RestController, Web API, Session, Interceptor, Argument Resolver
- **목표**
  - 예약하기
  - 예약확인하기
  - 예약하기 - 티켓입력
    - +,- 버튼을 누르면 숫자가 증가/감소되고, 금액이 변경
    - 0명이면 버튼이 비활성화
  - 예약하기 - 예매자정보 입력
    - 총 매수는 예약상황을 합쳐서 갯수가 변경될 때 바로 변경되어 노출
    - 연락처 정보는 전화번호 포맷(휴대폰/일반전화 모두 가능)만 입력이 가능
    - 그 외 값이 입력 되면 입력된 값의 형식이 틀렸다는 메시지를 자유롭게 만들어서 화면에 노출
  - 예약하기 - 약관동의 및 예약
    - 약관은 접기/보기로 토글
    - 약관정보 동의에 체크하면 활성화된 상태로 노출
    - 예매갯수가 1개이상, 예매자입력,연락처입력,약관동의 된 상태라면 모든 값이 유효한 상태
    - 모든 정보가 유효하다면 '예약하기' 버튼이 활성화된 상태로 노출
  - 예매내역확인 (예약확인) - 이메일로그인
    - 이메일 규칙검사
  - 예매내역확인 (예약확인) - 예약취소기능
    - 취소를 누르면 취소하겠냐는 메시지 레이어가 화면 가운데 뜨고 확인/취소를 통해 즉시 반영
    - 취소된 이후에는 '취소된 예약' 으로 새롭게 화면에 결과 노출
  - JavaScript - 객체지향개발
    - 자주 사용되는 함수를 객체형태로 묶어서 사용
    - UI 별로 기능을 묶어서 객체화된 모듈을 만들어야 하며, prototype방식을 적용
  - JavaScript- 정규표현식기반 유효성검증
    - form에 입력된 값을 체크를 할 때는 값의 유효성(validation)을 체크
    - 정규표현식을 써서 구현 (이메일 필드는 반드시 유효성검증)



- **피드백 및 개선**
  - [프로젝트5. 예약관리 시스템: 예약하기(FE) PASS](https://seokr.tistory.com/677)

- **프로젝트 주의 사항**

  - *application.properties* 생성 (보안으로 깃에 업로드 안하도록 적용 되어 있음)

```properties
    spring.datasource.driver-class-name={db}
    spring.datasource.url={db url}
    spring.datasource.username={db username}
    spring.datasource.password={db password}
```


### [BE_프로젝트6. 예약관리 시스템: 한줄평](https://seokr.tistory.com/678)

- HTML, CSS, HTML Templating, JavaScript, Regular Expression, Event Delegation, handlebar, Spring, RestController, Web API, Session, Interceptor, Argument Resolver, File upload & download, logging, 
- **목표**
  - 사진 등록 (업로드)
    - 사진 한장 업로드가 가능 (한장 이상 업로드 가능하도록 수정함)
    - 별점, 한줄평내용, 사진파일을 서버로 업로드
    - 사진파일의 확장자는 jpg, png만 허용
  - Java - Web API
    - 별점, 리뷰, 이미지(image)파일을 전달받아 저장하는 web api를 작성
    -  업로드의 경우는 MultipartFile을 이용해 파일 정보를 읽기
    - 이미지 업로드 되는 경로는 프로젝트 외부 폴더로 설정
    - 동일한 이름의 파일이 업로드 하더라도 덮어쓰기 X
    - api가 호출될 때, 컨트롤러 메소드의 이름과 요청 시간등을 log로 기록
  - Java - 다운로드
    - 이미지 id를 전달받아, 해당 이미지를 다운로드 하는 컨트롤러를 작성
  - Java - jsp
    - 기존 jsp의 이미지 경로를 이미지 다운로드 컨트롤러를 이용되도록 수정



- **피드백 및 개선**
  - [프로젝트6. 예약관리 시스템: 한줄평(BE) PASS](https://seokr.tistory.com/686)


- **프로젝트 주의 사항**

  - *application.properties* 생성 (보안으로 깃에 업로드 안하도록 적용 되어 있음)

```properties
    spring.datasource.driver-class-name={db}
    spring.datasource.url={db url}
    spring.datasource.username={db username}
    spring.datasource.password={db password}
```


### [FE_프로젝트6. 예약관리 시스템: 한줄평](https://seokr.tistory.com/678)

- **목표**
  - 한줄평쓰기
  - 별점입력
    - 별점을 1~5점까지 선택 (마우스 클릭에 반응)
    - 별점을 선택하면 좌측별점도 하이라이트
      - 예를들어 3번째 별점을 선택하면 1,2,3번째 별에 하이라이트
    - 우측에 선택한 별 갯수 만큼 숫자로 점수가 노출
  - 텍스트 입력
    - 글자수가 최소 5자에서 400자까지 등록
    - 400자 이상 입력이 되지 않도록 처리
    - 텍스트 입력박스에 선택을 하면(포커스를 주면) 숨겨져있던 입력창(textarea)이 화면에 노출되고 글쓰기가 가능
    - 입력을 하지 않고 입력창에서 포커스를 나가면 다시 원래의 콘텐츠가 노출
  - JavaScript - 별점과 Form조작
    - 리뷰쓰기의 별점 기능은 별도의 별점 컴포넌트로 개발 (prototype방식의 클래스로 작성)
    - form입력값은 유효성검증을 정규표현식을 사용해서 체크
  - JavaScript - 파일업로드
    - file upload시 이미지파일의 확장자체크는 자바스크립트로 체크
    - 썸네일 이미지 미리보기도 자바스크립트를 사용해서 구현



- **피드백  및 개선**
  - [프로젝트6. 예약관리 시스템: 한줄평(FE) PASS](https://seokr.tistory.com/688)



- **프로젝트 주의 사항**

  - *application.properties* 생성 (보안으로 깃에 업로드 안하도록 적용 되어 있음)

```properties
    spring.datasource.driver-class-name={db}
    spring.datasource.url={db url}
    spring.datasource.username={db username}
    spring.datasource.password={db password}
```
