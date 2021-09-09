## HTML Iframes

HTML iframe은 웹 페이지 내에 웹 페이지를 표시하는 데 사용됩니다.

***
### HTML 아이프레임 구문
HTML \<iframe>태그는 인라인 프레임을 지정합니다.

인라인 프레임은 현재 HTML 문서 내에 다른 문서를 포함하는 데 사용됩니다.

    기본형
    <iframe src="url" title="description"></iframe>

팁: 항상 \<iframe>에 title속성을 포함하는 것이 좋습니다. 이것은 스크린 리더가 iframe의 내용을 읽는 데 사용합니다.

***
### Iframe - 높이 및 너비 설정
사용 height및 widthiframe을의 크기를 지정하는 속성.

높이와 너비는 기본적으로 픽셀 단위로 지정됩니다.

    예시
    <iframe src="demo_iframe.html" height="200" width="300" title="Iframe Example"></iframe>
    
또는 style속성을 추가 하고 CSS height및 width 속성을 사용할 수 있습니다 .

    예시
    <iframe src="demo_iframe.html" style="height:200px;width:300px;" title="Iframe Example"></iframe>

***
### Iframe - 테두리 제거
기본적으로 iframe에는 테두리가 있습니다.

테두리를 제거하려면 style속성을 추가 하고 CSS border속성을 사용하세요 .

    예시
    <iframe src="demo_iframe.htm" style="border:none;" title="Iframe Example"></iframe>

CSS를 사용하면 iframe 테두리의 크기, 스타일 및 색상을 변경할 수도 있습니다.

    예시
    <iframe src="demo_iframe.htm" style="border:2px solid red;" title="Iframe Example"></iframe>

***
### Iframe - 링크 대상
iframe은 링크의 대상 프레임으로 사용할 수 있습니다.

target링크의 속성은 반드시 iframe의 name속성을 참조해야합니다.

    예시
    <iframe src="demo_iframe.htm" name="iframe_a" title="Iframe Example"></iframe>

    <p><a href="https://www.w3schools.com" target="iframe_a">W3Schools.com</a></p>