# HTML Tables & Forms

- Crucial
  - Table basic
  - Form element basic
  - Button elements
  - labels
  - common input types
- Important
  - table sections
  - Range & Text Area
  - form validation
- Nice to Have
  - table colspan and rowspan

_Forms, tables, and input element examples in [HTML Reference](https://github.com/Julie-Gibson/WebDevelopment/blob/main/Section4_HTML_Semantics/Formula1_Drivers.html)_


## Tables

display tabular data

### Elements

- Table
- td
  - table cell
- tr
  - table row
- th
  - table header
- logical breakup of table sections _semantic elements_
  - thead
  - tbody
  - tfoot
    - can be used for things like aggragate totals at the end of a table
- colgroup
- caption

### Attributes

- colspan
  - space columns across ir colspan=2
- rowspan
  - space of row hieght ie. rowpan=2

## Forms

A container that contains collection of inputs, checkboxes, buttons, etc...

> Grouping inputs for specifing where to send data

- When you send a form the ACTION attribute specifies WHERE the form data should be sent
- The METHOD attribute specifies which HTTP method should be used


### Form Elements

#### **Input Element**

Example:

```html
<input id="textInput" class="custon" size="32" />
```
> _NOTE: Input tag as no closing tag_

- versatile
- 20 different types of input elements
- attributes
  - **type** 
    - type defines input behavior
  - **placeholder** 
    - useful for some input types like _text_, _number_, _password_
    - not very accessable 
  - **label**
    - assign link via text to input 
    - helps accessability
    - adds link to input for easier clicking 
    - input should have id = identifer on input and use it in text for label
      - id should be unique 

[MDN input types reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)


#### **Button Element**
- default behavior in form is for it submit the form 
- attributes
  - type 
    - button - changes defualt behavior: does not submit form 


#### **name attribute**
- when form is submitted value is given the name with this attribute
  - For example: 
    - text input
      - username: fakename
      - query is: file:///formsubmitted?username=fakename
- name should be added to all inputs 

#### **More input elements**
- Check boxes
- Radio buttons
  - can only select one in a group 
- Select element
  - drop down menu 
- Range 
  - can choose step and min max values 


#### **Text Area**
- not an input element
- text area 

## Validation
- Client side validation
  - browser validation 
  - Javascript validation

- Server side validation

### Built in validation 
- attributes 
  - required
    - value is required to submit form  
  - pattern
    - regex
  - can use specific types 
    - url, email, telephone 

    

