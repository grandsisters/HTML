## HTML 배경 이미지
거의 모든 HTML 요소에 대해 배경 이미지를 지정할 수 있습니다.

***
### HTML 요소의 배경 이미지
HTML 요소에 배경 이미지를 추가하려면 HTML style속성과 CSS background-image속성을 사용하세요.


HTML 요소에 배경 이미지 추가

    예시
    <div style="background-image: url('img_girl.jpg');">


<head>의 섹션 \<style> 에서 요소 의 배경 이미지를 지정할 수도 있습니다.

\<style> 요소 의 배경 이미지를 지정합니다 .

    예시
    <style>
    div {
    background-image: url('img_girl.jpg');
    }
    </style>

***
### 페이지의 배경 이미지
전체 페이지에 배경 이미지가 포함되도록 하려면 \<body>요소 에 배경 이미지를 지정해야 합니다 .


전체 페이지의 배경 이미지 추가:

    예시
    <style>
    body {
    background-image: url('img_girl.jpg');
    }
    </style>

***
### 배경 반복
배경 이미지가 요소보다 작은 경우 이미지는 요소의 끝에 도달할 때까지 가로 및 세로로 반복됩니다.


    예시
    <style>
    body {
    background-image: url('example_img_girl.jpg');
    }
    </style>

배경 이미지가 반복되는 것을 방지하려면 background-repeat속성을 로 설정하십시오 no-repeat.

    예시
    <style>
    body {
    background-image: url('example_img_girl.jpg');
    background-repeat: no-repeat;
    }
    </style>

***
### 배경 표지
배경 이미지가 전체 요소를 덮도록 하려면 background-size속성을 cover로 설정할 수 있습니다.

또한 전체 요소가 항상 포함 background-attachment되도록 하려면 속성을 fixed로 설정하십시오. 

이렇게 하면 배경 이미지가 늘어나지 않고 전체 요소를 덮을 것입니다(이미지는 원래 비율을 유지함).

    예시
    <style>
    body {
    background-image: url('img_girl.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
    }
    </style>

***
### 배경 스트레치
전체 요소에 맞게 배경 이미지를 늘리려면 background-size속성을 100% 100%다음과 같이 설정할 수 있습니다 .

브라우저 창의 크기를 조정하면 이미지가 늘어나지만 항상 전체 요소를 덮는 것을 볼 수 있습니다.

    예시
    <style>
    body {
    background-image: url('img_girl.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
    }
    </style>