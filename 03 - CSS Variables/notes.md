

Cool nuggets of knowledge

- HTML5
  1. Input type options
    a. Type options include
      - text
      - password
      - submit
      - reset
      - radio
      - checkbox
      - button
    b. New options include      
    - color
    - date
    - datetime-local
    - email
    - month
    - number
    - range
    - search
    - tel
    - time
    - url
    - week
- CSS
  1. Declaration
    A. Root
      - :root {
        --name_of_variable: value;
        }
      - example
        :root {
          --base: #66c600;
          --spacing: 10px;
          --blur: 10px;
        }

  2. Usage
    A. example
      - img {
        padding: var(--spacing);
      }

- JS
  1. Nodelist vs Array
      A. Array has many more methods than Nodelist
      B. You are able to see this in console with querySelectorAll
        - __proto__
        - shows the available methods and properties
  2. addEventListener
      A. create a function
      B. add console.log
      C. this.value
        - when it's called on an object, it will tell you the value
      D. random
  3. const
      a. const creates something JS can manipulate in CSS and/or HTML
      b. example
        - const inputs =  document.querySelectorAll('.controls input');
        1. goes to document
        2. creates a querySelector on multiple div(s) with class CSS .controls and HTML5 attribute input
  4. Data attributes
      a. can be used by
  5. Dataset
      a. is an object that contains all the data from a specific element that has data attributes
      example
        - <div class="main_window" data-size='10' data-monkey='marshmellow' data-chicken='buffalo'>
        </div>
        1. data-** allows for all of these to be called in javascript
          - console.log(this.dataset)
          produces
          DOMStringMap { sizing: "px", monkey: "marshmellow" }
        2. to obtain the specific data attribute
          - const suffix = this.dataset.sizing
          produces
