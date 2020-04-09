## Più comandi sui costumi

Ora puoi aggiungere comandi per cambiare la dimensione dello sprite e anche decidere se l'immagine viene mostrata o nascosta.

--- task ---

Aggiungi questi blocchi per far apparire e scomparire lo sprite.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Ora aggiungi altri blocchi per cambiare la dimensione del costume.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Prova se riesci ad aggiungere altri controlli per cambiare la posizione dello sprite.

--- hints --- --- hint ---

Usa i tasti che preferisci per aumentare o diminuire la posizione dello sprite usando i blocchi `cambia x di`{:class="block3motion"} e `cambia y di`{:class="block3motion"}

--- /hint --- --- hint ---

Ecco due blocchi che spostano lo sprite a sinistra.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Ecco tutto il codice che ti serve, ma scegli i tasti che preferisci per muovere il tuo sprite.

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


