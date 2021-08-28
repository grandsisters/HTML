## HTML 단락

단락은 항상 새 줄에서 시작하며 일반적으로 텍스트 블록입니다.

HTML \<p>요소는 단락을 정의합니다.

단락은 항상 새 줄에서 시작하고 브라우저는 단락 앞뒤에 일부 공백(여백)을 자동으로 추가합니다.

    예시
    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>

***
### HTML 디스플레이

<br>

HTML이 어떻게 표시될지 확신할 수 없습니다.

크거나 작은 화면, 크기 조정된 창은 다른 결과를 생성합니다.

HTML을 사용하면 HTML 코드에 공백이나 줄을 추가하여 표시를 변경할 수 없습니다.

브라우저는 페이지가 표시될 때 추가 공백과 줄을 자동으로 제거합니다.

    예시
    <p>
    This paragraph
    contains a lot of lines
    in the source code,
    but the browser
    ignores it.
    </p>

    <p>
    This paragraph
    contains         a lot of spaces
    in the source         code,
    but the        browser
    ignores it.
    </p>

***
### HTML 수평 규칙

<br>

\<hr>태그는 HTML 페이지에서 주제 휴식을 정의하고, 가장 자주 수평선으로 표시됩니다.

\<hr>요소는 콘텐츠를 분리 (또는 변경 정의)는 HTML 페이지를 위해 사용된다.

    예시
    <h1>This is heading 1</h1>
    <p>This is some text.</p>
    <hr>
    <h2>This is heading 2</h2>
    <p>This is some other text.</p>
    <hr>

\<hr>태그는 끝 태그가 없음을 의미 빈 태그입니다.

***
### 시 문제

<br>

이 시는 한 줄로 표시됩니다.

예시
<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>


### 솔루션 - HTML <pre> 요소

<br>

HTML \<pre>요소는 미리 형식이 지정된 텍스트를 정의합니다.

\<pre>요소 내부의 텍스트 는 고정 너비 글꼴(보통 Courier)로 표시되며 공백과 줄 바꿈을 모두 유지합니다.

    예시
    <pre>
    My Bonnie lies over the ocean.

    My Bonnie lies over the sea.

    My Bonnie lies over the ocean.

    Oh, bring back my Bonnie to me.
    </pre>