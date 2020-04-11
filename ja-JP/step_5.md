## 色フィルターを追加する

次に、画像に色フィルターを設定 (せってい) します。

--- task ---

**背景** (はいけい) アイコンをクリックします。

![ステージアイコンを表す画像](images/stage.png)

**背景**タブの**ビットマップに変換** (へんかん) を選びます 。 次に、**塗りつぶし** (ぬりつぶし) ツールを使って背景を一色で塗りつぶします。

![ステージの背景が塗りつぶされた画像](images/paint-bucket.png)

--- /task ---

--- task ---

次に、`色フィルター` {:class="block3variables"}および`透明度 (とうめいど) フィルター` {:class="block3variables"}という2つの変数 (へんすう) を作ります。 ステージでこれらの変数を右クリックして、両方を**スライダー**に設定します。

![スライダーに変更された変数を表す画像](images/sliders.png)

--- /task ---

--- task ---

To finish off your project, use these variables to alter the look of the filter.

```blocks3
when flag clicked
turn video (on v)
forever
set video transparency to (filter amount)
set [color v] effect to (filter colour)
```

--- /task ---

--- task ---

Now you can move the sliders to see the effect on your image.

--- /task ---




