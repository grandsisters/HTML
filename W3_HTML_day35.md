## HTML form 요소
이 장에서는 다양한 HTML 양식 요소를 모두 설명합니다.

***
### HTML \<form> 요소
HTML \<form>요소는 다음 양식 요소 중 하나 이상을 포함할 수 있습니다.

    <input>
    <label>
    <select>
    <textarea>
    <button>
    <fieldset>
    <legend>
    <datalist>
    <output>
    <option>
    <optgroup>

***
### \<input> 요소
가장 많이 사용되는 양식 요소 중 하나는 \<input>요소입니다.

\<input>요소는 type 속성에 따라 여러 가지 방법으로 표시 할 수 있습니다 .

예시

<label for="fname">First name:</label>
<input type="text" id="fname" name="fname">

    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname">

type 속성 의 다른 모든 값은 다음 장인 [HTML 입력 유형](https://www.w3schools.com/html/html_form_input_types.asp) 에서 다룹니다 .

***
### \<label> 요소
\<label>요소는 여러 가지 형태의 요소에 대한 레이블을 정의합니다.

이 \<label>요소는 스크린 리더 사용자에게 유용합니다. 사용자가 입력 요소에 초점을 맞추면 스크린 리더가 레이블을 소리내어 읽어주기 때문입니다.

또한 이 \<label>요소는 매우 작은 영역(예: 라디오 버튼 또는 체크박스)을 클릭하는 데 어려움을 겪는 사용자에게 도움이 됩니다. 사용자가 \<label>요소 내의 텍스트를 클릭 하면 라디오 버튼/체크박스가 토글 되기 때문 입니다.

태그 의 for속성은 \<label>태그를 함께 묶는 요소 의 id속성 과 같아야 \<input>합니다.

***
### \<select> 요소
\<select>요소는 드롭 다운 목록을 정의합니다 :

예시
<label for="cars">Choose a car:</label>
<select id="cars" name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>

    <label for="cars">Choose a car:</label>
    <select id="cars" name="cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="fiat">Fiat</option>
    <option value="audi">Audi</option>
    </select>


\<option>요소는 선택할 수있는 옵션을 정의합니다.

기본적으로 드롭다운 목록의 첫 번째 항목이 선택됩니다.

미리 선택된 옵션을 정의하려면 옵션에 selected속성을 추가하십시오 .

    예시
    <option value="fiat" selected>Fiat</option>

### Visible Values:
size 속성을 사용해 Visible Values 값의 수를 지정한다 :

예시
<label for="cars">Choose a car:</label>
<select id="cars" name="cars" size="3">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>

    <label for="cars">Choose a car:</label>
    <select id="cars" name="cars" size="3">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="fiat">Fiat</option>
    <option value="audi">Audi</option>
    </select>

### 다중 선택 허용:
multiple속성을 사용하여 사용자가 하나 이상의 값을 선택할 수 있도록 한다 :

예시
<label for="cars">Choose a car:</label>
<select id="cars" name="cars" size="4" multiple>
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>

    <label for="cars">Choose a car:</label>
    <select id="cars" name="cars" size="4" multiple>
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="fiat">Fiat</option>
    <option value="audi">Audi</option>
    </select>

***
### \<textarea> 요소
\<textarea>소자는 여러 줄의 입력 필드 (텍스트 영역)을 정의한다 :

예시

<textarea name="message" rows="10" cols="30">
The cat was playing in the garden.
</textarea>

    <textarea name="message" rows="10" cols="30">
    The cat was playing in the garden.
    </textarea>


rows속성은 텍스트 영역에서 라인의 보이는 수를 지정합니다.

cols속성은 텍스트 영역의 가시 폭을 지정한다.

위의 HTML 코드가 브라우저에 표시되는 방식은 다음과 같습니다.

CSS를 사용하여 텍스트 영역의 크기를 정의할 수도 있습니다.

예시

<textarea name="message" style="width:200px; height:600px;">
The cat was playing in the garden.
</textarea>

    <textarea name="message" style="width:200px; height:600px;">
    The cat was playing in the garden.
    </textarea>

***
### \<button> 요소
\<button>요소는 클릭 버튼을 정의한다 :

예시
<button type="button" onclick="alert('Hello World!')">Click Me!</button>

    <button type="button" onclick="alert('Hello World!')">Click Me!</button>

참고: 항상 type버튼 요소의 속성을 지정하십시오. 브라우저마다 버튼 요소에 대해 다른 기본 유형을 사용할 수 있습니다.

***
### \<fieldset> 및 \<legend> 요소
\<fieldset>소자 형태로 그룹과 관련된 데이터를 저장하는 데 사용된다.

\<legend>요소는 \<fieldset>요소에 캡션(설명)을 정의한다 .

예시
<form action="/action_page.php">
  <fieldset>
    <legend>Personalia:</legend>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe"><br><br>
    <input type="submit" value="Submit">
  </fieldset>
</form>


    <form action="/action_page.php">
    <fieldset>
        <legend>Personalia:</legend>
        <label for="fname">First name:</label><br>
        <input type="text" id="fname" name="fname" value="John"><br>
        <label for="lname">Last name:</label><br>
        <input type="text" id="lname" name="lname" value="Doe"><br><br>
        <input type="submit" value="Submit">
    </fieldset>
    </form>

***
### \<datalist> 요소
\<datalist>요소는에서 미리 정의 된 옵션의리스트를 \<input>요소에 지정.

사용자는 데이터를 입력할 때 미리 정의된 옵션의 드롭다운 목록을 볼 수 있습니다.

\<input>요소의 list의 속성은 \<datalist>요소의 id 속성으로 반드시 참조해야 합니다.

예시
<form action="/action_page.php">
  <input list="browsers">
  <datalist id="browsers">
    <option value="Internet Explorer">
    <option value="Firefox">
    <option value="Chrome">
    <option value="Opera">
    <option value="Safari">
  </datalist>
</form>

    <form action="/action_page.php">
    <input list="browsers">
    <datalist id="browsers">
        <option value="Internet Explorer">
        <option value="Firefox">
        <option value="Chrome">
        <option value="Opera">
        <option value="Safari">
    </datalist>
    </form>

***
### \<output> 요소
\<output>(하나의 스크립트에 의해 수행 같은) 요소는 계산 결과를 나타낸다.

예시
계산을 수행하고 결과를 \<output>요소 에 표시합니다 .

<form action="/action_page.php"
  oninput="x.value=parseInt(a.value)+parseInt(b.value)">
  0
  <input type="range"  id="a" name="a" value="50">
  100 +
  <input type="number" id="b" name="b" value="50">
  =
  <output name="x" for="a b"></output>
  <input type="submit">
</form>

    <form action="/action_page.php"
    oninput="x.value=parseInt(a.value)+parseInt(b.value)">
    0
    <input type="range"  id="a" name="a" value="50">
    100 +
    <input type="number" id="b" name="b" value="50">
    =
    <output name="x" for="a b"></output>
    <input type="submit">
    </form>