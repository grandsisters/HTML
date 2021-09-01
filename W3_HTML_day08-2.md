## HTML 색상

HTML 색상은 미리 정의된 색상 이름이나 RGB, HEX, HSL, RGBA 또는 HSLA 값으로 지정됩니다.

***
### 색상 이름

HTML에서 색상 이름을 사용하여 색상을 지정할 수 있습니다.

HTML은 140개의 표준 색상 이름을 지원 합니다 .

[HTML에서 사용하는 색상들](https://www.w3schools.com/colors/colors_names.asp)

***
### 배경색

HTML 요소의 배경색을 설정할 수 있습니다.

    예시
    <h1 style="background-color:DodgerBlue;">Hello World</h1>
    <p style="background-color:Tomato;">Lorem ipsum...</p>

<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>

***
### 텍스트 색상

텍스트 색상을 설정할 수 있습니다.

    예시
    <h1 style="color:Tomato;">Hello World</h1>
    <p style="color:DodgerBlue;">Lorem ipsum...</p>
    <p style="color:MediumSeaGreen;">Ut wisi enim...</p>

<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>


***
### 테두리 색상

테두리 색상을 설정할 수 있습니다.

    예시
    <h1 style="border:2px solid Tomato;">Hello World</h1>
    <h1 style="border:2px solid DodgerBlue;">Hello World</h1>
    <h1 style="border:2px solid Violet;">Hello World</h1>


<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>

***
### 색상 값

HTML에서는 RGB 값, HEX 값, HSL 값, RGBA 값 및 HSLA 값을 사용하여 색상을 지정할 수도 있습니다.



    예시
    <h1 style="background-color:rgb(255, 99, 71);">...</h1>
    <h1 style="background-color:#ff6347;">...</h1>
    <h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

    <h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
    <h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>

다음 세 개의 \<div> 요소에는 RGB, HEX 및 HSL 값으로 설정된 배경색이 있습니다.

<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

다음 두 개의 \<div> 요소에는 RGBA 및 HSLA 값으로 설정된 배경색이 있으며, 이는 색상에 알파 채널을 추가합니다(여기서는 50% 투명도를 가짐).

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>