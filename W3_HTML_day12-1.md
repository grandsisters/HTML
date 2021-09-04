## HTML 테이블
HTML 테이블을 사용하면 웹 개발자가 데이터를 행과 열로 정렬할 수 있습니다.

예시
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
  <tr>
    <td>Ernst Handel</td>
    <td>Roland Mendel</td>
    <td>Austria</td>
  </tr>
  <tr>
    <td>Island Trading</td>
    <td>Helen Bennett</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Laughing Bacchus Winecellars</td>
    <td>Yoshi Tannamuri</td>
    <td>Canada</td>
  </tr>
  <tr>
    <td>Magazzini Alimentari Riuniti</td>
    <td>Giovanni Rovelli</td>
    <td>Italy</td>
  </tr>
</table>

***
### HTML 테이블 정의
HTML의 테이블은 행과 열 내부의 테이블 셀로 구성됩니다.

간단한 HTML 테이블:

[예시](./W3_HTML_day12-1-1.html)

***
### 테이블 셀
각 테이블 셀은 \<td>및 \</td>태그로 정의됩니다 .

td 테이블 데이터를 나타냅니다.

\<td>와 사이의 모든 것은 \</td>테이블 셀의 내용입니다.

    예시
    <table>
    <tr>
        <td>Emil</td>
        <td>Tobias</td>
        <td>Linus</td>
    </tr>
    </table>

참고: 테이블 데이터 요소는 테이블의 데이터 컨테이너입니다.
모든 종류의 HTML 요소를 포함할 수 있습니다. 텍스트, 이미지, 목록, 기타 테이블 등

***
### 테이블 행
각 테이블 행은 태그로 시작 \<tr>하고 \</tr>태그로 끝납니다 .

tr 테이블 행을 나타냅니다.

    예시
    <table>
    <tr>
        <td>Emil</td>
        <td>Tobias</td>
        <td>Linus</td>
    </tr>
    <tr>
        <td>16</td>
        <td>14</td>
        <td>10</td>
    </tr>
    </table>

테이블에 원하는 만큼의 행을 가질 수 있습니다. 

각 행의 셀 수가 동일한지 확인하기만 하면 됩니다.

참고: 행에 다른 행보다 셀이 적거나 많을 수 있는 경우가 있습니다. 

***
### 테이블 헤더
때로는 셀을 헤더로 사용하고 싶을 때가 있습니다. 

이 경우 \<th>태그 대신 태그를 사용하세요 \<td>.


첫 번째 행을 테이블 헤더로 설정합니다.

    예시
    <table>
    <tr>
        <th>Person 1</th>
        <th>Person 2</th>
        <th>Person 3</th>
    </tr>
    <tr>
        <td>Emil</td>
        <td>Tobias</td>
        <td>Linus</td>
    </tr>
    <tr>
        <td>16</td>
        <td>14</td>
        <td>10</td>
    </tr>
    </table>

기본적으로 \<th>요소 의 텍스트 는 굵게 중앙에 표시되지만 CSS를 사용하여 변경할 수 있습니다.

[HTML 테이블 태그](https://www.w3schools.com/tags/default.asp)