# 🧭웹 (Web)
* 월드 와이드 웹(World Wide Web)이란 인터넷에 연결된 사용자들이 서로의 정보를 공유할 수 있는 공간을 의미
* 1989년 팀 버너스리가 연구원 간에 아이디어를 주고받을 때 파일을 통해 주고받는 것이 비효율적이라고 생각하여 공통된 공간에 각자의 정보를 올리고 관리하는 정보 관리 시스템에서 시작됨
* 웹은 관리자가 존재하지는 않지만, 월드 와이드 웹 컨소시엄(W3C)라는 국제 기구에서 HTML이나 CSS, XML 등과 같은 웹 언어나 인터넷 프로토콜에 대한 공개 웹 표준을 제정하고 관리하는 역할을 수행

### 웹 프론트엔드 
* HTML : 웹 페이지의 구조와 내용
* CSS  : 웹 페이지의 모양
* JAVASCRIPT : 웹 페이지의 동작

### HTML
* HTML은 Hyper Text Markup Language의 약자
* HTML은 웹 페이지를 만드는 표준 마크업 언어
* HTML은 웹 페이지의 구조를 설명

### HTML 요소

    <!DOCTYPE html>                      <!--이 문서가 HTML5 문서임을 정의 -->
    <html>                               <!-- HTML 페이지의 루트 요소 -->
    <head>  </head>                      <!-- HTML 페이지에 대한 메타 정보를 포함 -->
    <title > 웹 페이지 제목 </title>      <!-- HTML 페이지의 제목을 지정 -->
    <body>                               <!--문서의 본문을 정의하며 모드 표시되는 콘텐츠의 컨테이너 -->
    <h1> 미래의 홈페이지</h1>            <!-- 큰 제목을 정의 -->
    <p> 첫 문단입니다. </p>           <!-- 문단을 정의 -->
    </body>
    </html>

### VSCode 설치
https://code.visualstudio.com/


# 🎆시맨틱 태그
* header : 헤더영역
* nav : 내비게이션 영역
* main : 핵심 콘텐츠
* article : 독립 콘텐츠
* section : 콘텐츠 영역
* aside : 사이드바 영역
* footer : 푸터 영역
* div : 논리적 영역 구별

### myhome.html 파일 생성
<title> 태그 안의 텍스트를 나의 웹 사이트 이름으로 수정

    <!DOCTYPE html>
    <html lang="ko">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>채움공간</title>
        <link rel="stylesheet" href="mystyle.css">
    </head>
    <body>


### 시맨틱 구조에 맞게 <body> 태그 안을 구성


       <body>
            <header>
                <div></div>
                <nav>
                </nav>
            </header>    
            <section id="main"></section>
            <section id="about"></scection>
            <section id="favorite"></section>
            <section id="gallery"></section>
            <section id="contact"></section>
            <footer></footer>
        </body>


### h1~h6​  태그 : 제목
h1은 주로 타이틀 제목으로 쓴다.
h2 h3 h4 h5 h6 순으로 작아지고, 순서대로 써야한다.

### p  태그 : 문단
독립된 문단을 표현할 때 사용한다.

    <h1>제목1</h1>
    <p>첫번째 문단을 구성합니다.</p>
    <p>두번째 문단을 구성합니다.</p>


### br 태그  : 줄바꿈

    <p>원하는 위치에서<br>줄 바꿈을 할 수 있습니다.</p>
    <p>두 번 사용하면<br><br>빈 줄을 만들 수 있습니다.</p>


### hr 태그 :  구분선
구분할 수 있도록 선이 그어진다.

    <h3>제목3</h3>
    <hr>
    <p>hr은 horizontal의 약자입니다.</p>
    <hr>
    <p>종료태그 없이 사용합니다.</p>


### strong , b 태그   : 텍스트 굵게 표시

    
    <p>텍스트를 <strong>강조</strong>할 때 사용</p>
    <p>b는 <b>bold</b>의 약자입니다</p>


### em , i 태그 : 텍스트 기울여 표시
    <p>em은 <em>emphasis</em>의 줄임말</p>
    <p>i는 기울기체를 뜻하는 <i>italic</i>의 줄임말</p>


# 리스트 만들기
### ol, li 태그 : 순서있는 리스트

    <ol>
        <li>첫번째 리스트</li>
        <li>두번째 리스트</li>
        <li>세번째 리스트</li>
    </ol>


### ul, li 태그 : 순서 없는 리스트

    
    <ul>
        <li>첫번째 리스트</li>
        <li>두번째 리스트</li>
        <li>세번째 리스트</li>
    </ul>


### dl, dt, dd 태그  : 용어를 설명하는 형태 리스트


    <dl>
        <dt>첫번째 용어</dt>
        <dd>첫번째 용어 설명</dd>
        <dt>두번째 용어</dt>
        <dd>두번째 용어 설명</dd>
    </dl>


# 🗺️하이퍼 링크 만들기


    







   
    

  
