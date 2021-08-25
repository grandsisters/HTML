## HTML 요소

HTML 요소는 시작 태그, 일부 콘텐츠 및 종료 태그로 정의됩니다.

***
### HTML 요소

<br>

HTML 요소 는 시작 태그에서 종료 태그까지의 모든 것입니다.

    < h1 > 나의 첫 번째 제목 < /h1 >
    < p > 나의 첫 단락. < /p >


|Start tag|Element content|End tag|
|-|-|-|
|\<h1>|My First Heading|\</h1>|
|\<p>|My first paragraph.|\</p>|
|\<br>|none|none|

참고: 일부 HTML 요소에는 콘텐츠가 없습니다(예: \<br> 요소). 

이러한 요소를 빈 요소라고 합니다. 빈 요소에는 끝 태그가 없습니다!

***
### 중첩된 HTML 요소

<br>

HTML 요소는 중첩될 수 있습니다(즉, 요소에 다른 요소가 포함될 수 있음).

모든 HTML 문서는 중첩된 HTML 요소로 구성됩니다.

다음 예제에는 4개의 HTML 요소( \<html>, \<body>, \<h1> 및 \<p>) 가 포함되어 있습니다 .


    <!DOCTYPE html>
    <html>
    <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

    </body>
    </html>

예시 설명

\<html>요소는 루트 요소이며 전체 HTML 문서를 정의합니다.

시작 태그 \<html>와 종료 태그가 \</html>있습니다.

그런 다음 \<html>요소 내부에 요소가 있습니다 \<body> .

    예시1


    <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

    </body>


\<body>요소는 문서의 본문을 정의합니다.

시작 태그 \<body>와 종료 태그가 \</body>있습니다.

그리고, 내부 \<body>요소가 다른 두 요소는 다음 \<h1>과 \<p>:

    예시2

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
    <h1>요소는 제목을 정의합니다.

시작 태그 \<h1>와 종료 태그가 있습니다 \</h1>.

\<p>요소는 문단을 정의합니다.

시작 태그 \<p>와 종료 태그가 있습니다 \</p>.

***
### 끝 태그를 건너뛰지 마십시오.

<br>

종료 태그를 잊어버린 경우에도 일부 HTML 요소는 올바르게 표시됩니다.

그러나 이것에 절대 의존하지 마십시오! 종료 태그를 잊어버리면 예기치 않은 결과와 오류가 발생할 수 있습니다!

***
### 빈 HTML 요소

<br>

내용이 없는 HTML 요소를 빈 요소라고 합니다.

\<br>태그는 줄 바꿈을 정의하고, 닫는 태그가없는 빈 요소입니다 :

    예시

    <p>This is a <br> paragraph with a line break.</p>

***
### HTML은 대소문자를 구분하지 않습니다

<br>

HTML 태그는 대소문자를 구분하지 않습니다 . \<P>와 동일함을 의미합니다 \<p>.

HTML 표준은 소문자 태그를 요구하지 않지만 W3C 는 HTML에서 소문자를 권장 하고 

XHTML과 같은 더 엄격한 문서 유형에 대해 소문자를 요구 합니다.

[HTML 요소 참조](https://www.w3schools.com/tags/default.asp)