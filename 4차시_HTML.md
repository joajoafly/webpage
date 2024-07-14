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


# 📅리스트 만들기
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
### a 태그 


    <a href="링크 주소" target="연결 방식" title="설명"></a>


### img 태그 : 이미지 삽입

    <img src="이미지 파일 경로" alt="대체 텍스트">


### 멀티미디어 삽입하기
파일 경로는 웹 문서와 이미지 파일이 같은 폴더에 있다면 파일 이름을 하위 폴더에 있다면 폴더명과 함께 파일을 작성

* object 태그 : pdf 등 다양한 문서 파일

  
      <object width="너비" height="높이" data="파일"></object>


  
* embed 태그 : 오디오, 비디오, 이미지 등 다양한 멀티미디어 파일

  
      <embed src="파일 경로" width="너비" height="높이">


  
* audio 태그 : mp3 등의 오디오 파일

  
      <audio src="오디오 파일 경로”></audio> 



* video 태그 : mp4 등의 비디오 파일

  
      <video src="비디오 파일 경로”></video> 


# 🎆 홈페이지 구성 예제
### 상단바에 내비게이션 메뉴 리스트 만들기


        <header>
        <h1 class="main-title">채움공간</h1>
        <nav>
            <ul>
                <li><button class="nav-btn">ABOUT</button></li>
                <li><button class="nav-btn">FAVORITE</button></li>
                <li><button class="nav-btn">GALLERY</button></li>
                <li><button class="nav-btn">CONTACT</button></li>
            </ul>       
        </nav>
        </header>
      


### 홈 화면에 환영 인사 작성하기


         <section id="main">
            <div>
                <h4>환영합니다</h4>
                <h5>WELCOME</h5>
                <h4>🎨🧸❤️🪇📸</h4>
                <p id="autotype">여기는 채움이네 공간입니다</p>
            </div>
        </section><!--/#main -->


### 소개 화면(aboutt)에 나를 표현하는 이미지와 글 작성하기


      <section id="about">
            <h2 class="section-title">ABOUT</h2>
            <img src="source/polaroid.png" alt="내사진" width="400px">
            <p>
                맛있는거 먹고 배 채우기<br>
                새로운 지식으로 머리 채우기<br>
                친구들 만나서 마음 채우기<br>
                채우기를 좋아하는 채움이네 공간
            </p>
        </section>


### 갤러리 화면 (gallery)에 이미지 삽입과 각 섹션에 제목 작성하기



    <section id="favorite">
        <h2 class="section-title">FAVORITE</h2>        
    </section>
    <section id="gallery">
        <h2 class="section-title">GALLERY</h2>
        <div>
            <img src="source/gal01.jpg" alt="" id="big">
        </div>
    </section>
    <section id="contact">
        <h2 class="section-title">CONTACT</h2>
    </section>


### 하단바 작성하기

     <footer>
        <p>&copy; 2024 채움공간. All rights reserved.</p>
    </footer>


 # 📅HTMl 표와 폼 만들기
 ### 표 만들기
 <img src = https://github.com/user-attachments/assets/3f2aa2f7-0522-4eb3-a04f-4a1d01e9e0d7 width=500px><br>
표를 작성하고 행과 열을 병합


    <table border="1">
        <caption>표 제목</caption>
        <tr>
            <th>1열 제목</th>
            <th>2열 제목</th>
            <th>3열 제목</th>
        </tr>
        <tr>
           <td rowspan="2">1행 1열</td>
           <td>1행 2열</td>
           <td>1행 3열</td>
        </tr>
        <tr>
            <td>2행 2열</td>
            <td>2행 3열</td>
        </tr>
        <tr>
            <td colspan="3">3행 1열</td>
        </tr>
    </table>

    

# 🙌 폼 만들기
### 기본 구조


    <form action="서버 url" method="get 또는 post"></form>


### input 태그
사용자가 입력한 정보를 받는 한 줄짜리 입력 요소


    <input type="종류" name="이름" value="서버전송값"></input>

### 폼의 다양한 입력 종류


    <form action="" method="get">
        이메일 :<input type="email" name="email"><br>
        URL :<input type="url" name="url"><br>
        전화번호 : <input type="tel" name="tel"><br>
        색상 : <input type="color" name="color"><br>
        월 : <input type="month" name="month"><br>
        날짜 : <input type="date" name="date"><br>
        주 :<input type="week" name="week"><br>
        시간 : <input type="time" name="time"><br>
        지역 시간 : <input type="datetime-local" name="localdatetime"><br>
        숫자 :<input type="number" name="number" min="1" max="10" step="2"><br>
        범위 :<input type="range" name="range" min="1" max="10" step="2"><br>
        <hr>
        성별:
        <input type="radio" name="gender" value="male">남성
        <input type="radio" name="gender" value="female">여성<br><hr>
        학년 선택:
        <input type="checkbox" name="grade" value="1" checked>1학년
        <input type="checkbox" name="grade" value="2">2학년
        <input type="checkbox" name="grade" value="3">3학년<br>
        <input type="submit" value="제출">
    </form>


### 단일 선택 라디오 버튼


    성별
        <input type ="radio" name="gender" value="male">남성
        <input type="radio" name="gender" value="female">여성



### 다중 선택 체크박스


    과일 선택:
        <input type="checkbox" name="fruits" value="apple" checked>Apple
        <input type="checkbox" name="fruits" value="banana">Banana
        <input type="checkbox" name="fruits" value="lemon">lemon



### label 태그 
폼 요소에 레이블 만들기


    <label for="userid">아이디(중복불가)
    <input type="text" id="userid">
    </label>


### select, option, optgroup 태그
선택지를 클릭하면 펼쳐지는 콤보 박스


    <select>
        <optgroup label="옵션선택">
            <option value="서버전송값1">옵션1</option>
            <option value="서버전송값2">옵션1</option>
            <option value="서버전송값3">옵션1</option>
        </optgroup>
    </select>


     
# 🎆홈페이지에 표 추가하기
### 관심 화면(favorite 섹션)에 내가 좋아하는 관심 주제 표로 작성하기


        <section id="favorite">
            <h2 class="section-title">FAVORITE</h2>
            <table border="1">
                <tr>
                    <td> <div class="content">
                        <h3>HTML5</h3><br>
                        <p>웹 페이지의 구조를 정의하는 스크립트 언어이다.</p>
                    </div>
                    </td>
                    <td> <div class="content">
                        <h3>CSS3</h3><br>
                        <p>HTML로 작성된 웹 페이지에 디자인을 추가한다.</p>
                    </div>
                    </td>
                    <td> <div class="content">
                        <h3>JAVASCRIPT</h3><br>
                        <p>웹 페이지의 동적인 기능을 담당한다.</p>
                    </div>
                    </td></tr>
                </tr>
            </table>
        </section>


   ### 연락 화면에 웹 사이트를 사용자에게서 받을 메시지 폼 작성


     <section id="contact">
        <h2 class="section-title">CONTACT</h2>
        <form action="#" method="post" class="contact-form">
            <div class="form=group">
                <label for="name">이름:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form=group">
                <label for="phone">전화번호</label>
                <input type="tel" id="phone" name="phone" >
            </div>
            <div class="form=group">
                <label for="email">이메일:</label>
                <input type="email" id="email" name="email">
            </div>
            <div class="form=group">
                <label for="mesage">메시지:</label>
                <textarea type="message" id="message" rows="4"></textarea>
            </div>
            <button type="submit">전송</button>
        </form>
    </section>
    




    







   
    

  
