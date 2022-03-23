# 01.

## 🌈 table 태그

✓ 행과 열로 이루어진 표를 나타낸다.

### 📌 종류

1. caption
2. colgroup
3. col
4. table

## 1. caption

✓ 표의 설명 또는 제목을 나타낸다.

- 전역 특성만 표함한다.
- 부모 table 요소의 <b>첫 번째 자식</b>이어야 한다.
- caption 요소를 가진 table 요소가 만약 figure태그 요소의 유일한 자식일 경우, <b>figcation</b>을 사용하여야한다.

## 2. colgroup

✓ 표의 열을 묶는 그룹을 의미한다.

- 전역 특성을 포함한다. <br>

### 📌 특징

- background-color 속성을 사용할 수 있다.
- span 태그 👉 열의 수를 나타내는 양의 정수로 기본값은 1이다. <br>✅ col 요소가 존재하면 사용할 수 없다.

## 3. col

✓ 표의 열을 나타내며, 열에 속하는 칸에 공통된 의미를 부여 할 때 사용한다.

- colgroup 태그 안에서 찾을 수 있다.
- 전역 특성을 포함한다.
- col이 차지할 열의 수를 나타내는 양의 정수.
- 기본값은 1이다.

## 4. table

✓ 행과 열로 이루어진 표를 나타낸다.

- 선택적인 <b>caption</b> 요소
- 0개 이상의 <b>colgroup</b> 요소
- 선택적인 <b>thead</b> 요소
- 0개 이상의 <b>tbody</b> 요소
- 0개 이상의 <b>tr</b> 요소
- 선택적인 <b>tfoot</b> 요소

✏️ 예제

```
<table>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Doe</td>
  </tr>
</table>
```
