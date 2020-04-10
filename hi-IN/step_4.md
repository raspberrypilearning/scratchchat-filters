## अधिक पोशाक नियंत्रण

आप अब स्प्राइट के आकार को बदलने के लिए नियंत्रण जोड़ सकते हैं और आप यह भी तय कर सकते हैं कि छवि दिखाई जाए या छिपाई जाए।

--- task ---

स्प्राइट दिखाई देने और गायब होने के लिए इन ब्लॉकों को जोड़ें।

```blocks3
when [s v] key pressed
show

when [h v] key pressed
hide
```

--- /task ---

--- task ---

अब कोस्टयूम के आकार को बदलने के लिए कुछ और ब्लॉक जोड़ें।

```blocks3
when [up arrow v] key pressed
change size by (10)

when [down arrow v] key pressed
change size by (-10)
```

--- /task ---

--- task ---

देखें कि क्या आप स्प्राइट की स्थिति को बदलने के लिए कुछ और नियंत्रण जोड़ सकते हैं।

--- hints --- --- hint ---

अपनी पसंद की किसी भी कुंजी का उपयोग करके स्प्राइट की स्थिति को बढ़ाने या घटाने के लिए `change x by`{:class="block3motion"} और `change y by`{:class="block3motion"} ब्लॉक का उपयोग करें

--- /hint --- --- hint ---

यहां दो ब्लॉक हैं जो स्प्राइट को बाईं ओर ले जाते हैं।

```blocks3
change x by (-10)
when [j v] key pressed
```

--- /hint --- --- hint ---

यहां आपके लिए आवश्यक सभी कोड हैं लेकिन आप अपने स्प्राइट के लिए अपनी पसंद की कोई भी कुंजी चुन सकते हैं।

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


