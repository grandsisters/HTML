## HTML Input form* Attributes

이 장에서는 form*HTML \<input>요소 의 다양한 속성에 대해 설명합니다.

***
### 양식 속성
입력 form속성은 \<input>요소가 속한 형식을 지정합니다 .

이 속성의 값은 그것이 속한 \<form> 요소의 id 속성과 같아야 합니다.

예시
HTML 양식 외부에 있는 입력 필드(그러나 여전히 양식의 일부임):

<form action="/action_page.php" id="form1">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <input type="submit" value="Submit">
</form>

<label for="lname">Last name:</label>
<input type="text" id="lname" name="lname" form="form1">

    <form action="/action_page.php" id="form1">
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname"><br><br>
    <input type="submit" value="Submit">
    </form>

    <label for="lname">Last name:</label>
    <input type="text" id="lname" name="lname" form="form1">

***
### formaction 속성
입력 formaction속성은 양식이 제출될 때 입력을 처리할 파일의 URL을 지정합니다.

참고: 이 속성은 \<form> 요소의 작업 속성을 재정의합니다.

formaction 속성은 submit 및 image 입력 유형과 함께 작동합니다.

예시
다른 작업과 함께 두 개의 제출 버튼이 있는 HTML 양식:

<form action="/action_page.php">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="submit" value="Submit">
  <input type="submit" formaction="/action_page2.php" value="Submit as Admin">
</form>

    <form action="/action_page.php">
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label>
    <input type="text" id="lname" name="lname"><br><br>
    <input type="submit" value="Submit">
    <input type="submit" formaction="/action_page2.php" value="Submit as Admin">
    </form>

***
### formenctype 속성
입력 formenctype 속성은 제출할 때 양식 데이터를 인코딩하는 방법을 지정합니다(method="post"가 있는 양식에만 해당).

참고: 이 속성은 \<form>요소의 enctype 속성을 재정의합니다 .

formenctype 속성은 submit 및 image 입력 유형과 함께 작동합니다.

예시
두 개의 제출 버튼이 있는 양식입니다. 첫 번째는 기본 인코딩으로 양식 데이터를 보내고 두 번째는 "multipart/form-data"로 인코딩된 양식 데이터를 보냅니다.

<form action="/action_page_binary.asp" method="post">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <input type="submit" value="Submit">
  <input type="submit" formenctype="multipart/form-data"
  value="Submit as Multipart/form-data">
</form>

    <form action="/action_page_binary.asp" method="post">
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname"><br><br>
    <input type="submit" value="Submit">
    <input type="submit" formenctype="multipart/form-data"
    value="Submit as Multipart/form-data">
    </form>

***
### formmethod 속성
input formmethod 속성은 form-data를 action URL로 보내기 위한 HTTP 메소드를 정의합니다.

참고: 이 속성은 \<form>요소의 메서드 속성을 재정의합니다 .

formmethod속성은 submit 및 image 입력 유형과 함께 작동합니다.

양식 데이터는 URL 변수(method="get") 또는 HTTP 포스트 트랜잭션(method="post")으로 보낼 수 있습니다.

"get" 메서드에 대한 참고 사항:

- 이 method는 이름/값 쌍의 URL에 양식 데이터를 추가합니다.
- 이 method는 사용자가 결과를 책갈피로 지정하려는 양식 제출에 유용합니다.
- URL에 넣을 수 있는 데이터의 양에는 제한이 있으므로(브라우저마다 다름) 모든 양식 데이터가 올바르게 전송되는지 확신할 수 없습니다.
- 민감한 정보를 전달하기 위해 "get" 메소드를 사용하지 마십시오! (비밀번호 또는 기타 민감한 정보는 브라우저의 주소 표시줄에 표시됩니다)


"post" 방법에 대한 참고 사항:

- 이 method는 양식 데이터를 HTTP 포스트 트랜잭션으로 보냅니다.
- "post" 방법을 사용하는 양식 제출은 북마크할 수 없습니다.
- "post" 방법은 "get"보다 더 강력하고 안전하며 "post"에는 크기 제한이 없습니다.


예시
두 개의 제출 버튼이 있는 양식입니다. 첫 번째는 method="get"으로 양식 데이터를 보냅니다. 두 번째는 method="post"로 form-data를 보냅니다.

<form action="/action_page.php" method="get">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="submit" value="Submit using GET">
  <input type="submit" formmethod="post" value="Submit using POST">
</form>

    <form action="/action_page.php" method="get">
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label>
    <input type="text" id="lname" name="lname"><br><br>
    <input type="submit" value="Submit using GET">
    <input type="submit" formmethod="post" value="Submit using POST">
    </form>

***
### formtarget 속성
입력 formtarget속성은 양식을 제출한 후 수신된 응답을 표시할 위치를 나타내는 이름 또는 키워드를 지정합니다.

참고: 이 속성은 \<form>요소의 대상 속성을 재정의합니다 .

formtarget속성은 submit 및 image 입력 유형과 함께 작동합니다.

예시
대상 창이 서로 다른 두 개의 제출 버튼이 있는 양식:

<form action="/action_page.php">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="submit" value="Submit">
  <input type="submit" formtarget="_blank" value="Submit to a new window/tab">
</form>

    <form action="/action_page.php">
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label>
    <input type="text" id="lname" name="lname"><br><br>
    <input type="submit" value="Submit">
    <input type="submit" formtarget="_blank" value="Submit to a new window/tab">
    </form>

***
### formnovavalidate 속성
입력 formnovalidate속성은 제출할 때 \<input> 요소의 유효성을 검사하지 않도록 지정합니다.

참고: 이 속성은 \<form> 요소 의 novalidate 속성을 재정의합니다 .

formnovalidate속성은 submit 입력 유형과 함께 작동합니다.

예시
두 개의 제출 버튼이 있는 양식(검증 포함 및 미포함):

<form action="/action_page.php">
  <label for="email">Enter your email:</label>
  <input type="email" id="email" name="email"><br><br>
  <input type="submit" value="Submit">
  <input type="submit" formnovalidate="formnovalidate"
  value="Submit without validation">
</form>

    <form action="/action_page.php">
    <label for="email">Enter your email:</label>
    <input type="email" id="email" name="email"><br><br>
    <input type="submit" value="Submit">
    <input type="submit" formnovalidate="formnovalidate"
    value="Submit without validation">
    </form>

***
### 무효화 속성
novalidate속성은 \<form>속성입니다 

존재하는 경우 novalidate는 제출 시 모든 양식 데이터의 유효성을 검사하지 않도록 지정합니다.

예시
제출 시 양식 데이터의 유효성을 검사하지 않도록 지정합니다.

<form action="/action_page.php" novalidate>
  <label for="email">Enter your email:</label>
  <input type="email" id="email" name="email"><br><br>
  <input type="submit" value="Submit">
</form>

    <form action="/action_page.php" novalidate>
    <label for="email">Enter your email:</label>
    <input type="email" id="email" name="email"><br><br>
    <input type="submit" value="Submit">
    </form>