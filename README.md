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
    files --> shef1(END1) & gardner1(END3) & housiei & botlleri

%%Shef, 1 ending
    shef1(END1) --> index & files

%%Botller, 1 ending 
    botlleri --> botllerii & botller1 
    botllerii --> botller1(END2) --> index & botlleri

%%Gardner, 1 ending
    gardner1(END3) --> index & files

%%Flowers, 1 ending
    flowersi --> flowers1(END4) & housiei

%%Housie, 2 endings
    housiei --> housieii & housie1(END5)
    housieii --> housie2(END6) & index1(END6.5)
    housie1(END5) --> index & files
    housie2(END6) --> index1(END6.5)

%%Index (2.5 endings)
 index1(END6.5) --> truth(END7) & victory(END8)
 
```

## Acknowledgements
- Images taken from free assets on Canva
- W3Schools for help with the navbar (no copy paste)
- Github Documentation, and Mermaid Tutorials for instructions on making a Mermaid diagram
- Inspired by interactive fiction novels, where you flip to a specific page after making a choice

No AI was used to write any part of the story or code. 
