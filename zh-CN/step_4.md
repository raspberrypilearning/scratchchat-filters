## 控制更多造型

您可以添加代码块来更改精灵的大小，还可以更改造型是显示还是隐藏。

--- task ---

添加这些代码块以使精灵显示和消失。

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

现在添加更多代码块以更改造型的大小。

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

看看你是否可以添加更多代码块来更改精灵的位置。

--- hints --- --- hint ---

使用您喜欢的任何键通过 `将x坐标增加`{:class="block3motion"} 和`将y坐标增加`{:class="block3motion"} 来更改精灵的位置

--- /hint --- --- hint ---

这是两个能让精灵向左移动的代码块。

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

这是您需要的所有代码，但请选择所需的按键。

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


