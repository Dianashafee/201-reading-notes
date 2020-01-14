# Reading Assignment 7
## Article: Domain Modeling
- Domain Modeling: the process of creating a conceptual model in code for a specific problem.
  - A model describes the various entities, their attributes, their behaviors, as well as constraints.
  - An entity that stores data in properties and behaviors in methods is called an object-oriented model.
- Ex: Epic Fails Videos
  - epicRating 1 to 10
  - hasAnimals true or false
  - Constructor Function:
    - `var EpicFailVideo = function(epicRating, hasAnimals) {`
      `this.epicRating = epicRating;`
      `this.hasAnimals = hasAnimals;`
      `}`
    - `var parkourFail = new EpicFailVideo(7, false);`
    - `var corgiFail = new EpicFailVideo(4, true);`
    - Function expression, instantiates the new objects parkourFail and corgiFail, whose properties are initialized by the contstructor function
    - Object-oriented programming
      - The `new` keyword creates an object
      - The constructor function initializes properties inside that object using `this.<property>`
      - The object is stored in a variable for later use
    - Prototype
      - `EpicFailVideo.prototype.generateRandom = function(min, max) {`
        - Prototype is sort of like a function that can be shared between objects
          - Sort of like classes in other languages
          - allows sharing of code, uses less memory
- Summary
  - Tips:
    - When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
    - Model its attributes with a constructor function that defines and initializes properties
    - Model its behaviors with small methods
    - Create instances using the `new` keyword followed by a call to a constructor function
    - Store the newly created object in a variable so you can access its properties and methods from outside
    - Use the `this` variable within methods to access the object's properties and methods from inside

## HTML AND CSS Chapter 6: "Tables" (pp 126-145)
- What's a Table?
  - Information in a grid format
- Basic table structure:
  - `<table>, <tr> (table row), <td> (table data), <th> (table headings)
  - Span rows with `<td colspan="3">` and columns with `<td rowspan="3">`
  - Tables can also have `<thead>, <tbody>, and <tfoot>`

## JAVASCRIPT AND JQUERY Chapter 3: "Functions, Methods, and Objects" (pp 106 144)
- Constructor Notation
  - `var hotel = new Object();`
  - can assign properties with key-value and dot notation once object is created
  - Values can also be updated with dot notation `object.property = newValue;`
  - Properties can be deleted with `delete object.property`
    - or can be cleared by setting value to empty string
  - Using object constructors allows you to make a generic object that you can then make versions of with different properties
  - Use `this` to allow an object to refer to itself
- Built-in Objects
  - Window object - current browser tab or window
  - Document object - webpage loaded into current browser or tab
  - String object
  - Number object
  - Math object
  - Date pbject
 
    
      
      
