## Més controls del vestit

Ara pots afegir controls per canviar la mida del personatge i també decidir si la imatge es mostra o s'amaga.

--- task ---

Afegeix aquests blocs per fer que aparegui i desaparegui el personatge.

```blocks3
quan la tecla [m v] es premi
mostra't

quan la tecla [a v] es premi
amaga't
```

--- /task ---

--- task ---

Afegeix ara uns quants blocs més per canviar la mida del vestit.

```blocks3
quan la tecla [fletxa amunt v] es premi
augmenta (10) la mida

quan la tecla [fletxa avall v] es premi
augmenta (-10) la mida
```

--- /task ---

--- task ---

Mira si pots afegir alguns controls més per canviar la posició del personatge.

--- hints --- --- hint ---

Utilitza les tecles que vulguis per augmentar o disminuir la posició del personatge mitjançant els blocs `auma a x`{:class="block3motion"} i `suma a y`{:class="block3motion"}

--- /hint --- --- hint ---

A continuació, es mostren dos blocs que mouen el personatge cap a l'esquerra.

```blocks3
suma (-10) a x
quan la tecla [j v] es premi
```

--- /hint --- --- hint ---

Aquí tens tot el codi que necessites, però tria les tecles que vulguis pel teu personatge.

```blocks3
quan la tecla [j v] es premi
suma (-10) a x

quan la tecla [l v] es premi
suma (10) a x

quan la tecla [o v] es premi
suma (10) a y

quan la tecla [k v] es premi
suma (-10) a y
```

--- /hint --- --- /hints ---



--- /task ---


