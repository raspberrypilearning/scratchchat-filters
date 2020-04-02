## Adding a colour filter

Now you can give your image a colour filter.

--- task ---

Click on the backdrop icon.

![image showing stage icon](images/stage.png)

Now use the **Backdrops** tab to **Convert to Bitmap** and fill the backdrop with a single colour, using the **Paint bucket tool**.

![image showing the filled in backdrop for the stage](images/paint-bucket.png)

--- /task ---

--- task ---

Now create two variables called `filter colour`{:class="block3variables"} and `filter amount`{:class="block3variables"}. On the stage you can right click on these variables and set them both to be **sliders**.

![image showing the variables being changed to sliders](images/slider.png)

--- /task ---

--- task ---

To finish off the project, you are going to use these variables to alter the look of the filter.

~~~blocks3
when flag clicked
turn video (on v)
forever
set video transparency to (filter amount)
set [color v] effect to (filter colour)
~~~

--- /task ---

--- task ---

Now you can move the sliders to see what effect they have on your image.

--- /task ---




