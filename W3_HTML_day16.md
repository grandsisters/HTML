## HTML 클래스 속성
HTML class속성은 HTML 요소에 대한 클래스를 지정하는 데 사용됩니다.

여러 HTML 요소가 동일한 클래스를 공유할 수 있습니다.

***
### 클래스 속성 사용하기
class속성은 종종 스타일 시트 클래스 이름에 포인트로 사용됩니다. 

특정 클래스 이름을 가진 요소에 액세스하고 조작하기 위해 JavaScript에서 사용할 수도 있습니다.

다음 예시에는 "city"라는 값의 class 속성을 가진 세 개의 \<div>요소가 있습니다. 

세 가지 \<div> 요소는 모두 .city head 섹션 의 스타일 정의에 따라 동일하게 스타일이 지정됩니다.

[예시](./W3_HTML_day16-1.html)

다음 예시에는 값이 "note"인 class 속성의 \<span>요소가 두 개의 있습니다. 

두 \<span>요소 모두 .note 헤드 섹션 의 스타일 정의에 따라 동일하게 스타일이 지정됩니다.

[예시](./W3_HTML_day16-2.html)

팁 : 어떤 HTML 요소에도 class 속성을 사용할 수 있습니다.

참고: 클래스 이름은 대소문자를 구분합니다.

***
### 클래스 구문
클래스를 생성하려면 마침표(.) 문자를 쓰고 그 뒤에 클래스 이름을 씁니다. 

그런 다음 중괄호 {} 안에 CSS 속성을 정의합니다.

"city"라는 클래스를 만듭니다.
[예시](./W3_HTML_day16-3.html)

***
### 여러 클래스
HTML 요소는 둘 이상의 클래스에 속할 수 있습니다.

여러 클래스를 정의하려면 클래스 이름을 공백으로 구분하십시오

(예: \<div class="city main">) 

요소는 지정된 모든 클래스에 따라 스타일이 지정됩니다.

다음 예제에서 첫 번째 \<h2>요소는 city클래스와 클래스 모두에 속하며 

두 클래스 모두 main에서 CSS 스타일을 가져옵니다. 

    예시
    <h2 class="city main">London</h2>
    <h2 class="city">Paris</h2>
    <h2 class="city">Tokyo</h2>

***
### 다른 요소가 동일한 클래스를 공유할 수 있음
다른 HTML 요소는 동일한 클래스 이름을 가리킬 수 있습니다.

다음 예에서 \<h2>및 둘 다 \<p> "city" 클래스를 가리키며 동일한 스타일을 공유합니다.

    예시
    <h2 class="city">Paris</h2>
    <p class="city">Paris is the capital of France</p>

***
### JavaScript에서 클래스 속성 사용
클래스 이름은 JavaScript에서 특정 요소에 대한 특정 작업을 수행하는 데 사용할 수도 있습니다.

JavaScript는 다음 getElementsByClassName()메소드를 사용하여 특정 클래스 이름을 가진 요소에 액세스할 수 있습니다 .

예시
버튼을 클릭하여 클래스 이름이 "city"인 모든 요소를 ​​숨깁니다.

    <script>
        function myFunction() {
            var x = document.getElementsByClassName("city");
            for (var i = 0; i < x.length; i++) {
                x[i].style.display = "none";
            }
        }
    </script>