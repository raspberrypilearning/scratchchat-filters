## More costume controls

You can now add controls to change the size of the sprite and also decide if the image is shown or hidden.

--- task ---

Add these blocks to make the sprite appear and disappear.

~~~blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
~~~

--- /task ---

--- task ---

Now add some more blocks to change the size of the costume.

~~~blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
~~~

--- /task ---

--- task ---

See if you can add some more controls to allow you to position the sprite, by changing its position on the screen.

--- hints --- --- hint ---

Use any keys you like to increase or decrease by using the `change x by`{:class="block3motion"} and `change y by`{:class="block3motion"} blocks

--- /hint --- --- hint ---

Here are two blocks that you would use to move the sprite left.

~~~blocks3
change x by (-10)
when [j v] key pressed
~~~

--- /hint --- --- hint ---

Here is all the code you need, but you can choose any keys you want.

~~~blocks3
when [j v] key pressed
change x by (-10)

when [l v] key pressed
change x by (10)

when [o v] key pressed
change y by (10)

when [k v] key pressed
change y by (-10)
~~~

--- /hint --- --- /hints ---



--- /task ---


