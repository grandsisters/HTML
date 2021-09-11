## HTML 스타일 가이드 및 코딩 규칙
일관되고 깨끗하며 깔끔한 HTML 코드는 다른 사람들이 귀하의 코드를 더 쉽게 읽고 이해할 수 있도록 합니다.

다음은 좋은 HTML 코드를 만들기 위한 몇 가지 지침과 팁입니다.

***
### 항상 문서 유형 선언
항상 문서 유형을 문서의 첫 번째 줄로 선언하십시오.

HTML에 대한 올바른 문서 유형은 다음과 같습니다.

    <!DOCTYPE html>

***
### 소문자 요소 이름 사용
HTML은 요소 이름에 대문자와 소문자를 혼합할 수 있습니다.

그러나 다음과 같은 이유로 소문자 요소 이름을 사용하는 것이 좋습니다.

- 대문자와 소문자 이름을 혼합하면 보기 좋지 않습니다.
- 개발자는 일반적으로 소문자 이름을 사용합니다.
- 소문자가 더 깔끔해 보입니다.
- 소문자가 쓰기 쉽습니다.

    좋은:

        <body>
            <p>This is a paragraph.</p>
        </body>


    나쁜:

        <BODY>
            <P>This is a paragraph.</P>
        </BODY>

***
### 모든 HTML 요소 닫기
HTML에서는 모든 요소(예: \<p>요소) 를 닫을 필요가 없습니다 .

그러나 다음과 같이 모든 HTML 요소를 닫는 것이 좋습니다.

    좋은:
    <section>
        <p>This is a paragraph.</p>
        <p>This is a paragraph.</p>
    </section>

    나쁜:
    <section>
        <p>This is a paragraph.
        <p>This is a paragraph.
    </section>

***
### 소문자 속성 이름 사용
HTML은 속성 이름에 대문자와 소문자를 혼합할 수 있습니다.

그러나 다음과 같은 이유로 소문자 속성 이름을 사용하는 것이 좋습니다.

- 대문자와 소문자 이름을 혼합하면 보기 좋지 않습니다.
- 개발자는 일반적으로 소문자 이름을 사용합니다.
- 소문자 모양이 더 깔끔해집니다.
- 소문자가 쓰기 쉽습니다.

    좋은:

        <a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>

    나쁜:

        <a HREF="https://www.w3schools.com/html/">Visit our HTML tutorial</a>

***
### 항상 속성 값 인용
HTML은 따옴표 없이 속성 값을 허용합니다.

그러나 다음과 같은 이유로 속성 값을 인용하는 것이 좋습니다.

- 개발자는 일반적으로 속성 값을 인용합니다.
- 인용된 값은 더 읽기 쉽습니다.
- 값에 공백이 포함된 경우 따옴표를 사용해야 합니다.

    좋은:
        
        <table class="striped">

    나쁜:
        
        <table class=striped>

    아주 나쁜:
    값에 공백이 포함되어 있기 때문에 작동하지 않습니다.

        <table class=table striped>

***
### 항상 이미지의 Alt, 너비 및 높이 지정
항상 alt이미지 의 속성을 지정하십시오. 

이 속성은 어떤 이유로 이미지를 표시할 수 없는 경우에 중요합니다.

또한 항상 width및 height이미지를 정의하십시오. 

이렇게 하면 브라우저가 로드하기 전에 이미지를 위한 공간을 예약할 수 있으므로 깜박임이 줄어듭니다.

    좋은:
    <img src="html5.gif" alt="HTML5" style="width:128px;height:128px">

    나쁜:
    <img src="html5.gif">

***
### 공백 및 등호
HTML은 등호 주위에 공백을 허용합니다. 

그러나 space-less는 읽기 쉽고 엔터티를 더 잘 그룹화합니다.

    좋은:
    <link rel="stylesheet" href="styles.css">

    나쁜:
    <link rel = "stylesheet" href = "styles.css">

***
### 긴 코드 줄 피하기
HTML 편집기를 사용할 때 HTML 코드를 읽기 위해 좌우로 스크롤하는 것은 편리하지 않습니다.

너무 긴 코드 라인을 피하십시오.

***
### 빈 줄 및 들여쓰기
이유 없이 빈 줄, 공백 또는 들여쓰기를 추가하지 마십시오.

가독성을 위해 빈 줄을 추가하여 크거나 논리적인 코드 블록을 구분합니다.

