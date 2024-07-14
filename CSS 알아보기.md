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


    
  


  

