# Reading Assignment 9
## HTML AND CSS Chapter 7: "Forms" (pp 144-175)
- HTML uses "form" to refer to different elements that allow you to collect information from visitors to your site.
- Use forms often: Google search, logins, shopping, etc.
- Types of form controls:
  - Adding text: text input (single line), password input, text area
  - Making choices: radio buttons, checkboxes, drop-down boxes
  - Submitting forms: submit buttons, image buttons
  - Uploading files: file upload
- Steps of a form: user fills in, name and value sent to server, server processes input, server creates new page
- Name/value pairs: `username=Ivy`
- Form structure
  - `<form>`, `action=`, and `method`
    - action has URL of page on the server that will recieve form info
    - method can be get or post
      - get adds values to the end of the url specified by action
        - short, just getting info
      - post sends values in http header
        - file uploads, long forms, sensitive data, adds or deletes database info
      - `<input>` type="text", "password", "checkbox", "file", "submit", "image", "hidden"
        - HTML5 - "date", "email", "url", "search"
      - `<textarea>`
      - `<select>` drop-down or select box
        - `<option>` each option
      - `<button>`
      - `<label>`- for visual impairment
      - `<fieldset>` groups related form elements
        - `<legend>` caption for fieldset
      - HTML5 
        - form validation possible in html
          - "required" attribute
        
## HTML AND CSS Chapter 14: "Lists, Tables, and Forms" (pp 330-357)
- CSS properties for specific html elements
- For lists:
  - list-style-type for bullet type or number/alpha type
  - list-style-image to have an image as bullet
  - list-style-position - next line indent
  - list-style - all of above
- For tables:
  - width, padding, text-transform (makes headers uppercase), letter-spacing, font-size, border-top (headers), border-bottom (headers), text-align, background-color, :hover
    - adding padding, distinguishing headings, and shading alternate rows all help greatly with readability
  - empty-cells - can choose not to show borders of cells without content
  - border-spacing - creates or removes margin between cells
- Forms
  - Important to style: should look attractive and easy to use
  - Text input styling:
    - Normal properties for text
    - :focus changes background color of textbox when being used
    - :hover applies styles on mouseover
  - Submit button styling
  - Fieldsets and legends styling
  - CSS can better align form controls
  - cursor
  - 

## JAVASCRIPT AND JQUERY Chapter 6: "Events" (pp 243-292)
- Events are registered by browser, and scripts can respond to them
- Events "fire" or are "raised", and "trigger" scripts
- Different event types:
  - UI events - load, unload, error, resize, scroll
  - Keyboard events - keydown, keyup, keypress
  - Mouse events - click, dbclick, mousedown, mouseup, mousemove, mouseover, mouseout
  - Focus events - focus/focusin, blur/focusout
  - Form events - input, change, submit, reset, cut, copy, paste, select
  - Mutation events - DOMSubtreeModified, DOMNodeInserted, DOMNodeRemoved, DOMNodeInsertedIntoDocument, DOMNodeRemovedFromDocument
- How events trigger javascript code
  1. Select element node
  2. Indicate which event on the selected node will trigger a response
  3. State the code you want to run when the event occurs
- How to bind an event to an element (3 ways)
  - BAD - HTML event handlers
  - Traditional DOM event handlers
    - strong support, but can only run one function on event trigger
    - `element.onevent = functionName;`
  - Dom level 2 event listeners
    - new, can have multiple functions triggered by one event
    - `element.addEventListener('event', functionName, [capture])
        - Events can bubble from most to least specific element, or be captured from least to most specific (newer functionality)
    - Only really matters if the same event is on nested elements
      - capture determines direction to trigger events, false does bubbles, true does capture
    - Can call anonymous functions in event listeners within the parameters
    - Event object


