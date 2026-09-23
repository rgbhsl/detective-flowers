# Detective Flowers
A choice-driven, mystery/psychological thriller text game written in HTML and CSS.

Image here

## Take a look at the rest: 

## Features
- x unique endings 
- x pages
Multiple sections with simple CSS formatting
- Buttons to navigate the story

## How it works

- Entirely made with HTML and CSS, with the written sections being fully original.
- The user uses buttons to navigate the story, automating the process of "flipping a page" in a physical interactive novel. 

- Website layout map: 
```mermaid

graph TD;
    index --> files
    files --> shef1(END1) & gardner1(END3) & housiei & botlleri & welthiei

%%Shef, 1 ending
    shef1(END1) --> index & files

%%Botller, 1 ending
    botlleri --> botllerii & botller1
    botllerii --> botller1(END2) --> index & botlleri

%%Gardner, 1 ending
    gardner1(END3) --> index & files

%%Welthie, 1 ending
    welthiei --> flowersi & welthie1
    welthie1(END4) --> index & welthiei

%%Flowers, 2 endings
    flowersi --> flowers1(END5) & index1(END8.5)
    housiei --> housieii & flowers2(END6)

%%Housie, 2 endings
    housieii --> housieiii & housie1(END7)
    housieiii --> index1(END8.5) & housie2(END8)
    housie1(END7) --> index & files
    housie2(END8) --> index1(END8.5)

%%Index (2 secret endings)
 index1(END8.5) --> truth(END9) & victory(END10)
 
```

## Acknowledgements
- Images taken from free assets on Canva
- W3Schools for help with the navbar (no copy paste)
- Github Documentation, and Mermaid Tutorials for instructions on making a Mermaid diagram
- Inspired by interactive fiction novels, where you flip to a specific page after making a choice

No AI was used to write any part of the story or code. 
