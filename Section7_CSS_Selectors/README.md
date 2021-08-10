# The World CSS Selectors

- curcial
  - Element selector
  - class selector
  - ID selector
  - Descendent selects
  - CSS Specificity
- important
  - adjacent selectors
  - direct descendent selectors
  - attribute selectors
  - pseudo selectors
  - pseudo elements

## Selectors

```CSS
    selector {
        porpery: value;
    }
```

- universal selector **\***

  - selects everything on page

    ```CSS
      * {
        color: black;
      }
    ```

- element selector

  - selects specified element

    ```CSS
      img {
        width: 100px;
      }
    ```

- list seperated by comma

  - both elements selected h1 and h2
    ```CSS
      h1, h2 {
        color: magenta;
      }
    ```

- id selector

  - selects based on id name
  - use **\#** before id name

    ```CSS
      #id_name {
        color: orange;
      }
    ```

- class selector

  - selects based on class
  - use the **.** sympbol
  - groups together content

    ```CSS
    .class_name {
      color: red;
    }
    ```

- descendant selector

  - for example all anchor tags inside an li tag would look like the folllowing:

    ```CSS
    li a {
      color: red;
    }
    ```

- adjacent selector

  - technically called _compensators_
  - selector is a combinator that alters selectors
  - plus sign is adjacent combinator
  - element1 **+** element2
  - selects only the element2s that are immediately preceded by element1
  - not children or parent of each other, just next to one another

  ```CSS
  h1 + p {
    color: red;
  }
  ```

  > **Note:** select p that are directly preceded by h1

- direct child / direct child combinator

  - uses greater than sign **>**
  - direct child only

  ```CSS
  div > li {
    color: white;
  }
  ```

  > **Note:** select only li's that are direct children of divs

- attribute selector

  - select all input elements where the type attribute is set

  ```CSS
    input[type="text"] {
      color: red;
    }
  ```

  > **Note:** sets all input elements with attribute set to text as red

- psuedo classes

  - keyword added to a selector that specifies a special state of the selected elements
  - examples
    - :active, :checked, :first, :first-child, :hover, :not(), :nth-child(), :nth-of-type()
  - start with colon :
  - most common use case is hover
  - for nth of type to continue pattern add **n** ie. 2n for every other

  ```CSS
  button:hover {
    color: white;
  }
  ```

  > **Note:** changes button color on hover

- psuedo elements

  - Keyword added to a selector that lets you style a particular part of selected element(s)
  - examples
    - ::after, ::before, ::first-letter, etc.
  - different from psuedo classes in that they are selecting part of an element only

  ```CSS
  h2::first-letter{
    color:red;
  }
  ```

  > **Note:** selects first letter of every h2 and makes it red
  > <br>

## The Cascade

- The order your styles are declared in and linked matters
- think of cascade

  - when conflicting, style at the bottom overwrites style above

  ```CSS
  h1 {
    color:red;
  }
  h1 {
    color:purple
  }
  ```

  > **Note:** Purple wins

### Specificity

- how browser decides which rules to apply when multiple rules could apply to same element
- measure of how specific a given selector is
- more specific wins
- inline styles are **MOST SPECIFIC**
- !important - can override specificty

> **Formula**
> ID > CLASS > ELEMENT

### inheritance

- elements nested in elements inherit from parent element
- some elements do not inherit
  - for inheritance with **inherit** keyword
  - some properties are not inheritable
    - border is not inherited

# References

[Color Palettes](https://coolors.co/palettes/trending) <br>
[Specificity Calculator](https://specificity.keegan.st/) <br>
