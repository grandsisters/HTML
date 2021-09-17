## HTML Plug-ins

플러그인은 브라우저의 표준 기능을 확장하는 컴퓨터 프로그램입니다.

***
### 플러그인
플러그인은 다양한 용도로 사용하도록 설계되었습니다.

- Java 애플릿을 실행하려면
- Microsoft ActiveX 컨트롤을 실행하려면
- Flash 동영상을 표시하려면
- 지도를 표시하려면
- 바이러스를 검사하려면
- 은행 ID를 확인하려면


    경고 !

    대부분의 브라우저는 더 이상 Java 애플릿 및 플러그인을 지원하지 않습니다.

    ActiveX 컨트롤은 더 이상 브라우저에서 지원되지 않습니다.

    Shockwave Flash에 대한 지원도 최신 브라우저에서 해제되었습니다.

***
### \<object> 요소
\<object>요소는 모든 브라우저에서 지원됩니다.

\<object>요소는 HTML 문서 내에 포함 된 개체를 정의합니다.

플러그인(Java 애플릿, PDF 리더, Flash Player 등)을 웹 페이지에 포함하도록 설계되었지만 HTML에 HTML을 포함하는 데 사용할 수도 있습니다.

    예시
    <object width="100%" height="500px" data="snippet.html"></object>

    또는 원하는 경우 이미지:

    예시
    <object data="audi.jpeg"></object>

***
### \<embed> 요소
\<embed>요소는 모든 주요 브라우저에서 지원됩니다.

\<embed>요소는 HTML 문서 내에 포함 된 개체를 정의합니다.

웹 브라우저는 오랫동안 \<embed> 요소를 지원해 왔습니다. 그러나 HTML5 이전에는 HTML 사양의 일부가 아니었습니다.

    예시
    <embed src="audi.jpeg">
    <embed> 요소에는 닫는 태그가 없습니다. 대체 텍스트를 포함할 수 없습니다.

    <embed>요소는 HTML에 HTML을 포함 할 수 있습니다 :

    예시
    <embed width="100%" height="500px" src="snippet.html">
