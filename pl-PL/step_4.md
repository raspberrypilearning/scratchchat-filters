## Więcej ustawień kostiumów

Teraz możesz dodać kod, który umożliwi Ci zmianę rozmiaru duszka i zdecydowanie czy ma być on widoczny, czy ukryty.

--- task ---

Dodaj te bloki, by sprawić, że duszek będzie mógł pojawiać się i znikać.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Teraz dodaj więcej bloków do Twojego kodu, tak by można było zmienić rozmiar kostiumu.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Sprawdź, czy jesteś w stanie kontrolować pozycję duszka.

--- hints ---
 --- hint ---

Wybierz, które klawisze mają zmieniać położenie duszka. Aby zmieniać jego pozycję zwiększaj lub zmniejszaj wartości współrzędnych x i y za pomocą poleceń `zmień x o`{class="block3motion"} i `zmień y o`{class="block3motion"}

--- /hint --- --- hint ---

Oto dwa bloki, które powodują przesunięcie się duszka w lewo.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Oto cały kod, którego potrzebujesz, ale wybierz własne klawisze do zmiany pozycji duszka.

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

--- /hint ------ /hints ---



--- /task ---


