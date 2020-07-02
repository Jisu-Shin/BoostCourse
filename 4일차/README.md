# Day4 : 20-07-02
* list-style:none
  > 옆에 점 표시를 없애준다

* width:20% / margin-left:5%
  > px를 하는 것보다 전체적인 비율을 주기 위해 %를 사용한다

* float:left
  >wrap안 모든 div에 float:left를 줘서 나란히 나열되게 만든다

* overflow:auto;
  > **자식요소에 float를 줄경우 부모는 인식하지 못한다**
  > 그래서 background-color가 사라진다 그래서 부모요소에 overflow:auto를 줘야한다

* position:(relative/absolute)
  > 자식요소에 absolute를 주면 부모 요소(relative) 범위 내에서 움직인다
  > 자식요소가 relative를 주면 부모 요소 범위 밖에서도 움직인다

* clear:(left,right,both)
  > float를 할 경우 아래 요소가 위로 올라오는 것을 막는다

* flex는 float와 다르게 위로 쌓는다는 개념이 아니라 좌우로 나뉘는 개념 같다...?

* [Java Code 규칙](https://myeonguni.tistory.com/1596)
