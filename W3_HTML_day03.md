## HTML 속성

- 모든 HTML 요소는 속성 을 가질 수 있습니다.
- 속성 은 요소에 대한 추가 정보 를 제공 합니다.
- 속성은 항상 시작 태그에 지정됩니다.
- 속성은 일반적으로 name="value" 와 같은 이름/값 쌍으로 제공됩니다.

***
### href 속성
<br>

\<a>태그는 하이퍼 링크를 정의합니다. href속성은 링크로 이동 페이지의 URL을 지정합니다

    예시
    <a href="https://www.w3schools.com">Visit W3Schools</a>

***
### src 속성

<br>

\<img>태그는 HTML 페이지에 포함 된 이미지에 사용됩니다. src화상의 경로를 표시하는 속성 지정

    \<img src="img.jpg">

src 속성에 URL을 지정하는 방법에는 두 가지가 있습니다 .

1. 절대 URL - 다른 웹사이트에서 호스팅되는 외부 이미지에 대한 링크입니다. 
    예: src="https://www.w3schools.com/images/img_girl.jpg".

    참고: 외부 이미지는 저작권이 있을 수 있습니다. 사용 허가를 받지 않으시면 저작권법에 저촉될 수 있습니다. 
    또한 외부 이미지를 제어할 수 없습니다. 
    갑자기 제거되거나 변경될 수 있습니다.

2. 상대 URL - 웹사이트 내에서 호스팅되는 이미지에 대한 링크입니다. 
    여기서 URL은 도메인 이름을 포함하지 않습니다. 
    URL이 슬래시 없이 시작되면 현재 페이지를 기준으로 합니다. 
    예: src="img.jpg" 
    URL이 슬래시로 시작하면 도메인을 기준으로 합니다. 
    예: src="/images/img_girl.jpg".

팁: 거의 항상 상대 URL을 사용하는 것이 가장 좋습니다. 
도메인을 변경해도 깨지지 않습니다.

***
### 너비 및 높이 속성

<br>

\<img>태그도 포함되어야 width하고 height(픽셀) 이미지의 폭 및 높이를 지정 특성 :

    <img src="img.jpg" width="500" height="600">


***
### 대체 속성

<br>

태그 의 필수 alt속성은 \<img>어떤 이유로 이미지를 표시할 수 없는 경우 이미지에 대한 대체 텍스트를 지정합니다. 연결 속도가 느리거나 src속성 오류가 있거나 사용자가 스크린 리더를 사용하기 때문일 수 있습니다 .

    <img src="img_girl.jpg" alt="Girl with a jacket">

***
### 스타일 속성

<br>

style속성은 예컨대 색상, 폰트, 크기, 등 같은 요소에 스타일을 추가하는 데 사용된다.

    <p style="color:red;">This is a red paragraph.</p>

***
### 언어 속성

<br>

웹 페이지의 언어를 선언하려면 항상 태그 lang내부 에 속성을 포함해야 \<html>합니다. 이것은 검색 엔진과 브라우저를 지원하기 위한 것입니다.

다음 예에서는 영어를 언어로 지정합니다.

    <!DOCTYPE html>
    <html lang="en">
    <body>
    ...
    </body>
    </html>

국가 코드는 lang 속성 의 언어 코드에 추가할 수도 있습니다 . 따라서 처음 두 문자는 HTML 페이지의 언어를 정의하고 마지막 두 문자는 국가를 정의합니다.

다음 예에서는 영어를 언어로 지정하고 미국을 국가로 지정합니다.

    <!DOCTYPE html>
    <html lang="en-US">
    <body>
    ...
    </body>
    </html>

***
### 제목 속성

<br>

title속성은 요소에 대한 몇 가지 추가 정보를 정의합니다.

제목 속성 값은 요소 위로 마우스를 가져가면 툴팁으로 표시됩니다.

    <p title="I'm a tooltip">This is a paragraph.</p>

***
### 항상 소문자 속성 사용

<br>

HTML 표준에는 소문자 속성 이름이 필요하지 않습니다.

title 속성(및 기타 모든 속성)은 title 또는 TITLE 와 같이 대문자 또는 소문자로 작성할 수 있습니다 .

그러나 W3C 는 HTML에서 소문자 속성을 권장 하고 XHTML과 같은 더 엄격한 문서 유형에 대해 소문자 속성을 요구 합니다.

***
### 항상 속성 값을 인용하십시오

<br>

HTML 표준은 속성 값 주위에 따옴표를 요구하지 않습니다.

그러나 W3C 는 HTML의 따옴표를 권장 하고 XHTML과 같은 더 엄격한 문서 유형에 대한 따옴표를 요구 합니다.

    좋은 예:
    <a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>

    나쁜 예:
    <a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>

따옴표를 사용해야 하는 경우가 있습니다. 이 예는 공백을 포함하기 때문에 제목 속성을 올바르게 표시하지 않습니다.

    예시
    <p title=About W3Schools>

### 작은따옴표 또는 큰따옴표?
속성 값을 묶는 큰 따옴표는 HTML에서 가장 일반적이지만 작은 따옴표도 사용할 수 있습니다.

속성 값 자체에 큰따옴표가 포함된 경우 작은따옴표를 사용해야 하는 경우가 있습니다.

    <p title='John "ShotGun" Nelson'>

혹은 그 반대로도:

    <p title="John 'ShotGun' Nelson">

***
### 단원 요약

<br>

- 모든 HTML 요소는 속성 을 가질 수 있습니다.
- href속성은 \<a>링크가 이동하는 페이지의 URL 을 지정합니다.
- src속성은 \<img>표시할 이미지의 경로를 지정합니다.
- width및 height속성은 \<img>이미지 에 대한 크기 정보를 제공합니다.
- alt속성은 \<img>이미지에 대한 대체 텍스트를 제공합니다.
- style속성은 예컨대 색상, 폰트, 크기, 등 같은 요소에 스타일을 추가하는 데 사용
- 태그 의 lang속성은 \<html>웹 페이지의 언어를 선언합니다.
- title속성은 요소에 대한 몇 가지 추가 정보를 정의합니다