## 의상 컨트롤 추가

이제 컨트롤을 추가하여 스프라이트의 크기를 변경하고 이미지를 보이게 하거나 보이지 않게 할 수 있습니다.

--- task ---

스프라이트가 나타나거나 사라지게 할 수 있도록 이 블럭을 추가합니다.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

이제 의상의 크기를 바꿀수 있는 블럭들을 추가합니다.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

스프라이트의 위치를 바꿀수 있는 컨트롤을 추가할 수 있는지 살펴 봅시다.

--- hints --- --- hint ---

스프라이트의 위치를 올리거나 낮출 때 사용하고자 하는 키를 설정하기 위해서 `x 좌표를 () 만큼 바꾸기`{:class="block3motion"}와 `y 좌표를 () 만큼 바꾸기`{:class="block3motion"} 블럭을 사용합니다.

--- /hint --- --- hint ---

이 두 블럭은 스프라이트를 왼쪽으로 옮깁니다.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

다음의 준비된 코드에 여러분이 스프라이트를 옮길 때 사용하고 싶은 키를 설정하세요.

```blocks3
when [j v] key pressed
change x by (-10)

when [l v] key pressed
change x by (10)

when [o v] key pressed
change y by (10)

when [k v] key pressed
change y by (-10)
```

--- /hint --- --- /hints ---



--- /task ---


