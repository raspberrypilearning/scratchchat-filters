## Mais controles de fantasia

Agora você pode adicionar controles para alterar o tamanho do ator e também decidir se a imagem é mostrada ou oculta.

--- task ---

Adicione estes blocos para fazer o ator aparecer e desaparecer.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Agora adicione mais alguns blocos para mudar o tamanho da fantasia.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Veja se você pode adicionar mais controles para alterar a posição do ator.

--- hints --- --- hint ---

Use as teclas que desejar para aumentar ou diminuir a posição do ator usando os blocos `adicione () a x`{:class="block3motion"} e `adicione () a y`{:class="block3motion"}

--- /hint --- --- hint ---

Aqui estão dois blocos que movem o ator para a esquerda.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Aqui está todo o código que você precisa, mas escolha quaisquer teclas que você queira para seu ator.

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