가독성을 위해 들여쓰기를 두 칸 추가합니다. 탭 키를 사용하지 마십시오.

    좋은:
    <body>

    <h1>Famous Cities</h1>

    <h2>Tokyo</h2>
    <p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area,
    and the most populous metropolitan area in the world.
    It is the seat of the Japanese government and the Imperial Palace,
    and the home of the Japanese Imperial Family.</p>

    </body>

    나쁜:
    <body>

    <h1>Famous Cities</h1>

    <h2>Tokyo</h2>

    <p>
        Tokyo is the capital of Japan, the center of the Greater Tokyo Area,
        and the most populous metropolitan area in the world.
        It is the seat of the Japanese government and the Imperial Palace,
        and the home of the Japanese Imperial Family.
    </p>

    </body>

    좋은 테이블 예:
    <table>
    <tr>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>A</td>
        <td>Description of A</td>
    </tr>
    <tr>
        <td>B</td>
        <td>Description of B</td>
    </tr>
    </table>

    좋은 목록 예:
    <ul>
    <li>London</li>
    <li>Paris</li>
    <li>Tokyo</li>
    </ul>

***
### \<title> 요소를 건너뛰지 마십시오.
\<title>요소는 HTML에 필요합니다.

페이지 제목의 내용은 검색엔진 최적화(SEO)에 매우 중요합니다! 

페이지 제목은 검색 엔진 알고리즘에서 검색 결과에 페이지를 나열할 때 순서를 결정하는 데 사용됩니다.

\<title>요소 :
- 브라우저 도구 모음에서 제목을 정의합니다.
- 즐겨찾기에 추가될 때 페이지의 제목을 제공합니다.
- 검색 엔진 결과에 페이지 제목을 표시합니다.


따라서 제목을 가능한 한 정확하고 의미 있게 만드십시오. 

    <title>HTML Style Guide and Coding Conventions</title>

***
### \<html> 및 \<body> 생략?
HTML 페이지는 \<html>및 \<body>태그 없이 유효성을 검사 합니다.

    예시
    <!DOCTYPE html>
    <head>
    <title>Page Title</title>
    </head>

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>

그러나 항상 \<html>및 \<body>태그를 추가하는 것이 좋습니다 !

\<body>를 생략하면 이전 브라우저에서 오류가 발생할 수 있습니다.

\<body>과 마찬가지로 \<html>를 생략하는것 또한 DOM과 XML 소프트웨어를 충돌 할 수 있습니다.

***
### \<head> 생략?
HTML \<head> 태그도 생략할 수 있습니다.

브라우저는 \<body>, 이전의 모든 요소를 기본 \<head> 요소에 추가합니다 .

    예시
    <!DOCTYPE html>
    <html>
    <title>Page Title</title>
    <body>

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>

    </body>
    </html>

그러나 <head>태그를 사용하는 것이 좋습니다 .

***
### 빈 HTML 요소를 닫으시겠습니까?
HTML에서 빈 요소를 닫는 것은 선택 사항입니다.

    허용 된:
    <meta charset="utf-8">

    또한 허용됨:
    <meta charset="utf-8" />

XML/XHTML 소프트웨어가 페이지에 액세스할 것으로 예상되는 경우 닫는 슬래시(/)를 유지하십시오. 

이는 XML 및 XHTML에 필요하기 때문입니다.

***
### 언어 속성 추가
웹 페이지의 언어를 선언하려면 항상 \<html>태그 lang내부에 속성을 포함해야 합니다. 

이것은 검색 엔진과 브라우저를 지원하기 위한 것입니다.

    예시
    <!DOCTYPE html>
    <html lang="en-us">
    <head>
    <title>Page Title</title>
    </head>
    <body>

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>

    </body>
    </html>

***
### 메타 데이터
적절한 해석과 올바른 검색 엔진 인덱싱을 보장하려면 언어와 문자 인코딩 을 HTML 문서에서 가능한 한 빨리 정의해야 합니다. 

    기본형
    <meta charset="charset">

    예시
    <!DOCTYPE html>
    <html lang="en-us">
    <head>
    <meta charset="UTF-8">
    <title>Page Title</title>
    </head>

***
### 뷰포트 설정
뷰포트는 웹 페이지에서 사용자가 볼 수 있는 영역입니다. 

기기에 따라 다릅니다. 

컴퓨터 화면보다 휴대전화에서 더 작습니다.

\<meta>모든 웹 페이지에 다음 요소를 포함해야 합니다.

<meta name="viewport" content="width=device-width, initial-scale=1.0">

이것은 페이지의 크기와 배율을 제어하는 ​​방법에 대한 브라우저 지침을 제공합니다.

