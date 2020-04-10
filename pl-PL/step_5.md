## Dodaj filtr koloru

Teraz dodaj do swojego obrazka kolorowy filtr.

--- task ---

Naciśnij ikonę **Scena**.

![obrazek pokazujący ikonę sceny](images/stage.png)

Wejdź w zakładkę **Tła** i naciśnij przycisk **Przekształć w bitmapę**. Potem użyj narzędzia **Wypełnij**, aby pomalować tło jednym kolorem.

![obrazek pokazujący wypełnione tło sceny](images/paint-bucket.png)

--- /task ---

--- task ---

Następnie stwórz dwie zmienne, które nazwiesz `Kolor filtra`{:class="block3variables"} i `Intensywność filtra`{:class="block3variables"}. Kliknij prawym przyciskiem myszy na zmienne, które właśnie pojawiły się na scenie i z rozwijanego menu wybierz opcję **suwak**.

![obrazek pokazujący zmienne będące zmieniane w suwaki](images/sliders.png)

--- /task ---

--- task ---

Aby dokończyć swój projekt, użyj tych zmiennych, by wpływać na efekt użytego filtra.

```blocks3
when flag clicked
turn video (on v)
forever
set video transparency to (filter amount)
set [color v] effect to (filter colour)
```

--- /task ---

--- task ---

Teraz możesz przesuwać suwaki i obserwować zmiany na twoim obrazku.

--- /task ---




