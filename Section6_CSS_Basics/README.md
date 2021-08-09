# CSS 

- Curcial
    - concepts of CSS
    - Basic CSS syntax
    - including styles
    - color systems    
        - RGB, HEX, etc.
    - font-family property

- Important 
    - common text property 

## CSS Concept
The 
Purple  - CSS   - adjective
Dino    - HTML  - nouns
Danced  - JS    - verbs

### What is it?
> Describes how documents are laid out visually 

### WHat does it stand for?
> Cascading Style Sheets

## CSS rules
(almost) Everything you do in CSS follows this basic pattern 

Simple Example: 
``` CSS
    selector {
        property: value;
    }
```
> __NOTE__: to many to memorize these are links for reference on CSS 
  [CSS Reference MDN](https://developer.mozilla.org/en-US/docs/Web/CSS)
  [CSS properties MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Properties_Reference)
 
## Implemeting CSS 
1. inline 
2. head
3. style sheet **Prefered Method**
    - link sheet with link element 
    ``` HTML 
        <link rel="sytlesheet" href="app.css"> 
    ```

## CSS properties

- color
    - select text color 
- background-color
    - select background color
- background
    - less specific than background color 

## CSS colors
- named colors
    - limited set
    - modern browsers have **140** known named colors
- RGB
    - ranges from 0 - 255
        - red       - rgb(255,0,0)
        - blue      - rgb(0,255,0)
        - green     - rgb(0,0,255)
        - black     - rgb(0,0,0)
- Hex
    - 0 - 255 but in hexadecimal 
    - hex:#ff (red) ff(green) 00(blue)
    - red green blue 

## Text Properties
- text-align
    - operates within the confines of the content ie. block 
- font-weigh
    - bold or unbold something
- text-decoration
    - appreance of decortive lines around text
- line-height
    - line spacing 
    - number ie. to make double spaced 2
    - number is multiplier
    - increases size of line not text
- letter-spacing
    - space between letter

## Font Propeties
### Font Sizes
- absolute
    - pixels
        - not always same size depending on machine
        - common
    - others
        - mm, cm, 
- relative

### Font
- font-family
    - choose a stack of fonts - highest to least priority 
 



# References
[Color Picker](https://htmlcolorcodes.com/color-picker/) <br>
[Color Names](https://htmlcolorcodes.com/color-names/) <br>
[Font Stacl](https://www.cssfontstack.com/) <br>
 



