## Cómo cambiar disfraces

--- task ---

Ahora que tienes las gafas colocadas, puedes cambiar su estilo simplemente pulsando unas teclas. Añade estos bloques de código a tu objeto.

```blocks3
when [flecha derecha v] key pressed
next costume
```

--- /task ---

--- task ---

Prueba a presionar la tecla de dirección derecha (flecha a la derecha) en tu teclado para ver cómo las gafas cambian de estilo.

![imagen de un hombre que lleva las gafas en forma de corazón](images/heart-glasses.png)

--- /task ---

--- task ---

También puede que quieras volver a un disfraz anterior usando la tecla de dirección izquierda. Para hacerlo, debes usar el `número de disfraz`{:class="block3looks"} y restarle `1`.

```blocks3
when [left arrow v] key pressed
switch costume to ((costume [number v]) - (1))
```

--- /task ---

--- task ---

Para añadir más disfraces a tu objeto, haz clic en la pestaña **Disfraces** y luego en el botón **Elige un Disfraz** en la esquina inferior izquierda de la pantalla.

![imagen mostrando el botón Elegir un disfraz con el menú abierto](images/choose-costume.png)

--- /task ---

--- task ---

En la pestaña **Disfraces**, puedes seleccionar todas las partes de un disfraz manteniendo presionada la tecla Ctrl de tu teclado y luego presionando la tecla con la letra A. Después podás mover y cambiar el tamaño de cada disfraz para que esté en el lugar correcto.

![imagen de un hombre con antena alienígena en la cabeza](images/alien-antenna.png)

--- /task ---

--- task ---

Ahora puedes usar las teclas de dirección para recorrer todos tus distintos disfraces.

![gif animado de un hombre con diferentes disfraces](images/costumes.gif)

--- /task ---

