## Mehr Kostümsteuerung

Du kannst jetzt auch Steuerungselemente hinzufügen, um die Größe der Figur zu ändern und um zu entscheiden ob das Bild angezeigt oder versteckt wird.

--- task ---

Füge diese Blöcke hinzu, um die Figur erscheinen und verschwinden zu lassen.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Füge nun ein paar weitere Blöcke hinzu, um die Größe des Kostüms zu ändern.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Schau mal, ob du noch weitere Steuerelemente hinzufügen kannst um die Position der Figur zu ändern.

--- hints ---
 --- hint ---

Verwende Tasten deiner Wahl, um die Position deiner Figur zu erhöhen oder zu verringern, indem du die `ändere x um`{:class="block3motion"} und `ändere y um`{:class="block3motion"} Blöcke benutzt

--- /hint --- --- hint ---

Hier sind zwei Blöcke, die die Figur nach links bewegen.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Hier ist der gesamte Code, den du brauchst, aber wähle welche Tasten auch immer du willst, für deine Figur.

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


