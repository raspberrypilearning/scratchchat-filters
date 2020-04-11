## Mai multe controale pentru costumuri

Acum poți adăuga controale pentru a schimba dimensiunea personajului și de asemenea decide dacă imaginea este afișată sau ascunsă.

--- task ---

Adaugă aceste blocuri pentru a face personajul să apară și să dispară.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Acum adaugă mai multe blocuri pentru a schimba dimensiunea costumului.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Vezi dacă poți adăuga mai multe controale pentru a schimba poziția personajului.

--- hints --- --- hint ---

Folosește orice taste vrei ca să mărești sau să micșorezi poziția personajului folosind blocurile `modifică x cu`{:class="block3motion"} și `modifică y cu`{:class="block3motion"}

--- /hint --- --- hint ---

Aici sunt două blocuri care mută personajul la stânga.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Iată tot codul de care ai nevoie, dar alege orice taste vrei pentru personaj.

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


