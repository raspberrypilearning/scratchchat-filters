## 如何切换造型

--- task ---

现在您已经放置好眼镜，可以使用一些简单的按键来更改其样式。 将这些代码块添加到您的精灵中。

```blocks3
当 按下 [右箭头v] 键
下一个造型
```

--- /task ---

--- task ---

尝试按键盘上的右箭头键，以查看眼镜的样式变化。

![一个戴着心形眼镜的男人的形象](images/heart-glasses.png)

--- /task ---

--- task ---

您可能还想使用向左箭头键恢复到以前的造型。 为此，您需要使用 `造型编号`{:class="block3looks"}，然后让它减 `1`。

```blocks3
when [left arrow v] key pressed
switch costume to ((costume [number v]) - (1))
```

--- /task ---

--- task ---

要将更多造型添加到精灵中，请单击 **造型** 选项卡，然后单击屏幕左下角的 **选择一个造型** 按钮。

![该图显示了打开菜单时的“选择一个角色”按钮](images/choose-costume.png)

--- /task ---

--- task ---

在 **造型** 选项卡中，您可以通过按住键盘上的 Ctrl + A 键来选择造型的所有部分。 然后，您可以移动每个造型并调整其大小，以便将它们放在正确的位置。

![头上带着外星天线的人的形象](images/alien-antenna.png)

--- /task ---

--- task ---

现在，您可以使用方向键在所有不同的造型中循环。

![一个男人在不同造型的gif动画](images/costumes.gif)

--- /task ---

