## Farbfilter hinzufügen

Gib deinem Bild nun einen Farbfilter.

--- task ---

Klicke auf das **Bühnenbild**-Symbol.

![Bild das das Bühnensymbol zeigt](images/stage.png)

Benutze die **Bühnenbilder**-Registerkarte um **in eine Vektorgrafik umzuwandeln**. Nutze dann das **Fülleimer** Werkzeug, um den Bühnenhintergrund mit einer einzigen Farbe zu füllen.

![Bild das den gefüllten Bühnenhintergrund für die Bühne zeigt](images/paint-bucket.png)

--- /task ---

--- task ---

Erstelle als nächstes zwei Variablen namens `Filterfarbe`{:class="block3variables"} und `Filterstärke`{:class="block3variables"}. Du kannst auf der Bühne, mit der rechten Maustaste auf diese Variablen klicken um sie beide **Schieberegler** sein zu lassen.

![Bild das zeigt wie die Variablen zu Schiebereglern geändert werden](images/sliders.png)

--- /task ---

--- task ---

Nutze diese Variablen um das Aussehen des Filters zu verändern, um dein Projekt fertigzustellen.

```blocks3
when flag clicked
turn video (on v)
forever
set video transparency to (Filterstärke)
set [color v] effect to (Filterfarbe)
```

--- /task ---

--- task ---

Du kannst jetzt die Schieberegler bewegen um den Effekt auf deinem Bild zu sehen.

--- /task ---




