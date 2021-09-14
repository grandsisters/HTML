## HTML Form

HTML Form은 사용자 입력을 수집하는 데 사용됩니다. 사용자 입력은 처리를 위해 가장 자주 서버로 전송됩니다.

***
### \<form> 요소
HTML \<form>요소는 사용자 입력을 위한 HTML 양식을 만드는 데 사용됩니다.

    <form>
    .
    form elements
    .
    </form>


\<form>요소는 텍스트 필드, 체크 박스, 라디오 버튼, 제출 버튼과 같은 서로 다른 입력 요소 유형에 대한 컨테이너이다.

[HTML 양식 요소](https://www.w3schools.com/html/html_form_elements.asp)

***
### \<input> 요소
HTML \<input>요소는 가장 많이 사용되는 양식 요소입니다.

\<input>요소는에 type 속성 따라 여러 가지 방법으로 표시 할 수 있습니다 .

<img src='./img/form.png'>

[form 입력 유형](https://www.w3schools.com/html/html_form_input_types.asp)

***
### 텍스트 필드
는 \<input type="text">텍스트 입력을위한 한 줄의 입력 필드를 정의합니다.

예시
텍스트 입력 필드가 있는 양식:

예시

<form>
<label for="fname">First name:</label><br>
<input type="text" id="fname" name="fname"><br>
<label for="lname">Last name:</label><br>
<input type="text" id="lname" name="lname">
</form>


    <form>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname">
    </form>

참고: 양식 자체는 표시되지 않습니다. 또한 입력 필드의 기본 너비는 20자입니다.

***
### \<label> 요소
위의 예에서 \<label>요소의 사용에 주목하십시오 .

\<label>태그는 많은 폼 요소에 대한 레이블을 정의합니다.

이 \<label>요소는 스크린 리더 사용자에게 유용합니다. 

사용자가 입력 요소에 초점을 맞추면 스크린 리더가 레이블을 소리내어 읽어주기 때문입니다.

또한 이 \<label>요소는 매우 작은 영역(예: 라디오 버튼 또는 체크박스)을 클릭하는 데 어려움을 겪는 사용자에게 도움이 됩니다. 사용자가 \<label>요소 내의 텍스트를 클릭 하면 라디오 버튼/체크박스가 토글 되기 때문 입니다.

태그의 for속성은 \<label>태그를 함께 묶는 요소 의 id속성 과 같아야 \<input>합니다.

***
### 라디오 버튼
\<input type="radio">는 라디오 버튼을 정의합니다.

라디오 버튼을 사용하면 제한된 수의 선택 항목 중 하나를 선택할 수 있습니다.

예시
라디오 버튼이 있는 양식:

<p>Choose your favorite Web language:</p>

<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>


    <p>Choose your favorite Web language:</p>

    <form>
    <input type="radio" id="html" name="fav_language" value="HTML">
    <label for="html">HTML</label><br>
    <input type="radio" id="css" name="fav_language" value="CSS">
    <label for="css">CSS</label><br>
    <input type="radio" id="javascript" name="fav_language" value="JavaScript">
    <label for="javascript">JavaScript</label>
    </form>

***
### 체크박스
<input type="checkbox">는 체크박스를 정의합니다.

체크박스를 통해 사용자는 제한된 수의 선택 중에서 ZERO 또는 MORE 옵션을 선택할 수 있습니다.

예시
체크박스가 있는 양식:

<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>

    <form>
    <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
    <label for="vehicle1"> I have a bike</label><br>
    <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
    <label for="vehicle2"> I have a car</label><br>
    <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
    <label for="vehicle3"> I have a boat</label>
    </form>

***
### 제출 버튼
\<input type="submit">는 폼 - 처리기 폼 데이터의 송신 버튼을 정의한다.

양식 처리기는 일반적으로 입력 데이터를 처리하기 위한 스크립트가 있는 서버의 파일입니다.

양식 처리기는 양식의 action 속성에 지정됩니다 .

예시
제출 버튼이 있는 양식:

<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>

    <form action="/action_page.php">
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe"><br><br>
    <input type="submit" value="Submit">
    </form>

***
### \<input>의 이름 속성
각 입력 필드에는 name제출할 속성이 있어야 합니다 .

경우] name속성이 생략되어, 입력 필드의 값이 모두 전송 될 수 없습니다.

예시
이 예에서는 "이름" 입력 필드의 값을 제출하지 않습니다. 

<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" value="John"><br><br>
  <input type="submit" value="Submit">
</form>

    <form action="/action_page.php">
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" value="John"><br><br>
    <input type="submit" value="Submit">
    </form>