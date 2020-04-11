## Mais controles de fantasia

Agora você pode adicionar controles para alterar o tamanho do ator e também decidir se a imagem é mostrada ou oculta.

--- task ---

Adicione estes blocos para fazer o ator aparecer e desaparecer.

```blocks3
quando a tecla [s v] for pressionada
mostre

quando a tecla [h v] for pressionada
esconda
```

--- /task ---

--- task ---

Agora adicione mais alguns blocos para mudar o tamanho da fantasia.

```blocks3
quando a tecla [seta para cima v] for pressionada
mude (10) no tamanho

quando a tecla [seta para baixo v] for pressionada
mude (-10) no tamanho
```

--- /task ---

--- task ---

Veja se você pode adicionar mais controles para alterar a posição do ator.

--- hints --- --- hint ---

Use any keys you like to increase or decrease the sprite's position by using the `change x by`{:class="block3motion"} and `change y by`{:class="block3motion"} blocks

--- /hint --- --- hint ---

Here are two blocks that move the sprite left.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Here is all the code you need, but choose any keys you want for your sprite.

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


