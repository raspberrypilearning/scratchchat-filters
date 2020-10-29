## Daha fazla kostüm kontrolü

Artık spriteınızın boyutlarını değiştirmeyi sağlayacak kontroller ekleyebilir ve resmin görünüp görünmeyeceğine karar verebilirsiniz.

--- task ---

Bu kod bloklarını spriteınızı görünürlüğü değiştirecek kontrolleri tanımlamak için ekleyin.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

Buradaki kod bloklarını ise kostümün boyutlarını değiştirecek kontrolleri tanımlamak için ekleyin.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

Spriteın pozisyonunu değiştirebilecek kontrolleri tanımlayabiliyor olup olmadığınızı kontrol edin.

--- hints --- --- hint ---

Spriteın yerleşimini istediğiniz tuşlar ile değiştirmek için `x konumunu değiştir`{:class="block3motion"} ve `y konumunu değiştir`{:class="block3motion"} kod bloklarını kullanın

--- /hint --- --- hint ---

Spriteın sola kaydırılmasını sağlayan iki kod bloğu görülmektedir.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

İhtiyacınız olan tüm kod buradadır, bir diğer yandan spriteınız için dilediğiniz tuşları seçebilirsiniz.

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


