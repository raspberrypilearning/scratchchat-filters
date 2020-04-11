## Подальше управління образами

Тепер ти можеш додати елементи керування для зміни розміру спрайта, а також для показування чи приховування зображення.

--- task ---

Додай ці блоки, щоб змусити спрайт відображатися або сховатися.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Тепер додай ще трохи блоків для зміни розміру образа.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Подумай, чи можеш ти додати ще деякі елементи управління для зміни положення спрайта.

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