width=device-width부분 (기기에 따라 다름) 장치의 화면 폭을 따라 페이지의 폭을 설정한다.

이 initial-scale=1.0부분은 브라우저에서 페이지를 처음 로드할 때 초기 확대/축소 수준을 설정합니다.

다음은 뷰포트 메타 태그가 없는 웹 페이지 와 뷰포트 메타 태그가 있는 동일한 웹 페이지의 예 입니다 .

팁: 휴대전화나 태블릿으로 이 페이지를 탐색하는 경우 아래 두 링크를 클릭하여 차이점을 확인할 수 있습니다.

***
### HTML 주석
짧은 주석은 다음과 같이 한 줄로 작성해야 합니다.

    <!-- This is a comment -->

한 줄 이상의 주석은 다음과 같이 작성해야 합니다.

    <!--
    This is a long comment example. This is a long comment example.
    This is a long comment example. This is a long comment example.
    -->

긴 주석은 두 개의 공백으로 들여쓰기되어 있으면 더 쉽게 관찰할 수 있습니다.

***
### 스타일 시트 사용
스타일 시트에 연결하기 위해 간단한 구문을 사용하십시오( type속성은 필요하지 않음):

    <link rel="stylesheet" href="styles.css">

짧은 CSS 규칙은 다음과 같이 압축하여 작성할 수 있습니다.

    p.intro {font-family:Verdana;font-size:16em;}

긴 CSS 규칙은 여러 줄에 걸쳐 작성해야 합니다.

    body {
        background-color: lightgrey;
        font-family: "Arial Black", Helvetica, sans-serif;
        font-size: 16em;
        color: black;
    }

- 선택기와 같은 줄에 여는 대괄호를 놓습니다.
- 여는 대괄호 앞에 한 칸 띄우기
- 들여쓰기 두 칸 사용
- 마지막을 포함하여 각 속성-값 쌍 뒤에 세미콜론을 사용하십시오.
- 값에 공백이 포함된 경우에만 값 주위에 따옴표를 사용하십시오.
- 선행 공백 없이 새 줄에 닫는 대괄호 배치

***
### HTML에서 JavaScript 로드
외부 스크립트를 로드하는 데 간단한 구문을 사용합니다( type속성은 필요하지 않음).

    <script src="myscript.js">


***
### JavaScript로 HTML 요소에 접근하기
"정확하지 않은" HTML 코드를 사용하면 JavaScript 오류가 발생할 수 있습니다.

이 두 JavaScript 문은 다른 결과를 생성합니다.

    예시
    getElementById("Demo").innerHTML = "Hello";

    getElementById("demo").innerHTML = "Hello";

***
### 소문자 파일 이름 사용
일부 웹 서버(Apache, Unix)는 파일 이름에 대해 대소문자를 구분합니다. 

"london.jpg"는 "London.jpg"로 액세스할 수 없습니다.

다른 웹 서버(Microsoft, IIS)는 대소문자를 구분하지 않습니다. 

"london.jpg"는 "London.jpg"로 액세스할 수 있습니다.

대문자와 소문자를 혼용하여 사용하는 경우에는 이 점에 유의해야 합니다.

대소문자를 구분하지 않는 서버에서 대소문자를 구분하는 서버로 이동하면 작은 오류로도 웹이 손상됩니다!

이러한 문제를 방지하려면 항상 소문자 파일 이름을 사용하십시오!

***
### 파일 확장자
HTML 파일에는 .html 확장자 가 있어야 합니다 ( .htm 허용).

CSS 파일의 확장자 는 .css 여야 합니다.

JavaScript 파일에는 .js 확장자 가 있어야 합니다 .

***
### .htm과 .html의 차이점은 무엇입니까?
.htm과 .html 파일 확장자 사이에는 차이가 없습니다!

둘 다 모든 웹 브라우저와 웹 서버에서 HTML로 처리됩니다.

***
### 기본 파일 이름
URL이 끝에 파일 이름을 지정하지 않으면(예: "https://www.w3schools.com/"), 

서버는 "index.html", "index.htm", "default.html" 또는 "default.htm"와 같은 기본 파일 이름을 추가합니다. 

서버가 기본 파일 이름으로 "index.html"만 사용하여 구성된 경우 

파일 이름은 "default.html"이 아니라 "index.html"이어야 합니다.

그러나 서버는 둘 이상의 기본 파일 이름으로 구성할 수 있습니다. 

일반적으로 원하는 만큼 기본 파일 이름을 설정할 수 있습니다.