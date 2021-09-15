## HTML Input Attributes

이 장에서는 HTML \<input>요소 의 다양한 속성에 대해 설명합니다 .

***
### 값 속성
입력 value속성은 입력 필드의 초기 값을 지정합니다.

예시
초기(기본값) 값이 있는 입력 필드:

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe">
</form>

    <form>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe">
    </form>

***
### 읽기 전용 속성
입력 readonly속성은 입력 필드가 읽기 전용임을 지정합니다.

읽기 전용 입력 필드는 수정할 수 없습니다(그러나 사용자가 탭하여 강조 표시하고 텍스트를 복사할 수 있음).

양식을 제출할 때 읽기 전용 입력 필드의 값이 전송됩니다!

예시
읽기 전용 입력 필드:

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John" readonly><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe">
</form>

    <form>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John" readonly><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe">
    </form>


***
### 비활성화된 속성
입력 disabled속성은 입력 필드가 비활성화되어야 함을 지정합니다.

비활성화된 입력 필드는 사용할 수 없고 클릭할 수 없습니다.

비활성화된 입력 필드의 값은 양식을 제출할 때 전송되지 않습니다!

예시
비활성화된 입력 필드:

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John" disabled><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe">
</form>

    <form>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John" disabled><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe">
    </form>


***
### 크기 속성
입력 size속성은 입력 필드의 보이는 너비를 문자로 지정합니다.

size의 기본값은 20입니다.

참고 :size 다음과 같은 입력 유형과 속성 작품 : 텍스트, 검색, 전화, URL, 이메일과 암호를 입력합니다.

예시
입력 필드의 너비를 설정합니다.

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" size="50"><br>
  <label for="pin">PIN:</label><br>
  <input type="text" id="pin" name="pin" size="4">
</form>

    <form>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" size="50"><br>
    <label for="pin">PIN:</label><br>
    <input type="text" id="pin" name="pin" size="4">
    </form>

***
### 최대 길이 속성
입력 maxlength속성은 입력 필드에 허용되는 최대 문자 수를 지정합니다.

참고: 최대 길이가 설정되면 입력 필드에 지정된 문자 수 이상을 사용할 수 없습니다. 그러나 이 속성은 피드백을 제공하지 않습니다. 따라서 사용자에게 경고를 하려면 자바스크립트 코드를 작성해야 합니다.

예시
입력 필드의 최대 길이를 설정합니다.

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" size="50"><br>
  <label for="pin">PIN:</label><br>
  <input type="text" id="pin" name="pin" maxlength="4" size="4">
</form>

    <form>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" size="50"><br>
    <label for="pin">PIN:</label><br>
    <input type="text" id="pin" name="pin" maxlength="4" size="4">
    </form>

***
### 최소 및 최대 속성
입력 min및 max속성은 입력 필드의 최소값과 최대값을 지정합니다.

min 및 max 속성은 숫자, 범위, 날짜, 날짜-시간-로컬, 월, 시간 및 주 등의 입력 유형에서 작동합니다.

팁: 최대 및 최소 속성을 함께 사용하여 적절한 값 범위를 만드십시오.

예시
최대 날짜, 최소 날짜 및 유효한 값 범위를 설정합니다.

<form>
  <label for="datemax">Enter a date before 1980-01-01:</label>
  <input type="date" id="datemax" name="datemax" max="1979-12-31"><br><br>

  <label for="datemin">Enter a date after 2000-01-01:</label>
  <input type="date" id="datemin" name="datemin" min="2000-01-02"><br><br>

  <label for="quantity">Quantity (between 1 and 5):</label>
  <input type="number" id="quantity" name="quantity" min="1" max="5">
</form>


    <form>
    <label for="datemax">Enter a date before 1980-01-01:</label>
    <input type="date" id="datemax" name="datemax" max="1979-12-31"><br><br>

    <label for="datemin">Enter a date after 2000-01-01:</label>
    <input type="date" id="datemin" name="datemin" min="2000-01-02"><br><br>

    <label for="quantity">Quantity (between 1 and 5):</label>
    <input type="number" id="quantity" name="quantity" min="1" max="5">
    </form>

***
### 다중 속성
입력 multiple속성은 사용자가 입력 필드에 둘 이상의 값을 입력할 수 있도록 지정합니다.

이 multiple속성은 이메일 및 파일 입력 유형에서 작동합니다.

예시
여러 값을 허용하는 파일 업로드 필드:

<form>
  <label for="files">Select files:</label>
  <input type="file" id="files" name="files" multiple>
</form>

    <form>
    <label for="files">Select files:</label>
    <input type="file" id="files" name="files" multiple>
    </form>

***
### 패턴 속성
입력 pattern속성은 양식이 제출될 때 입력 필드의 값이 검사되는 정규식을 지정합니다.

이 pattern속성은 텍스트, 날짜, 검색, URL, 전화, 이메일 및 비밀번호 입력 유형과 함께 작동합니다.

팁: 전역 제목 속성을 사용 하여 사용자에게 도움이 되는 패턴을 설명합니다.

팁: JavaScript 자습서에서 정규식 에 대해 자세히 알아보세요 .

예시
세 글자만 포함할 수 있는 입력 필드(숫자 또는 특수 문자 없음):

<form>
  <label for="country_code">Country code:</label>
  <input type="text" id="country_code" name="country_code"
  pattern="[A-Za-z]{3}" title="Three letter country code">
</form>

    <form>
    <label for="country_code">Country code:</label>
    <input type="text" id="country_code" name="country_code"
    pattern="[A-Za-z]{3}" title="Three letter country code">
    </form>

