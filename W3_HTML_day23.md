## HTML 반응형 웹 디자인
반응형 웹 디자인은 모든 장치에서 보기 좋은 웹 페이지를 만드는 것입니다.

반응형 웹 디자인은 다양한 화면 크기와 뷰포트에 맞게 자동으로 조정됩니다.

반응형 웹 디자인은 HTML 및 CSS를 사용하여 웹 사이트의 크기를 자동으로 조정, 숨기기, 축소 또는 확대하여 모든 장치(데스크톱, 태블릿 및 휴대폰)에서 보기 좋게 만드는 것입니다.

<img src='./img/Responsive Web Design.jpg'>

***
### 뷰포트 설정
반응형 웹사이트를 만들려면 \<meta> 모든 웹페이지에 다음 태그를 추가 하세요.

    예시
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

***
### 반응형 이미지
반응형 이미지는 모든 브라우저 크기에 맞게 잘 확장되는 이미지입니다.

- 너비 속성 사용

    CSS width속성이 100%로 설정되면 이미지가 반응하고 확장 및 축소됩니다.

        예시
        <img src="img_girl.jpg" style="width:100%;">

위의 예에서 이미지는 원래 크기보다 크게 확대될 수 있습니다.

많은 경우에 더 나은 솔루션은 max-width속성을 대신 사용하는 것입니다.

<br>

- 최대 너비 속성 사용

    max-width속성이 100%로 설정된 경우 이미지는 필요한 경우 축소되지만 원래 크기보다 크게 확대되지는 않습니다.

        예시
        <img src="img_girl.jpg" style="max-width:100%;height:auto;">

- 브라우저 너비에 따라 다른 이미지 표시

    HTML \<picture>요소를 사용하면 브라우저 창 크기에 따라 다른 이미지를 정의할 수 있습니다.

    브라우저 창의 크기를 조정하여 너비에 따라 아래 이미지가 어떻게 변경되는지 확인합니다.

        예시
        <picture>
            <source srcset="img_smallflower.jpg" media="(max-width: 600px)">
            <source srcset="img_flowers.jpg" media="(max-width: 1500px)">
            <source srcset="flowers.jpg">
            <img src="img_smallflower.jpg" alt="Flowers">
        </picture>

### 반응형 텍스트 크기
텍스트 크기는 "뷰포트 너비"를 의미하는 "vw" 단위로 설정할 수 있습니다.

그렇게 하면 텍스트 크기가 브라우저 창의 크기를 따릅니다.

뷰포트는 브라우저 창 크기입니다. 

1vw = 뷰포트 너비의 1%. 뷰포트의 너비가 50cm인 경우 1vw는 0.5cm입니다.

    예시
    <h1 style="font-size:10vw">Hello World</h1>

<h1 style="font-size:10vw">Hello World</h1>

***
### 미디어 쿼리
텍스트와 이미지의 크기를 조정하는 것 외에도 반응형 웹 페이지에서 미디어 쿼리를 사용하는 것도 일반적입니다.

미디어 쿼리를 사용하면 다양한 브라우저 크기에 대해 완전히 다른 스타일을 정의할 수 있습니다.

예: 브라우저 창의 크기를 조정하여 아래의 세 div 요소가 큰 화면에서는 가로로 표시되고 작은 화면에서는 세로로 쌓이도록 합니다.

[예시](./W3_HTML_day23-1.html)

***
### 반응형 웹 페이지 - 전체 예시
반응형 웹 페이지는 큰 데스크톱 화면과 작은 휴대전화에서 보기 좋게 표시되어야 합니다.

[예시](./W3_HTML_day23-2.html)

***
### 반응형 웹 디자인 - 프레임워크
모든 인기 있는 CSS 프레임워크는 반응형 디자인을 제공합니다.

그들은 무료이며 사용하기 쉽습니다.

### W3.CSS
W3.CSS는 기본적으로 데스크탑, 태블릿 및 모바일 디자인을 지원하는 최신 CSS 프레임워크입니다.

W3.CSS는 유사한 CSS 프레임워크보다 작고 빠릅니다.

W3.CSS는 Bootstrap의 고품질 대안으로 설계되었습니다.

W3.CSS는 jQuery 또는 기타 JavaScript 라이브러리와 독립적으로 설계되었습니다.

[W3.CSS 데모](./W3_HTML_day23-3.html)

***
### 부트스트랩
또 다른 인기 있는 CSS 프레임워크는 Bootstrap입니다. 

Bootstrap은 HTML, CSS 및 jQuery를 사용하여 반응형 웹 페이지를 만듭니다.

[부트스트랩](./W3_HTML_day23-4.html)