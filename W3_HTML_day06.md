## HTML 스타일

HTML style속성은 색상, 글꼴, 크기 등과 같은 요소에 스타일을 추가하는 데 사용됩니다.

***
### HTML 스타일 속성

HTML 요소의 스타일을 설정하는 것은 style속성을 사용하여 수행할 수 있습니다.

HTML style속성의 구문은 다음과 같습니다.

    <tagname style="property:value;">

속성은 CSS의 속성입니다. 값은 CSS의 값입니다.

***
### 배경색

CSS background-color속성은 HTML 요소의 배경색을 정의합니다.

    예시
    페이지의 배경색을 powderblue로 설정합니다.

    <body style="background-color:powderblue;">

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>

    </body>


    예시2
    두 개의 다른 요소에 대한 배경색 설정:

    <body>

    <h1 style="background-color:powderblue;">This is a heading</h1>
    <p style="background-color:tomato;">This is a paragraph.</p>

    </body>

***
### 텍스트 색상
CSS color속성은 HTML 요소의 텍스트 색상을 정의합니다.

    예시
    <h1 style="color:blue;">This is a heading</h1>
    <p style="color:red;">This is a paragraph.</p>

***
### 글꼴
CSS font-family속성은 HTML 요소에 사용할 글꼴을 정의합니다.

    예시
    <h1 style="font-family:verdana;">This is a heading</h1>
    <p style="font-family:courier;">This is a paragraph.</p>

***
### 텍스트 크기
CSS font-size속성은 HTML 요소의 텍스트 크기를 정의합니다.

    예시
    <h1 style="font-size:300%;">This is a heading</h1>
    <p style="font-size:160%;">This is a paragraph.</p>

***
### 텍스트 정렬
CSS text-align속성은 HTML 요소의 수평 텍스트 정렬을 정의합니다.

    예시
    <h1 style="text-align:center;">Centered Heading</h1>
    <p style="text-align:center;">Centered paragraph.</p>
