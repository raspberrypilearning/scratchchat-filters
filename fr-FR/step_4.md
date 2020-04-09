## Plus de contrôles de costumes

Tu peux maintenant ajouter des contrôles pour changer la taille du sprite et aussi décider si l'image est affichée ou masquée.

--- task ---

Ajoute ces blocs pour faire apparaître et disparaître le sprite.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Ajoute maintenant plus de blocs pour changer la taille du costume.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Vois si tu peux ajouter plus de contrôles pour changer la position du sprite.

--- hints ---
 --- hint ---

Utilise les touches de ton choix pour augmenter ou diminuer la position du sprite en utilisant les blocs `ajouter à x`{:class="block3motion"} et `ajouter à y`{:class="block3motion"}

--- /hint --- --- hint ---

Voici deux blocs qui déplacent le sprite vers la gauche.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Voici tout le code dont tu as besoin, mais choisis toutes les touches que tu veux pour ton sprite.

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


