***
## 목록 만들기
***
***
## 순서있는 목록 만들기

- 순서 있는 목록을 만드는 ol, li태그
<br>
순서 있는 목록 ordered list의 줄임말 ol
<br>
li는 list의 줄임말
<br>

각 항목을 순서대로 나열한 것이다
***
### ol태그의 속성
***

ol태그에는 type속성과 start속성이 있다

<br>
<br>
- type속성

순서있는 목록은 숫자 1,2,3,...으로 앞에 번호를 매기는데

type속성은 이 번호를 영문자나 로마 숫자 등으로 바꿀수 있다

<br>
<br>
- start속성

순서목록은 기본적으로 1부터 시작하지만 start속성을 사용해서 시작 번호를 바꿀 수도 있다

목록이 중간에 끊어졌다가 다시 이어지는 경우 번호도 이어져야 하는데 이때 이어지는 부분의 시작 번호를 start속성으로 알맞게 바꿔주면 된다

|종류|설명|
|------|------|
|type = "1"|숫자(기본값)|
|type = "a"|영문 소문자|
|type = "A"|영문 대문자|
|type = "i"|로마 숫자 소문자|
|type = "I"|로마 숫자 대문자|

***
## 순서없는 목록 만들기

- 순서 없는 목록을 만드는 ul, li 태그
<br>
unordered list의 줄임말인 ul
<br>
li 태그도 같이 쓰인다


항목의 순서가 중요하지 않을 때 사용한다

항목 앞에 작은 원이나 사각형을 붙여서 구분하는데 이런 작은 그림을 불릿(bullet)이라고 한다

ol태그로 만든 순서있는 목록에서 li태그는 그대로 두고 ol태그만 ul태그로 수정하면 순서 없는 목록을 만들 수 있다 
***
## 설명 목록을 만드는 dl, dt, dd태그

- 이름 부분을 지정하는 dt태그와 값(설명) 부분을 지정하는 dd태그로 구성된다
<br>
dl태그 사이에 한쌍의 dt, dd태그를 넣는다
<br>
dt태그 하나에 여러 개의 dd태그를 사용할 수도 있다 

설명 목록이란(description list)란 이름(name)과 값(value)형태로 된 목록을 말한다
***

~87p