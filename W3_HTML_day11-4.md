## HTML \<picture> 요소
HTML \<picture>요소를 사용하면 다양한 장치 또는 화면 크기에 대해 다른 그림을 표시할 수 있습니다. 또한 웹 개발자가 이미지 리소스를 보다 유연하게 지정할 수 있습니다.

\<picture>소자를 포함하는 하나 이상의 \<source>요소를 관통 다른 이미지를 참조하여 각각의 srcset 속성. 

이런 식으로 브라우저는 현재 보기 및/또는 장치에 가장 잘 맞는 이미지를 선택할 수 있습니다.

각 \<source>요소에는 media이미지가 가장 적합한 시기를 정의 하는 속성이 있습니다.


다양한 화면 크기에 대해 다른 이미지 표시:

    예시
    <picture>
    <source media="(min-width: 650px)" srcset="img_food.jpg">
    <source media="(min-width: 465px)" srcset="img_car.jpg">
    <img src="img_girl.jpg">
    </picture>

참고: 항상 \<img>요소를 요소의 마지막 자식 요소로 지정 하십시오 \<picture>. 

\<img>요소는 지원하지 않는 브라우저에서 사용되는 \<picture>요소를, 

또는 전혀 경우 \<source>태그가 일치하지 않습니다.

***
### 그림 요소를 사용하는 경우
\<picture>요소 에는 두 가지 주요 목적이 있습니다 .

1. 대역폭
화면이 작거나 기기가 작은 경우 큰 이미지 파일을 로드할 필요가 없습니다. 

브라우저는 \<source> 속성 값이 일치하는 첫 번째 요소를 사용 하고 다음 요소를 무시합니다.

2. 포맷 지원
일부 브라우저 또는 장치는 모든 이미지 형식을 지원하지 않을 수 있습니다. 

\<picture>요소 를 사용하여 모든 형식의 이미지를 추가할 수 있으며 브라우저는 인식하는 첫 번째 형식을 사용하고 다음 요소를 무시합니다.


브라우저는 인식하는 첫 번째 이미지 형식을 사용합니다.

    예시
    <picture>
    <source srcset="img_avatar.png">
    <source srcset="img_girl.jpg">
    <img src="img_beatles.gif" alt="Beatles" style="width:auto;">
    </picture>

참고: 브라우저는 \<source>속성 값이 일치하는 첫 번째 요소를 사용하고 다음 \<source>요소를 무시합니다 .