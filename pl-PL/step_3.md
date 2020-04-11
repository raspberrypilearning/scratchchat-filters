## Jak zmieniać kostiumy

--- task ---

Po ustawieniu okularów, możesz sprawić, że kostiumy duszka będzie można zmieniać naciśnięciami klawiszy. Dodaj poniższe bloki kodu do duszka.

```blocks3
kiedy klawisz [strzałka w prawo v] naciśnięty
następny kostium
```

--- /task ---

--- task ---

Spróbuj nacisnąć klawisz strzałki w prawo na klawiaturze, aby zobaczyć, jak zmienia się wygląd okularów.

![wizerunek mężczyzny w okularach w kształcie serca](images/heart-glasses.png)

--- /task ---

--- task ---

Możesz także wrócić do poprzedniego kostiumu za pomocą klawisza strzałki w lewo. Aby to zrobić, trzeba użyć `kostium liczba`{class="block3looks"} i odjąć `1` od niego.

```blocks3
when [left arrow v] key pressed
switch costume to ((costume [number v]) - (1))
```

--- /task ---

--- task ---

Aby dodać więcej kostiumów do duszka, kliknij kartę **Kostiumy** , a następnie przycisk **Wybierz kostium** w lewym dolnym rogu ekranu.

![obraz przedstawiający przycisk Wybierz kostium z otwartym menu](images/choose-costume.png)

--- /task ---

--- task ---

W karcie **Kostiumy** możesz wybrać wszystkie kostiumy duszka, przytrzymując klawisz Ctrl na klawiaturze, a następnie naciskając klawisz litery A. Następnie możesz zmienić położenie i rozmiar każdego kostiumu, tak aby wszystkie znalazły się we właściwym miejscu.

![obraz człowieka z anteną obcego na głowie](images/alien-antenna.png)

--- /task ---

--- task ---

Teraz możesz użyć klawiszy strzałek, aby przechodzić między różnymi kostiumami.

![animowany gif mężczyzny w różnych strojach](images/costumes.gif)

--- /task ---

