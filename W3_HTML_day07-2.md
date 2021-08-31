## HTML 인용 및 인용 요소

이 장에서 \<blockquote>, \<q>, \<abbr>, \<address>, \<cite>, 및 \<bdo> HTML 요소를 알아보자

***
### 인용을 위한 HTML \<blockquote>
HTML \<blockquote>요소는 다른 소스에서 인용된 섹션을 정의합니다.

브라우저는 일반적으로 \<blockquote>요소를 들여씁니다 .

    예시
    <p>Here is a quote from WWF's website:</p>
    <blockquote cite="http://www.worldwildlife.org/who/index.html">
    For 50 years, WWF has been protecting the future of nature.
    The world's leading conservation organization,
    WWF works in 100 countries and is supported by
    1.2 million members in the United States and
    close to 5 million globally.
    </blockquote>

***
### 짧은 인용문을 위한 HTML \<q>
HTML \<q>태그는 짧은 인용문을 정의합니다.

브라우저는 일반적으로 따옴표 주위에 따옴표를 삽입합니다.

    예시
    <p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>

***
### 약어용 HTML \<abbr>
HTML \<abbr>태그는 "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM"과 같은 약어 또는 두문자어를 정의합니다.

약어를 표시하면 브라우저, 번역 시스템 및 검색 엔진에 유용한 정보를 제공할 수 있습니다.

팁: 전역 제목 속성을 사용하여 요소 위에 마우스를 놓을 때 약어/두문자어에 대한 설명을 표시하십시오. 

    예시
    <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

***
### 연락처 정보용 HTML \<address>
HTML \<address>태그는 문서 또는 기사의 작성자/소유자에 대한 연락처 정보를 정의합니다.

연락처 정보는 이메일 주소, URL, 실제 주소, 전화번호, 소셜 미디어 핸들 등이 될 수 있습니다.

\<address>요소 의 텍스트는 일반적으로 기울임꼴로 렌더링되며 브라우저는 항상 \<address>요소 앞뒤에 줄 바꿈을 추가합니다 .

    예시
    <address>
    Written by John Doe.<br>
    Visit us at:<br>
    Example.com<br>
    Box 564, Disneyland<br>
    USA
    </address>

***
### 작품 제목에 대한 HTML \<cite>
HTML \<cite>태그는 창작물(예: 책, 시, 노래, 영화, 그림, 조각 등)의 제목을 정의합니다.

참고: 사람의 이름은 작품의 제목이 아닙니다.

\<cite>요소 의 텍스트는 일반적으로 기울임꼴로 렌더링됩니다 .

    예시
    <p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

***
### 양방향 재정의를 위한 HTML \<bdo>
BDO는 양방향 재정의를 의미합니다.

HTML \<bdo>태그는 현재 텍스트 방향을 재정의하는 데 사용됩니다.

    예시
    <bdo dir="rtl">This text will be written from right to left</bdo>