# 02.

## 🌈 React에서 table태그 사용하기

### 🧐 table이란?

- HTML의 DOM중 하나로 행과 열로 이루어진 표를 나타내는 태그
- 하위 요소로 <br><b>thead<br> tbody<br> tr<br> td<br> th</b> 등이 있다.
  <br>
  <br>

### 📌 JSX에서 table 사용하기.

#### ✓ <b>tbody</b> 와 <b>thead</b> 를 반드시 사용해야 한다.

- HTML에서의 table은 tbody를 생략하고 바로 tr과 td를 사용할 수 있지만, <br> ✏️ JSX에서는 반드시 <b>tbody를 선언해야 tr과 td를 사용 할 수 있다</b>.
- tbody를 선언하지 않는 경우에는 오류가 발생한다.

✓ 마찬가지로 <b>thead를 작성해야 th를 사용할 수 있다</b>.

<br>

#### ✅ tbody와 thead를 작성해야되는 이유

- React가 리렌더링을 진행할 때 DOM tree가 예상과는 달리 진행될 수 있으므로 작성을 해야한다.
