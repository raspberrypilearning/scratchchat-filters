## 控制更多造型

您可以添加控制項目來更改精靈的大小，還可以決定要顯示還是隱藏圖像。

--- task ---

添加這些代碼塊使精靈顯示或消失。

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

現在添加更多代碼塊快來更改造型的大小。

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

看看是否可以添加更多控制項目來更改精靈的位置。

--- hints --- --- hint ---

使用您喜歡的任意鍵通過 `更改x座標`{:class="block3motion"} 和`更改y座標`{:class="block3motion"} 來更改精靈的位置

--- /hint --- --- hint ---

這是能讓精靈往左的兩個代碼塊。

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

這是您需要的所有代碼，但請為精靈選擇您想要的按鍵。

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


