## HTML 자바스크립트
JavaScript는 HTML 페이지를 보다 동적이고 대화식으로 만듭니다.(dynamic and interactive)

[예시](./W3_HTML_day19-1.html)

***
### HTML \<script> 태그

HTML \<script>태그는 클라이언트 측 스크립트(JavaScript)를 정의하는 데 사용됩니다.

\<script>요소는 스크립트 문을 포함, 또는 src속성을 통해 외부 스크립트 파일을 가리킨다.

JavaScript의 일반적인 용도는 이미지 조작, 양식 유효성 검사 및 콘텐츠의 동적 변경입니다.

JavaScript는 HTML 요소를 선택하기 위해 가장 자주 document.getElementById()메서드를 사용합니다 .

이 JavaScript 예제는 id="demo"인 HTML 요소로 "Hello JavaScript!"를 작성합니다.

    예시
    <script>
    document.getElementById("demo").innerHTML = "Hello JavaScript!";
    </script>

***
### 자바스크립트 맛보기
다음은 JavaScript가 수행할 수 있는 몇 가지 예입니다.

JavaScript는 콘텐츠를 변경할 수 있습니다.

    예시
    document.getElementById("demo").innerHTML = "Hello JavaScript!";

JavaScript는 스타일을 변경할 수 있습니다.

    예시
    document.getElementById("demo").style.fontSize = "25px";
    document.getElementById("demo").style.color = "red";
    document.getElementById("demo").style.backgroundColor = "yellow";

JavaScript는 속성을 변경할 수 있습니다.

    예시
    document.getElementById("image").src = "picture.gif";

***
### HTML \<noscript> 태그
HTML \<noscript>태그는 브라우저에서 스크립트를 비활성화했거나 스크립트를 지원하지 않는 브라우저를 가진 사용자에게 표시할 대체 콘텐츠를 정의합니다.

    예시
    <script>
        document.getElementById("demo").innerHTML = "Hello JavaScript!";
    </script>
    
    <noscript>Sorry, your browser does not support JavaScript!</noscript>