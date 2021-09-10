## HTML 컴퓨터 코드 요소
HTML에는 사용자 입력 및 컴퓨터 코드를 정의하기 위한 여러 요소가 포함되어 있습니다.

    예시
    <code>
        x = 5;
        y = 6;
        z = x + y;
    </code>

***
### 키보드 입력용 HTML \<kbd>
HTML \<kbd>요소는 키보드 입력을 정의하는 데 사용됩니다. 내부 콘텐츠는 브라우저의 기본 고정 폭 글꼴로 표시됩니다.

문서에서 일부 텍스트를 키보드 입력으로 정의:

    예시
    <p>Save the document by pressing <kbd>Ctrl + S</kbd></p>
    
    결과
    Save the document by pressing Ctrl + S

***
### 프로그램 출력용 HTML \<samp>
HTML \<samp>요소는 컴퓨터 프로그램의 샘플 출력을 정의하는 데 사용됩니다. 

내부 콘텐츠는 브라우저의 기본 고정 폭 글꼴로 표시됩니다.

    문서에 있는 컴퓨터 프로그램의 샘플 출력으로 일부 텍스트를 정의합니다.

    예시
    <p>Message from my computer:</p>
    <p><samp>File not found.<br>Press F1 to continue</samp></p>

    결과
    Message from my computer:
    File not found.
    Press F1 to continue

***
### 컴퓨터 코드용 HTML \<code>
HTML \<code>요소는 컴퓨터 코드를 정의하는 데 사용됩니다. 내부 콘텐츠는 브라우저의 기본 고정 폭 글꼴로 표시됩니다.

문서에서 일부 텍스트를 컴퓨터 코드로 정의:

    예시
    <code>
        x = 5;
        y = 6;
        z = x + y;
    </code>

    결과:
    x = 5; y = 6; z = x + y;

\<code>요소가 추가 공백과 줄 바꿈을 보존하지 않습니다.

이 문제를 해결하려면 \<code>요소 내부에 \<pre>요소를 넣을 수 있습니다 .

    예시
    <pre>
        <code>
            x = 5;
            y = 6;
            z = x + y;
        </code>
    </pre>

    결과:
    x = 5;
    y = 6;
    z = x + y;

***
### 변수용 HTML \<var>
HTML \<var>요소는 프로그래밍이나 수학적 표현에서 변수를 정의하는 데 사용됩니다. 

내부 콘텐츠는 일반적으로 기울임꼴로 표시됩니다.

    문서에서 일부 텍스트를 변수로 정의합니다.
    예시
    <p>The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height.</p>

    결과:
    The area of a triangle is: 1/2 x b x h, where b is the base, and h is the vertical height.