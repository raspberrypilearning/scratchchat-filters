## Meer uiterlijk mogelijkheden

Je kunt nu besturingselementen toevoegen om de grootte van de sprite te wijzigen en ook beslissen of de afbeelding wordt weergegeven of verborgen.

--- task ---

Voeg deze blokken toe om de sprite te laten verschijnen en verdwijnen.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Voeg nu meer blokken toe om de grootte van het uiterlijk te veranderen.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Kijk of je nog meer besturingselementen kunt toevoegen om de positie van de sprite te veranderen.

--- hints ---
 --- hint ---

Gebruik diverse toetsen om de sprite zijn positie te veranderen door gebruik te maken van `verander x met`{:class="block3motion"} en `verander y met`{:class="block3motion"} blokken

--- /hint --- --- hint ---

Hier zijn twee blokken die de sprite naar links verplaatsen.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Hier is de code die je nodig hebt, maar kies zelf de toets die je wilt voor je sprite.

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


