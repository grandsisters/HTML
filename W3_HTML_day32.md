## HTML Versus XHTML

XHTML은 더 엄격하고 XML 기반의 HTML 버전입니다.

***
### XHTML이란 무엇입니까?
- XHTML은 EXtensible HyperTEXT Markup Language의 약자
- XHTML은 더 엄격하고 XML 기반의 HTML 버전입니다.
- XHTML은 XML 애플리케이션으로 정의된 HTML입니다.
- XHTML은 모든 주요 브라우저에서 지원됩니다.

***
### 왜 XHTML인가?
XML은 모든 문서가 올바르게 마크업되어야 하는 마크업 언어입니다("올바른 형식"이어야 함).

XHTML은 다른 데이터 형식(예: XML)과 함께 작동하도록 HTML을 보다 확장 가능하고 유연하게 만들기 위해 개발되었습니다. 또한 브라우저는 HTML 페이지의 오류를 무시하고 마크업에 약간의 오류가 있더라도 웹사이트를 표시하려고 합니다. 따라서 XHTML은 훨씬 더 엄격한 오류 처리와 함께 제공됩니다.

***
### HTML과의 가장 중요한 차이점
- \<!DOCTYPE>은(는) 필수 항목입니다.
- xmlns의 \<html> 속성은 필수입니다.
- \<html>, \<head>, \<title>, \<body>는 필수입니다.
- 요소는 항상 적절하게 중첩 되어야 합니다.
- 요소는 항상 닫혀 있어야 합니다.
- 요소는 항상 소문자여야 합니다.
- 속성 이름은 항상 소문자여야 합니다.
- 속성 값은 항상 따옴표 로 묶어야 합니다.
- 속성 최소화는 금지되어 있습니다.

***
### XHTML - \<!DOCTYPE ....> 필수입니다.
XHTML 문서에는 XHTML <!DOCTYPE> 선언이 있어야 합니다.

\<html>, \<head>, \<title> 및 \<body> 요소도 있어야 하며 \<html>의 xmlns 속성은 문서의 xml 네임스페이스를 지정해야 합니다.

    예시
    다음은 최소한의 필수 태그가 있는 XHTML 문서입니다. 

    <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN"
    "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
    <html xmlns="http://www.w3.org/1999/xhtml">
        <head>
            <title>Title of document</title>
        </head>
        <body>

            some content here...

        </body>
    </html>

***
### HTML 요소는 적절하게 중첩되어야 합니다.
XHTML에서 요소는 다음과 같이 항상 서로 적절하게 중첩되어야 합니다.

    옳은:
    <b><i>Some text</i></b>

    잘못된:
    <b><i>Some text</b></i>

***
### XHTML 요소는 항상 닫아야 합니다.
XHTML에서 요소는 다음과 같이 항상 닫혀 있어야 합니다.

    옳은:
    <p>This is a paragraph</p>
    <p>This is another paragraph</p>

    잘못된:
    <p>This is a paragraph
    <p>This is another paragraph

***
### XHTML 빈 요소는 항상 닫아야 합니다.
XHTML에서 다음과 같이 빈 요소는 항상 닫아야 합니다.

    옳은:
    A break: <br />
    A horizontal rule: <hr />
    An image: <img src="happy.gif" alt="Happy face" />

    잘못된:
    A break: <br>
    A horizontal rule: <hr>
    An image: <img src="happy.gif" alt="Happy face">

***
### XHTML 요소는 소문자여야 합니다.
XHTML에서 요소 이름은 다음과 같이 항상 소문자여야 합니다.

    옳은:
    <body>
    <p>This is a paragraph</p>
    </body>

    잘못된:
    <BODY>
    <P>This is a paragraph</P>
    </BODY>

***
### XHTML 속성 이름은 소문자여야 합니다.
XHTML에서 속성 이름은 다음과 같이 항상 소문자여야 합니다.

    옳은:
    <a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>

    잘못된:
    <a HREF="https://www.w3schools.com/html/">Visit our HTML tutorial</a>

***
### XHTML 속성 값은 따옴표로 묶어야 합니다.
XHTML에서 속성 값은 다음과 같이 항상 인용되어야 합니다.

    옳은:
    <a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>

    잘못된:
    <a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>

***
### XHTML 속성 최소화 금지
XHTML에서는 속성 최소화가 금지됩니다.

    옳은:
    <input type="checkbox" name="vehicle" value="car" checked="checked" />
    <input type="text" name="lastname" disabled="disabled" />

    잘못된:
    <input type="checkbox" name="vehicle" value="car" checked />
    <input type="text" name="lastname" disabled />