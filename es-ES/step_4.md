## Más controles para los disfraces

Ahora puedes añadir controles para cambiar el tamaño del objeto y también decidir si la imagen se muestra u oculta.

--- task ---

Añade estos bloques para hacer que el objeto aparezca y desaparezca.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Ahora añade algunos bloques más para cambiar el tamaño del disfraz.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Prueba a añadir más controles para cambiar la posición del objeto.

--- hints ---
 --- hint ---

Usa las teclas que quieras para aumentar o disminuir la posición del objeto usando los bloques `sumar a x`{:class="block3motion"} y `sumar a y`{:class="block3motion"}

--- /hint --- --- hint ---

Aquí tienes dos bloques que mueven el objeto hacia la izquierda.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

Aquí está todo el código que necesitas, pero elige las teclas que quieras para tu objeto.

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


