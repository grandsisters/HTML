## HTML 파일 경로
파일 경로는 웹 사이트의 폴더 구조에서 파일의 위치를 ​​설명합니다.

***
### HTML 파일 경로
파일 경로는 웹 사이트의 폴더 구조에서 파일의 위치를 ​​설명합니다.

파일 경로는 다음과 같은 외부 파일에 연결할 때 사용됩니다.

- 웹 페이지
- 이미지
- 스타일 시트
- 자바스크립트

***
### 절대 파일 경로
절대 파일 경로는 파일의 전체 URL입니다.

예시

<img src="https://www.w3schools.com/images/picture.jpg" alt="Mountain">

    예시
    <img src="https://www.w3schools.com/images/picture.jpg" alt="Mountain">

***
### 상대 파일 경로
상대 파일 경로는 현재 페이지에 상대적인 파일을 가리킵니다.

다음 예에서 파일 경로는 현재 웹의 루트에 있는 이미지 폴더의 파일을 가리킵니다.

    예시
    <img src="/images/picture.jpg" alt="Mountain">

다음 예에서 파일 경로는 현재 폴더에 있는 이미지 폴더의 파일을 가리킵니다.

    예시
    <img src="images/picture.jpg" alt="Mountain">

다음 예에서 파일 경로는 현재 폴더에서 한 수준 위 폴더에 있는 이미지 폴더의 파일을 가리킵니다.

    예시
    <img src="../images/picture.jpg" alt="Mountain">

가능한 경우 상대 파일 경로를 사용하는 것이 가장 좋습니다.

상대 파일 경로를 사용할 때 웹 페이지는 현재 기본 URL에 바인딩되지 않습니다.

모든 링크는 자신의 컴퓨터(localhost)는 물론 현재 공개 도메인과 미래의 공개 도메인에서도 작동합니다.