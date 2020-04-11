## Больше способов управления костюмами

Теперь ты можешь добавить элементы управления, чтобы изменить размер спрайта, а также решить, будет ли изображение показано или скрыто.

--- task ---

Добавь эти блоки, чтобы спрайт появлялся и исчезал.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Теперь добавь ещё несколько блоков, чтобы изменить размер костюма.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Посмотри, можешь ли ты добавить ещё несколько элементов управления, чтобы изменить положение спрайта.

--- hints --- --- hint ---

Используй любые клавиши, которые бы ты хотел, чтобы увеличить или уменьшить положение спрайта, применяя блоки `изменить x на`{:class="block3motion"} и `изменить y на`{:class="block3motion"}

--- /hint --- --- hint ---

Вот два блока, которые перемещают спрайт влево.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Вот весь код, который тебе нужен, но ты можешь выбрать любую клавишу для своего спрайта.

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


