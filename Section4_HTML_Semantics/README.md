# HTML Next Steps and Semantics

- Crucial
  - Understanding HTML 5
  - Block vs Inline Elements
  - Span and Div Elements
  - Semantic Elements
- Nice to Have
  - Emmet
  - sub elements
  - hr elements
  - sup elements
  - br elements

_element examples in [HTML Reference](
https://github.com/Julie-Gibson/WebDevelopment/blob/main/Section3_HTML_Essentials/html_reference.html)_
## HTML 5

refers to lastest evolution of standard that defines HTML
HTML Standard is how broswers implement HTML

## Inline vs Block

Define how elements act on page, in line shares space and block elements take up block.

### div

- generic container
- block element
- content division
- to group content together

### span

- generic container
- inline element
- wraps content to add style with CSS

### hr

- represents a thematic break between paragraph elements
- horizontal rule (fancy line through paragraphs)

### br

- line break
- use case - poem
- used to control where to break line

### sup

- superscript
- used for citations
- can nest a link inside

### sub

- subscript
- can combine with sup to create fraction

## HTML Entities

- used to display reserved characters that are invalid
- start with ampersand and end with semicolon
- also for difficult to type characters
- brower interpreted and rendered to correct character
- common uses include: > < &

## Semantic Markup

semantic - related to meaning
meaningless markup means that there is no meaninf in the document
you can give meaning to pages by using elements that are descriptive

> purpose of using semantic elments to give meaning for web crawlers or google search.
> Adds accessability for screen readers.
> Adds no new features just gives meaning to the markup and used for SEO

### Semantic elements

- section
- - represents a standalone section, typically have headings
- article
- - self contained composition 
- - should have heading 
- nav
- - element for navigational content
- main
- - represents dominant content, should not include repeatable elements like footer, nav bar ...
- header
- - introductory content and navigation area
- footer
- - self explainatory can exist more than once on page 
- aside
- - represents a portion of the document whose content is only indirectly related to main topic
- summary
- time
- - specify attribute

## Emmit
extension to help write html with shortened syntax. 


[emmet cheat sheet](https://docs.emmet.io/cheat-sheet/)
