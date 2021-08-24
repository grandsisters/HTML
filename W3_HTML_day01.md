## HTML 기본

***
### HTML 문서

<br>

모든 HTML 문서는 문서 유형 선언으로 시작해야 합니다 \<!DOCTYPE html>.

HTML 문서 자체는 로 시작 \<html>하고 로 끝납니다 \</html>.

HTML 문서의 보이는 부분은 \<body>과 사이 에 \</body>있습니다.

    <!DOCTYPE html>
    <html>
    <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

    </body>
    </html>

***
### <!DOCTYPE> 선언

<br>


\<!DOCTYPE>선언은 문서 유형을 나타내며 올바르게 표시 웹 페이지에 브라우저를하는 데 도움이됩니다.

페이지 상단(HTML 태그 앞)에 한 번만 나타나야 합니다.

\<!DOCTYPE>선언은 대소 문자를 구분하지 않습니다.

\<!DOCTYPE>HTML5에 대한 선언은 다음과 같습니다.

    <!DOCTYPE html>

***
### HTML 제목

<br>

HTML 제목은 \<h1>to \<h6>태그 로 정의됩니다 .

\<h1>가장 중요한 제목을 정의합니다. 

\<h6>가장 덜 중요한 제목을 정의합니다. 

    <h1>This is heading 1</h1>
    <h2>This is heading 2</h2>
    <h3>This is heading 3</h3>


***
### HTML 단락

<br>

HTML 단락은 다음 \<p>태그 로 정의됩니다 .

    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>


***
### HTML 링크

<br>

HTML 링크는 다음 \<a>태그 로 정의됩니다 .

    <a href="https://www.w3schools.com">This is a link</a>

링크의 대상은 href속성에 지정됩니다 . 

속성은 HTML 요소에 대한 추가 정보를 제공하는 데 사용됩니다.

속성에 대한 자세한 내용은 이후 장에서 배우게 됩니다.

***
### HTML 이미지

<br>

HTML 이미지는 \<img>태그 로 정의됩니다 .

소스 파일( src), 대체 텍스트( alt) width, 및 height속성으로 제공됩니다.

    <img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">