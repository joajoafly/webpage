# 😍CSS 스타일 시트와 선택자
### CSS 형식
## 선택자  { 속성1: 속성값1;  속성2: 속성값2  }

* 선택자 : 스타일을 어느 태그에 적용할지 지정
* 속성 : 스타일 이름. 속성값 : 속성의 값
* 속성과 속성값은 콜론(:)으로 구분. 속성과 속성은 세미콜론(;)으로 구분
* 주석 : 코드 설명    /* 주석*/
* 대소문자 구분 없음

  
### 스타일 적용하기



    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CSS연습</title>
        <style>
            h2 {background-color: blueviolet;       /* 내부 스타일 시트 */
            color: white;
        }
        </style>
        <link rel="stylesheet" href = "4_style.css">     <!--- 외부 스타일 시트 적용 -->
    </head>
    <body>
        <h1 style="color:blue;">인라인 스타일 적용하기</h1>       <!-- 인라인 스타일 적용-->  
        <h2> 내부 스타일 시트 적용하기</h2>
        <p>외부 스타일 시트 적용하기</p>  
    </body>
    </html>
    



 ### 스타일 적용하기 : CSS 문서(style.css)


    p{
    color:red;
    background-color: yellow;
    }


 ### CSS 기본 선택자
 #### 전체 선택자  : 모든 요소에 스타일 적용
      * {    css코드      }

 #### 태그 선택자    : 지정된 태그에 스타일 적용
      태그명 {     css 코드    }

 #### 클래스 선택자   : class 속성값으로 지정, 마침표(.) 을 붙여 사용
     .class 속성값 {   css코드    }

 #### 아이디 선택자 : id 속성값으로 지정. 샵(#)을 붙여 사용
     #id 속성값 {    css코드    }
  

 #### 그룹 선택자  : 여러 선택자를 그룹으로 묶어 지정
    선택자1, 선택자2, ....  {    css코드    }

 #### 자식 선택자 : 부모 요소에 포함된 자식 요소만 선택하여 지정 >으로 구분
    부모선택자 > 자식 선택자  {    css코드    }
    
 #### 하위 선택자 : 상위요소에 포함된 모든 하위 요소를 지정. 공백으로 구분
    상위요소 하위요소...  {    css코드    }

 ### 🐾웹 폰트 사용하기 
  https://fonts.google.com/ 
  원하는 폰트 검색하여 선택 -> embed code -> import


#### 내부 스타일 시트에서 적용하기 (html파일)

    <style>        
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100..900&display=swap');
         * {
        font-family : "Noto Sans KR", sans-serif; 
        font-size : 20px; 
        letter-spacing : 1px;
        }
    </style>


### 외부 스타일 시트에서 적용하기
#### html파일에 추가하기
    <link rel="stylesheet" href = "style.css">

### css 파일에 추가하기
    @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100..900&display=swap');
     * {
        font-family : "Noto Sans KR", sans-serif; 
        font-size : 20px; 
        letter-spacing : 1px;
        }
    

# 🎆 홈페이지 CSS추가하여 꾸미기
### 상단바에 색상과 버튼 소성 설정하기(mystyle.css)


    header {
    background-color: #333;
    color: #fff;
    }
    /** 제목 **/
    .main-title {
        font-size: 30px;
    }
    
    /** 내비게이션 **/
    li {
        list-style: none;       /* 리스트 스타일 제거 */
    }
    .nav-btn {
        color: #fff;            /* 버튼 글자색 */
        background-color: #555; /* 버튼색 */
        border: none;             /* 테두리 제거 */
    }
    .nav-btn:hover {
        background-color: #777; /*마우스 올릴때 버튼색*/
    }


### 메인 섹션에 배경 이미지 추가 및 폰트 설정

   #main {
    color: white;        /* 텍스트 색상을 흰색으로 설정 */
    background: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), 
                url('source/train.jpg') center center; 
                            /* 배경색이 이미지를 덮는 효과 */
    background-size: cover; /* 배경 이미지 화면 가득 채우기 */
    }
    #main h4{
        font-size: 25px;
    }
    #main h5{
        font-size: 40px;
    }


## 갤러리 섹션에 이미지 추가 및 사이즈 설정

### myhome.html


      <div>
          <img src="source/gal01.jpg" alt="" id="big">
      </div>
      <div>
          <img src="source/gal01.jpg" class="picture">
          <img src="source/gal02.jpg" class="picture">
          <img src="source/gal03.jpg" class="picture">
          <img src="source/gal04.jpg" class="picture">
          <img src="source/gal05.jpg" class="picture">
          <img src="source/gal06.jpg" class="picture">
      </div>


### style.css   


    /** section-gallery  **/
    #gallery #big {
        width: 600px;
    }
    #gallery .picture {
        width: 60px;
    }


# 박스 모델
![스크린샷 2024-07-14 154203](https://github.com/user-attachments/assets/a3717135-e060-4876-ba6d-944c69fdbbe0)
