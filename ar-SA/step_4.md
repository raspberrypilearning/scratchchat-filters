## المزيد من عناصر التحكم في المظاهر

يمكنك الآن إضافة عناصر تحكم لتغيير حجم الرموز المتحركة وتحديد ما إذا كانت الصورة معروضة أو مخفية.

--- task ---

أضف هذه اللبنات (المقطع البرمجي) لجعل المظاهر تظهر وتختفي.

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

أضف الآن المزيد من اللبنات (الكود البرمجي) لتغيير حجم الزي.

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

تحقق مما إذا كان يمكنك إضافة المزيد من عناصر التحكم لتغيير موقع المظاهر.

--- hints ---
 --- hint ---

`غيّر y حسب`{:class="block3motion"}و {:class="block3motion"}`تغيير x بواسطة` استخدم أي مفاتيح ترغب في زيادة أو تقليل موقع المظاهر (الكائن) باستخدام 

--- /hint --- --- hint ---

إليك لبنتان (الكود البرمجي) تحريك المظاهر (الكائن) إلى اليسار.

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

إليك جميع التعليمات البرمجية التي تحتاجها ، ولكن اختر أي مفاتيح تريدها للمظهر (الكائن) الخاص بك.

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