***
### 자리 표시자 속성
입력 placeholder속성은 입력 필드의 예상 값(예상 값 또는 예상 형식에 대한 간단한 설명)을 설명하는 짧은 힌트를 지정합니다.

사용자가 값을 입력하기 전에 짧은 힌트가 입력 필드에 표시됩니다.

placeholder텍스트, 검색, URL, 전화, 이메일, 비밀번호 : 속성은 다음과 같은 입력 유형과 작동합니다.

예시
자리 표시자 텍스트가 있는 입력 필드:

<form>
  <label for="phone">Enter a phone number:</label>
  <input type="tel" id="phone" name="phone"
  placeholder="123-45-678"
  pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}">
</form>

    <form>
    <label for="phone">Enter a phone number:</label>
    <input type="tel" id="phone" name="phone"
    placeholder="123-45-678"
    pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}">
    </form>

***
### 필수 속성
입력 required속성은 양식을 제출하기 전에 입력 필드를 채워야 함을 지정합니다.

required텍스트, 검색, URL, 전화, 이메일, 비밀번호, 날짜 선택기, 숫자, 체크 박스, 라디오, 파일 : 속성은 다음과 같은 입력 유형과 작동합니다.

예시
필수 입력 필드:

<form>
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required>
</form>

    <form>
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" required>
    </form>

***
### 단계 속성
입력 step속성은 입력 필드의 법적 숫자 간격을 지정합니다.

예: step="3"인 경우 법적 번호는 -3, 0, 3, 6 등이 될 수 있습니다.

팁: 이 속성은 최대 및 최소 속성과 함께 사용하여 유효한 값 범위를 생성할 수 있습니다.

step다음과 같은 입력 유형과 속성 작품 : 수, 범위, 날짜, 날짜 로컬, 월, 시간, 주.

예시
지정된 법적 번호 간격이 있는 입력 필드:

<form>
  <label for="points">Points:</label>
  <input type="number" id="points" name="points" step="3">
</form>

    <form>
    <label for="points">Points:</label>
    <input type="number" id="points" name="points" step="3">
    </form>

참고: 입력 제한은 완전하지 않으며 JavaScript는 잘못된 입력을 추가할 수 있는 다양한 방법을 제공합니다. 안전하게 입력을 제한하려면 수신자(서버)도 확인해야 합니다!


***
### 자동 초점 속성
입력 autofocus속성은 페이지가 로드될 때 입력 필드가 자동으로 포커스를 받아야 함을 지정합니다.

예시
페이지가 로드될 때 "이름" 입력 필드가 자동으로 포커스를 받도록 합니다.

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" autofocus><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>

    <form>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" autofocus><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname">
    </form>

***
### 높이 및 너비 속성
입력 height및 width속성은 \<input type="image">요소 의 높이와 너비를 지정합니다 .

팁: 항상 이미지의 높이 및 너비 속성을 모두 지정하십시오. 높이와 너비가 설정되어 있으면 페이지가 로드될 때 이미지에 필요한 공간이 예약됩니다. 이러한 속성이 없으면 브라우저는 이미지의 크기를 알지 못하며 적절한 공간을 확보할 수 없습니다. 그 결과 로드하는 동안(이미지가 로드되는 동안) 페이지 레이아웃이 변경될 수 있습니다.

예시
높이 및 너비 속성을 사용하여 이미지를 제출 버튼으로 정의합니다.

<form>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="image" src="img_submit.gif" alt="Submit" width="48" height="48">
</form>

    <form>
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label>
    <input type="text" id="lname" name="lname"><br><br>
    <input type="image" src="img_submit.gif" alt="Submit" width="48" height="48">
    </form>

***
### 목록 속성
input list속성은 \<datalist>\<input> 요소에 대해 미리 정의된 옵션을 포함 하는 요소를 참조합니다 .

예시
\<datalist>에 사전 정의된 값이 있는 \<input> 요소:

<form>
  <input list="browsers">
  <datalist id="browsers">
    <option value="Internet Explorer">
    <option value="Firefox">
    <option value="Chrome">
    <option value="Opera">
    <option value="Safari">
  </datalist>
</form>

    <form>
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
### 자동 완성 속성
입력 autocomplete속성은 양식 또는 입력 필드가 자동 완성 기능을 켜야 하는지 여부를 지정합니다.

자동 완성을 사용하면 브라우저에서 값을 예측할 수 있습니다. 사용자가 필드에 입력을 시작하면 브라우저는 이전에 입력한 값을 기반으로 필드를 채우는 옵션을 표시해야 합니다.

자동 완성 속성은 텍스트, 검색, url, tel, 이메일, 암호, 날짜 표시기, 범위 및 색상과 같은 \<form>태그에 속하는 \<input> 유형에서 작동합니다.

예시
하나의 입력 필드에 대해 자동 완성 기능을 켜고 끄는 HTML 양식:

<form action="/action_page.php" autocomplete="on">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" autocomplete="off"><br><br>
  <input type="submit" value="Submit">
</form>

    <form action="/action_page.php" autocomplete="on">
    <label for="fname">First name:</label>
    <input type="text" id="fname" name="fname"><br><br>
    <label for="lname">Last name:</label>
    <input type="text" id="lname" name="lname"><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" autocomplete="off"><br><br>
    <input type="submit" value="Submit">
    </form>


팁: 일부 브라우저에서는 자동 완성 기능을 활성화해야 작동할 수 있습니다(브라우저 메뉴의 "기본 설정" 참조).