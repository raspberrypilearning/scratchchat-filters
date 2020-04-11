## コスチュームの切りかえ方

--- task ---

Now that you have your glasses positioned, you can use some simple key presses to change their style. このコードブロックをスプライトに追加します。

```blocks3
[右向き矢印v] キーが押されたとき
次のコスチュームにする
```

--- /task ---

--- task ---

キーボードの右矢印キーを押して (おして)、メガネが変わることをたしかめましょう。

![ハートがたのメガネをかけている男の人の画像](images/heart-glasses.png)

--- /task ---

--- task ---

左矢印キーを使用して、前のコスチュームにもどるようにもしたいですね。 これを行うには、 `コスチューム番号`{:class="block3looks"}を使い、 `1` を引き算する必要があります。

```blocks3
when [left arrow v] key pressed
switch costume to ((costume [number v]) - (1))
```

--- /task ---

--- task ---

To add some more costumes to your sprite, click on the **Costumes** tab and then on the **Choose a Costume** button in the bottom left-hand corner of the screen.

![image showing the Choose a costume button with the menu opened](images/choose-costume.png)

--- /task ---

--- task ---

In the **Costumes** tab, you can select all the parts of a costume by holding down the Ctrl key on your keyboard and then pressing the letter A key. You can then move and resize each costume so they are in the correct place.

![image of man with alien antenna on his head](images/alien-antenna.png)

--- /task ---

--- task ---

Now you can use the arrow keys to cycle through all your different costumes.

![animated gif of a man with different costumes on](images/costumes.gif)

--- /task ---

