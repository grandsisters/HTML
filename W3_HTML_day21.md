## HTML - 헤드 요소
HTML \<head>요소는 다음과 같은 요소의 컨테이너입니다 

: \<title>, \<style>, \<meta>, \<link>, \<script>, \<base>.

***
### HTML \<head> 요소
\<head>요소는 메타 데이터(데이터에 대한 데이터)에 대한 컨테이너이고 <html>태그와 <body>태그 사이에 위치 합니다.

HTML 메타데이터는 HTML 문서에 대한 데이터입니다. 메타데이터는 표시되지 않습니다.

메타데이터는 일반적으로 문서 제목, 문자 집합, 스타일, 스크립트 및 기타 메타 정보를 정의합니다.

***
### HTML \<title> 요소
\<title>요소는 문서의 제목을 정의합니다. 제목은 텍스트 전용이어야 하며 브라우저의 제목 표시줄이나 페이지의 탭에 표시됩니다.

\<title>요소는 HTML 문서에 필요합니다!

페이지 제목의 내용은 검색엔진최적화(SEO)에 매우 중요합니다! 

페이지 제목은 검색 엔진 알고리즘에서 검색 결과에 페이지를 나열할 때 순서를 결정하는 데 사용됩니다.

\<title>요소 :

- 브라우저 도구 모음에서 제목을 정의합니다.
- 즐겨찾기에 추가될 때 페이지의 제목을 제공합니다.
- 검색 엔진 결과에 페이지 제목을 표시합니다.

따라서 제목을 가능한 한 정확하고 의미 있게 만드십시오!

    예시
    <!DOCTYPE html>
    <html>
    <head>
    <title>A Meaningful Page Title</title>
    </head>
    <body>

    The content of the document......

    </body>
    </html>

***
### HTML \<style> 요소
\<style>요소는 하나의 HTML 페이지에 대한 스타일 정보를 정의하는 데 사용됩니다.

    예시
    <style>
        body {background-color: powderblue;}
        h1 {color: red;}
        p {color: blue;}
    </style>

***
### HTML \<link> 요소
\<link>요소는 현재 문서 및 외부 자원 사이의 관계를 정의한다. 

\<link>태그는 대부분 외부 스타일 시트에 연결하는 데 사용됩니다.

    예시
    <link rel="stylesheet" href="mystyle.css">

***
### HTML \<meta> 요소
\<meta>요소는 일반적으로 문자 집합, 페이지 설명, 키워드, 문서의 저자, 뷰포트 설정을 지정하는 데 사용됩니다.

메타데이터는 페이지에 표시되지 않지만 브라우저(콘텐츠 표시 또는 페이지 새로고침 방법), 검색 엔진(키워드) 및 기타 웹 서비스에서 사용됩니다.

예시

    사용된 문자 집합을 정의합니다.
    <meta charset="UTF-8">

    검색 엔진에 대한 키워드 정의:
    <meta name="keywords" content="HTML, CSS, JavaScript">

    웹 페이지에 대한 설명을 정의합니다.
    <meta name="description" content="Free Web tutorials">

    페이지 작성자 정의:
    <meta name="author" content="John Doe">

    30초마다 문서 새로 ​​고침:
    <meta http-equiv="refresh" content="30">

    웹사이트가 모든 기기에서 잘 보이도록 표시 영역 설정:
    <meta name="viewport" content="width=device-width, initial-scale=1.0">


    \<meta>태그의 예시

    <meta charset="UTF-8">
    <meta name="description" content="Free Web tutorials">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <meta name="author" content="John Doe">

***
### 뷰포트 설정
뷰포트는 웹 페이지에서 사용자가 볼 수 있는 영역입니다. 

기기에 따라 다릅니다. 

컴퓨터 화면보다 휴대전화에서 더 작습니다.

\<meta>모든 웹 페이지에 다음 요소를 포함해야 합니다.

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

이것은 페이지의 크기와 배율을 제어하는 ​​방법에 대한 브라우저 지침을 제공합니다.

width=device-width부분은 장치의 화면 폭을 따라 페이지의 폭을 설정한다.(기기에 따라 다름)

initial-scale=1.0부분은 페이지가 처음 브라우저에 의해로드 된 초기 줌 레벨을 설정합니다.

다음은 뷰포트 메타 태그가 없는 웹 페이지와 뷰포트 메타 태그가 있는 동일한 웹 페이지의 예 입니다.

<img src='./img/viewport_meta.png'>

팁: 휴대전화나 태블릿으로 이 페이지를 탐색하는 경우 아래 두 링크를 클릭하여 차이점을 확인할 수 있습니다.

***
### HTML \<script> 요소
\<script>요소는 클라이언트 측 자바 스크립트를 정의하는 데 사용된다.

다음 JavaScript는 id="demo"인 HTML 요소로 "Hello JavaScript!"를 작성합니다.

    예시
    <script>
        function myFunction() {
        document.getElementById("demo").innerHTML = "Hello JavaScript!";
        }
    </script>

***
### HTML \<base> 요소
\<base>요소는 페이지의 모든 상대 URL의 기본 URL 및 / 또는 대상을 지정합니다.

\<base>태그는 HREF 또는 대상 속성 존재 또는 둘 모두를 가져야한다.

문서에는 하나의 단일 \<base> 요소 만 있을 수 있습니다 !

    예시
    페이지의 모든 링크에 대한 기본 URL 및 기본 대상 지정:

    <head>
        <base href="https://www.w3schools.com/" target="_blank">
    </head>

    <body>
        <img src="images/stickman.gif" width="24" height="39" alt="Stickman">
        <a href="tags/tag_base.asp">HTML base Tag</a>
    </body>