## HTML 이미지
이미지는 웹 페이지의 디자인과 모양을 향상시킬 수 있습니다.

    예시
    <img src="pic_trulli.jpg" alt="Italian Trulli">

    예시
    <img src="img_girl.jpg" alt="Girl in a jacket">

    예시
    <img src="img_chania.jpg" alt="Flowers in Chania">

***
### HTML 이미지 구문
HTML \<img>태그는 웹 페이지에 이미지를 삽입하는 데 사용됩니다.

이미지는 기술적으로 웹 페이지에 삽입되지 않습니다. 

이미지는 웹 페이지에 링크됩니다. 

- \<img>태그는 참조 된 이미지에 대한 유지 공간을 만듭니다.

- \<img>태그는 속성 만 포함하고, 닫는 태그가없습니다.

- \<img>태그는 두 개의 필수 속성이 있습니다

src - 이미지의 경로를 지정합니다.

alt - 이미지의 대체 텍스트를 지정합니다.

    기본형
    <img src="url" alt="alternatetext">

***
### src 속성
필수 src속성은 이미지의 경로(URL)를 지정합니다.

참고: 웹 페이지가 로드될 때, 그 순간에 웹 서버에서 이미지를 가져와 페이지에 삽입하는 것은 브라우저입니다. 

따라서 이미지가 실제로 웹 페이지와 관련하여 동일한 위치에 있는지 확인하십시오. 

그렇지 않으면 방문자에게 깨진 링크 아이콘이 표시됩니다. 

alt브라우저에서 이미지를 찾을 수 없는 경우 깨진 링크 아이콘과 텍스트가 표시됩니다.

    예시
    <img src="img_chania.jpg" alt="Flowers in Chania">


***
### 대체 속성
필수 alt속성은 사용자가 어떤 이유로 이미지를 볼 수 없는 경우

(느린 연결, src 속성의 오류 또는 사용자가 화면 판독기를 사용하는 경우) 

이미지에 대한 대체 텍스트를 제공합니다.

alt속성 값은 이미지를 설명해야 합니다.

    예시
    <img src="img_chania.jpg" alt="Flowers in Chania">

브라우저에서 이미지를 찾을 수 없으면 alt 속성 값이 표시됩니다 .

    예시
    <img src="wrongname.gif" alt="Flowers in Chania">

***
### 이미지 크기 - 너비 및 높이
style속성을 사용하여 이미지의 너비와 높이를 지정할 수 있습니다 .

    예시
    <img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">

또는 width및 height속성을 사용할 수 있습니다 .

    예시
    <img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">

width및 height속성은 항상 픽셀 이미지의 폭과 높이를 정의합니다.

참고: 항상 이미지의 너비와 높이를 지정하십시오. 

너비와 높이를 지정하지 않으면 이미지가 로드되는 동안 웹 페이지가 깜박일 수 있습니다.

***
### 너비와 높이, 또는 스타일?
width, height및 style속성은 모든 HTML에서 유효합니다.

그러나 style속성을 사용하는 것이 좋습니다 . 스타일 시트가 이미지 크기를 변경하는 것을 방지합니다.

[예시](./W3_HTML_day11-1-1.html)

***
### 다른 폴더의 이미지
하위 폴더에 이미지가 있는 경우 src속성에 폴더 이름을 포함해야 합니다.

    예시
    <img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

***
### 다른 서버/웹사이트의 이미지
일부 웹 사이트는 다른 서버의 이미지를 가리킵니다.

다른 서버의 이미지를 가리키려면 src속성 에 절대(전체) URL을 지정해야 합니다.

    예시
    <img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">

외부 이미지에 대한 참고 사항: 외부 이미지는 저작권이 있을 수 있습니다. 사용 허가를 받지 않으시면 저작권법에 저촉될 수 있습니다. 또한 외부 이미지를 제어할 수 없습니다. 갑자기 제거되거나 변경될 수 있습니다.

***
### 애니메이션 이미지
HTML은 애니메이션 GIF를 허용합니다.

    예시
    <img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">

***
### 이미지를 링크로
이미지를 링크로 사용하려면 \<a> 태그 안에 \<img> 태그를 넣으세요.

    예시
    <a href="default.asp">
    <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
    </a>

***
### 이미지 플로팅
CSS float속성을 사용하여 이미지가 텍스트의 오른쪽이나 왼쪽으로 떠 있게 하십시오.

    예시
    <p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
    The image will float to the right of the text.</p>

    <p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
    The image will float to the left of the text.</p>