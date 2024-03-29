## 의상 바꿔 입기

--- task ---

이제 안경을 썼으니 간단한 키 조작으로 스타일을 바꿔보겠습니다. 아래 코드 블록을 스프라이트에 추가합니다.

```blocks3
when [right arrow v] key pressed
next costume
```

--- /task ---

--- task ---

키보드의 오른쪽 화살표 키를 누르면 안경 스타일이 변하는 것을 볼수있습니다.

![심장 모양의 안경을 쓴 남자의 이미지](images/heart-glasses.png)

--- /task ---

--- task ---

왼쪽 화살표 키를 누르면 이전 의상으로 돌아갑니다. 이전 의상으로 돌아가려면 `의상 번호`{:class="block3looks"}를 사용해야 하는데 `1` 을 빼는 것으로 구현합니다.

```blocks3
when [left arrow v] key pressed
switch costume to ((costume [number v]) - (1))
```

--- /task ---

--- task ---

스프라이트에 의상을 더 추가하고 싶다면 **의상** 탭을 클릭 한 다음 화면 왼쪽 아래의 **의상 선택** 버튼을 클릭하세요.

![메뉴가 열린 채 의상 선택 버튼을 보여주는 이미지](images/choose-costume.png)

--- /task ---

--- task ---

**의상** 탭에서 키보드의 Ctrl 키를 누른 상태에서 문자 A 키를 누르면 모든 의상을 선택할 수 있습니다. 이 상태에서 각각의 의상을 움직이거나 크기를 원하는대로 조정할 수 있습니다.

![머리에 외계인 안테나를 가진 남자의 이미지](images/alien-antenna.png)

--- /task ---

--- task ---

이제 화살표 키를 계속 눌러서 의상을 계속 바꿔볼수도 있습니다.

![다른 의상들을 입어보고 있는 남자의 움직이는 gif 이미지](images/costumes.gif)

--- /task ---

