## Añade un filtro de color

Ahora dale a tu imagen un filtro de color.

--- task ---

Haz clic en el icono **Fondo**.

![imagen mostrando el icono del escenario](images/stage.png)

Usa la pestaña **Fondos** para **Convertir a mapa de bits**. Luego usa la herramienta **Cubo de pintura** para llenar el fondo con un solo color.

![imagen que muestra el fondo rellenado para el escenario](images/paint-bucket.png)

--- /task ---

--- task ---

A continuación, crea dos variables llamadas `filtro color`{:class="block3variables"} y `filtro cantidad`{:class="block3variables"}. En el escenario, puedes hacer clic derecho en estas variables y configurarlas para que sean **deslizadores**.

![imagen que muestra las variables que se están cambiando por deslizadores](images/sliders.png)

--- /task ---

--- task ---

Para terminar tu proyecto, utiliza estas variables para alterar el aspecto del filtro.

```blocks3
when flag clicked
turn video (on v)
forever
set video transparency to (filtro cantidad)
set [color v] effect to (filtro color)
```

--- /task ---

--- task ---

Ahora puedes mover los deslizadores para ver el efecto en tu imagen.

--- /task ---




