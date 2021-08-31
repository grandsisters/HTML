## HTML 텍스트 서식

<br>

HTML에는 특별한 의미를 가진 텍스트를 정의하기 위한 여러 요소가 포함되어 있습니다.

    예시
    This text is bold

    This text is italic

    This is subscript and superscript

***
### HTML 서식 요소

서식 요소는 다음과 같은 특수 유형의 텍스트를 표시하도록 설계되었습니다.

    <b> - 굵은 텍스트
    <strong> - 중요한 텍스트
    <i> - 기울임꼴 텍스트
    <em> - 강조된 텍스트
    <mark> - 표시된 텍스트
    <small> - 더 작은 텍스트
    <del> - 삭제된 텍스트
    <ins> - 삽입된 텍스트
    <sub> - 아래 첨자 텍스트
    <sup> - 위 첨자 텍스트

***
### HTML \<b> 및 \<strong> 요소

HTML \<b>요소는 추가적인 중요성 없이 굵은 텍스트를 정의합니다.

    예시
    <b>This text is bold</b>

HTML \<strong>요소는 매우 중요한 텍스트를 정의합니다. 

내부 콘텐츠는 일반적으로 굵게 표시됩니다.

    예시
    <strong>This text is important!</strong>

***
### HTML \<i> 및 \<em> 요소

HTML \<i>요소는 대체 음성 또는 분위기에서 텍스트의 일부를 정의합니다. 내부 콘텐츠는 일반적으로 기울임꼴로 표시됩니다.

팁 :\<i> 태그는 종종 등 다른 언어, 생각, 배의 이름에서 문구를 전문 용어를 표시하는 데 사용됩니다

    예시
    <i>This text is italic</i>
    HTML <em>요소는 강조된 텍스트를 정의합니다. 내부 콘텐츠는 일반적으로 기울임꼴로 표시됩니다.

팁: 스크린 리더는 \<em> 강세를 사용하여 in 을 강조 하여 단어를 발음합니다 .

    예시
    <em>This text is emphasized</em>

***
### HTML \<small> 요소

HTML \<small>요소는 더 작은 텍스트를 정의합니다.

    예시
    <small>This is some smaller text.</small>

***
### HTML \<mark> 요소

HTML \<mark>요소는 표시하거나 강조 표시해야 하는 텍스트를 정의합니다.

    예시
    <p>Do not forget to buy <mark>milk</mark> today.</p>

***
### HTML \<del> 요소
HTML \<del>요소는 문서에서 삭제된 텍스트를 정의합니다. 브라우저는 일반적으로 삭제된 텍스트에 줄을 긋습니다.

    예시
    <p>My favorite color is <del>blue</del> red.</p>

*** 
### HTML \<ins> 요소

HTML \<ins>요소는 문서에 삽입된 텍스트를 정의합니다. 브라우저는 일반적으로 삽입된 텍스트에 밑줄을 긋습니다.

    예시
    <p>My favorite color is <del>blue</del> <ins>red</ins>.</p>

***
### HTML \<sub> 요소

HTML \<sub>요소는 아래 첨자 텍스트를 정의합니다. 

아래 첨자 텍스트는 일반 줄 아래 반 문자로 나타나며 때로는 더 작은 글꼴로 렌더링됩니다. 

아래 첨자 텍스트는 H 2 O 와 같은 화학식에 사용할 수 있습니다 .

    예시
    <p>This is <sub>subscripted</sub> text.</p>

***
### HTML \<sup> 요소

HTML \<sup>요소는 위 첨자 텍스트를 정의합니다. 

위 첨자 텍스트는 일반 줄 위의 문자 반으로 나타나며 때로는 더 작은 글꼴로 렌더링됩니다. 

위 첨자 텍스트는 WWW [1] 와 같은 각주에 사용할 수 있습니다 .

    예시
    <p>This is <sup>superscripted</sup> text.</p>