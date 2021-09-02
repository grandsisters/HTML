## HTML 링크

링크는 거의 모든 웹 페이지에서 찾을 수 있습니다. 링크를 통해 사용자는 페이지에서 페이지로 이동할 수 있습니다.

***
### HTML 링크 - 하이퍼링크
HTML 링크는 하이퍼링크입니다.

링크를 클릭하면 다른 문서로 이동할 수 있습니다.

링크 위로 마우스를 이동하면 마우스 화살표가 작은 손 모양으로 바뀝니다.

참고: 링크는 텍스트일 필요가 없습니다. 링크는 이미지 또는 기타 HTML 요소가 될 수 있습니다!

***
### HTML 링크 - 구문
HTML \<a>태그는 하이퍼링크를 정의합니다. 다음 구문이 있습니다.

\<a href="url">link text</a>
요소 의 가장 중요한 속성은 링크의 목적지를 나타내는 속성입니다.\<a> href

'link text'는 독자에게 표시되는 부분입니다.

'link text'를 클릭하면 지정된 URL 주소로 전송됩니다.

예시
이 예에서는 W3Schools.com에 대한 링크를 만드는 방법을 보여줍니다.

    <a href="https://www.w3schools.com/">Visit W3Schools.com!</a>

기본적으로 링크는 모든 브라우저에서 다음과 같이 표시됩니다.

- 방문하지 않은 링크는 밑줄과 파란색
- 방문한 링크는 밑줄과 보라색으로 표시됩니다.
- 활성 링크는 밑줄과 빨간색으로 표시됩니다.

팁: 링크는 물론 CSS로 스타일을 지정하여 다른 모습을 얻을 수 있습니다!


***
### HTML 링크 - 대상 속성
기본적으로 링크된 페이지는 현재 브라우저 창에 표시됩니다. 이를 변경하려면 링크에 대해 다른 대상을 지정해야 합니다.

target속성 지정은 어디에서 링크 된 문서를 엽니다.

target속성은 다음 값 중 하나를 사용할 수 있습니다 :

- _self- 기본값으로, 클릭한 것과 동일한 창/탭에서 문서를 엽니다.
- _blank - 새 창이나 탭에서 문서를 엽니다.
- _parent - 상위 프레임에서 문서를 엽니다.
- _top - 창의 전체 본문에서 문서를 엽니다.

예시
target="_blank"를 사용하여 새 브라우저 창이나 탭에서 연결된 문서를 엽니다.

    <a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

***
### 절대 URL과 상대 URL
위의 두 예 모두 속성에 절대 URL (전체 웹 주소)을 사용하고 href있습니다.

로컬 링크(동일한 웹사이트 내의 페이지에 대한 링크)는 

상대 URL ("https://www" 부분 제외)로 지정됩니다.

    예시
    <h2>Absolute URLs</h2>
    <p><a href="https://www.w3.org/">W3C</a></p>
    <p><a href="https://www.google.com/">Google</a></p>

    <h2>Relative URLs</h2>
    <p><a href="html_images.asp">HTML Images</a></p>
    <p><a href="/css/default.asp">CSS Tutorial</a></p>

***
### 절대 URL 및 상대 URL에 대한 추가 정보

    예시
    전체 URL을 사용하여 웹페이지에 링크: 

    <a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>

    예시
    현재 웹 사이트의 html 폴더에 있는 페이지 링크: 

    <a href="/html/default.asp">HTML tutorial</a>

    예시
    현재 페이지와 동일한 폴더에 있는 페이지에 대한 링크: 

    <a href="default.asp">HTML tutorial</a>

***
### HTML 링크 - 이미지를 링크로 사용
이미지를 링크로 사용하려면 \<img> 태그 안에 태그를 넣으면 됩니다 \<a>.

    예시
    <a href="default.asp">
    <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
    </a>

***
### 이메일 주소 링크
새 이메일을 보낼 수 있도록 하기 위해 속성 mailto:내부를 사용 href하여 사용자의 이메일 프로그램을 여는 링크를 생성합니다

    예시
    <a href="mailto:someone@example.com">Send email</a>

***
### 링크로서의 버튼
HTML 버튼을 링크로 사용하려면 JavaScript 코드를 추가해야 합니다.

JavaScript를 사용하면 버튼 클릭과 같은 특정 이벤트에서 발생하는 일을 지정할 수 있습니다.

    예시
    <button onclick="document.location='default.asp'">HTML Tutorial</button>

***
### 링크 제목
title속성은 요소에 대한 추가 정보를 지정합니다. 

정보는 마우스가 요소 위로 이동할 때 도구 설명 텍스트로 가장 자주 표시됩니다.

    예시
    <a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>