## コスチュームのコントロール

コントロールを追加することで、スプライトの大きさを変えたり、画像を表示 (ひょうじ) するか隠す (かくす) かを決めることができます。

--- task ---

このブロックを追加して、スプライトを表示または非表示にします。

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

次に、さらにいくつかのブロックを追加して、コスチュームの大きさを変えます。

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

スプライトの位置を変えるためのコントロールを追加できますか？

--- hints --- --- hint ---

好きなキーを使って、`x座標 (ざひょう) を～ずつ変える`{:class="block3motion"}および`y座標を～ずつ変える`{:class="block3motion"}ブロックでスプライトの位置座標を増減(ぞうげん)します

--- /hint --- --- hint ---

これはスプライトを左に動かすための2つのブロックです。

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

ここに必要なすべてのコードがありますが、自分のスプライト用に使うキーは好きなものを選んでください。

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


