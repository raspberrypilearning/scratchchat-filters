## Switching costumes

--- task ---

Now that you have your glasses positioned, you can change their style, by using some simple key presses. Add these code blocks to your sprite.

~~~blocks3
when [right arrow v] key pressed
next costume
~~~

--- /task ---

--- task ---

Try pressing the right arrow key on your keyboard, to see the glasses change style.

![image of a man wearing the heart shaped glasses](images/heart-glasses.png)

--- /task ---

--- task ---

You might also want to get back to a previous costume using the left arrow key. To do this you will need to use the `costume number`{:class="block3looks"} and subtract `1` from it.

~~~blocks3
when [left arrow v] key pressed
switch costume to ((costume [number v]) - (1))
~~~

--- /task ---

--- task ---

Add some more costumes to your sprite, by clicking on the costumes tab and then on the **Choose a Costume** button in the bottom left corner of the screen.

![image showing the Choose a costume button with the menu opened](images/choose-costume.png)

--- /task ---

--- task ---

In the costumes tab you can select all the parts of a costume by holding down the **Ctrl** key on your keyboard and then pressing the **a** key. You can then move and resize each costume so they are in the correct place.

![image of man with alien antenna on his head](images/alien-antenna.png)

--- /task ---

--- task ---

Now you can use the arrow keys to cycle through all your different costumes.

![animated gif of a man with different costumes on](images/costumes.gif)

--- /task ---
