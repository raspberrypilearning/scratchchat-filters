## Add a colour filter

Now give your image a colour filter.

--- task ---

Click on the **Backdrop** icon.

![image showing stage icon](images/stage.png)

**Convert to Bitmap** करने के लिए **Backdrops** टैब का उपयोग करें | फिर एक रंग के साथ बैकड्रॉप को भरने के लिए **Paint bucket** का उपयोग करें।

![image showing the filled in backdrop for the stage](images/paint-bucket.png)

--- /task ---

--- task ---

इसके बाद `filter colour`{:class="block3variables"} और `filter amount`{:class="block3variables"} नामक दो वेरियबल (variable) बनाएं | मंच पर आप इन वेरियबल पर राइट-क्लिक कर सकते हैं और उन दोनों को **स्लाइडर्स** (sliders) के रूप में सेट कर सकते हैं |

![image showing the variables being changed to sliders](images/sliders.png)

--- /task ---

--- task ---

To finish off your project, use these variables to alter the look of the filter.

```blocks3
when flag clicked
turn video (on v)
forever
set video transparency to (filter amount)
set [color v] effect to (filter colour)
```

--- /task ---

--- task ---

Now you can move the sliders to see the effect on your image.

--- /task ---




