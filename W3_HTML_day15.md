## HTML 블록 및 인라인 요소
모든 HTML 요소에는 요소 유형에 따라 기본 표시 값이 있습니다.

표시 값에는 블록과 인라인의 두 가지가 있습니다.

***
### 블록 수준 요소
블록 수준 요소는 항상 새 줄에서 시작합니다.

블록 수준 요소는 항상 사용 가능한 전체 너비를 차지합니다(가능한 한 왼쪽과 오른쪽으로 늘어남).

블록 수준 요소에는 위쪽 및 아래쪽 여백이 있는 반면 인라인 요소에는 없습니다.

\<div> 요소는 블록 수준 요소입니다.

    예시
    <div>Hello World</div>

다음은 HTML의 블록 수준 요소입니다.

    <address> <article> <aside>

    <blockquote>

    <canvas>

    <dd> <div> <dl> <dt>

    <fieldset> <figcaption> <figure> <footer> <form>

    <h1>-<h6> <header> <hr>

    <li>

    <main>

    <nav> <noscript>

    <ol>

    <p> <pre>

    <section>

    <table> <tfoot>

    <ul>

    <video>

***
### 인라인 요소
인라인 요소는 새 줄에서 시작하지 않습니다.

인라인 요소는 필요한 만큼만 너비를 차지합니다.

이것은 단락 내부의 \<span> 요소 입니다.

    예시
    <span>Hello World</span>

HTML의 인라인 요소는 다음과 같습니다.

    <a> <abbr> <acronym>

    <b> <bdo> <big> <br> <button>

    <cite> <code>

    <dfn>

    <em>

    <i> <img> <input>

    <kbd>

    <label>

    <map>

    <object> <output>

    <q>

    <samp> <script> <select> <small> <span> <strong> <sub> <sup>

    <textarea> <time> <tt>

    <var>

참고: 인라인 요소는 블록 수준 요소를 포함할 수 없습니다!

***
### \<div> 요소
\<div>요소는 종종 다른 HTML 요소에 대한 컨테이너로 사용됩니다.

\<div>요소에 속성이 필요 없지만, style, class그리고 id을 사용하는 것이 일반적이다.

CSS와 함께 사용할 때 \<div>요소는 콘텐츠 블록의 스타일을 지정하는 데 사용할 수 있습니다.

예시
<div style="background-color:black;color:white;padding:20px;">
<h2>London</h2>
<p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
</div>

    예시
    <div style="background-color:black;color:white;padding:20px;">
    <h2>London</h2>
    <p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
    </div>

***
### \<span> 요소
\<span>요소는 텍스트, 또는 문서의 일부의 부분을 표시하는 데 사용 인라인 용기이다.

\<span>요소에 속성이 필요 없지만, style, class그리고 id을 사용하는 것이 일반적이다.

CSS와 함께 사용하면 \<span>요소를 사용하여 텍스트 부분의 스타일을 지정할 수 있습니다.

예시
<p>My mother has <span style="color:blue;font-weight:bold">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold">dark green</span> eyes.</p>

    예시
    <p>My mother has <span style="color:blue;font-weight:bold">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold">dark green</span> eyes.</p>