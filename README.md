# learnHTML

- div(block) 내부 정가운데 정렬 팁
  display: flex;
  justify-content: center;
  align-items: center;

- span 크기조절
  span은 원래 inline이므로
  display: block;
  후에 크기조절

- padding때문에 원래 길이가 늘어나서
  밀려났을때 border에 맞게 해주려면
  box-sizing: border-box;

- 블럭 3개 중 하나 정중앙 위치시킬때
  3블럭에 width: 33%;
  양끝 블럭은 margin-right(or left): auto;
  가운데블럭은 center

- 블럭의 우선순위정하기
  z-index: 숫자;
  z축 수치라고 생각하면 될듯.

- span을 아래 끝으로 위치시키려면
  부모는
  flex-direction: column
  자식은
  display: flex
  align-items: flex-end
