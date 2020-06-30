# Day3 : 20-06-30
* display: (block,inline)
  > 기본값은 block 이다
  inline은 상단메뉴처럼 오른쪽으로 나열한다.
  inline은 설정을 줘도 적용이 안된다
* position:(static,relative,absolute,fixed)
  > relative는 사실 좀 헷갈린다.. static과 차이점이 뭐지
  absolute는 상위 element중 static이 아닌 것을 기준으로 top,left,right,bottom 이동한다. 이리저리 잘 바뀌어진다
  fixed 광고처럼 고정되어 있다
* float:(left,right,middle)
  >3차원처럼 위로 뜨여있다 그래서 float를 안쓴 element에서 쓰이면 아래에 있던 element가 올라온다
* box-sizing :(border-box, content-box)
  >border-box는 테두리 친곳에서 padding값을 더 줘도 안커질려고 노력한다 padding 너무 많이 주면 커지긴 함
  content-box는 padding 값 주는 만큼 커진다
* margin > border > padding 박스 범위
