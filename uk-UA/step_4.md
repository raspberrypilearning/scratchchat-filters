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

Викристовуй клавіші, які забажаєш, для зміни позиції спрайта за допомогою блоків `змінити x на`{:class="block3motion"} та `змінити y на`{:class="block3motion"}.

--- /hint --- --- hint ---

Ось два блоки, що переміщують спрайт вліво.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Ось увесь потрібний тобі код, але для свого спрайта ти можеш використовувати інші клавіші.

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


