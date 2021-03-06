# Reading Assignment 3
## HTML AND CSS Chapter 3: "Lists" (pp 62-73)
- Ordered Lists
  - Numbered
  - `<ol>` with `<li>` (list items)
- Unordered Lists
  - Not numbered
  - `<ul>` with `<li>` (list items)
- Definition Lists
  - `<dl>`
  - `<dt> (definition terms), <dd> (definition of the term)`
  - One term could have multiple definitions
- Nested Lists
  - `<li> inside of another <li>`
  - Child lists indented further than parent, usually with different bullet point style
 
## HTML AND CSS Chapter 13: "Boxes" (pp 300-329)
- Can use CSS to create the appearance of boxes around elements, with sizes, borders, margins, padding, etc
  - Box dimensions - width and height
    - Defaults to large enough to hold element
  - min-width, max-width, min-height, max-height
    - Ensures legibility, esp for small screens
  - overflow - controls what happens if content is too large for box
    - hidden - hides extra content
    - scroll - automatically adds scrollwheel
  - Border
    - Box line thickness
    - border-width controls thickness, can be pixels or "thin", "medium", "thick".
      - widths of each side can be controlled individually
  - Margin
    - Space to clear outside box
  - Padding
    - Space between content and inside of box
  - Border, margin, padding all good for white space
  - display can change elements between block and inline or hide them as though they don't exist
  - visibility can hide elements but leaves a space where they would have been
  - border-image applies an image to the border of any box, either stretched or repeating (new CSS3)
  - box-shadow adds a shadow (new CSS3)
  - border-radius rounds corners or creates eliptical shapes (new CSS3)
  
## JAVASCRIPT AND JQUERY Chapter 4: "Decisions and Loops" (pp 164-182)
- Switch statements
  - Starts with switch value variable
  - Checks switch values against cases, and runs code for matching case or default if no case matches
  - Breaks once match is found, unlike if statements. Faster.
- Javascript has weak typing, so variables can be coerced to change type
  - This leads to odd results, like Truthy and Falsy values
    - Falsy values are treated as if they are false
      - 0, '', 10/'score', var (no assignment) - all these evaluate to false
        - All other values will evaluate to true
    - An object's presence can be used to check for the existence of an element, because existance evaluates to truthy
      - Unary operator
    - Short-circuit values may emerge because a logical operator produced a truthy or falsy result but returned a non-boolean value
  - Should use === to avoid all this
- Loops
  - For
    - Runs code a specific number of times
    - Condition counter includes initialization, condition, and update
  - While
    - Runs code until the condition is true
  - Do while
    - Runs code once, and then until the condition is true
  - Loops are good for dealing with arrays
  - Loops dealing with a large number of items will cause pages to load slowly
  - Infinite loops will cause browser to run out of memory
  - Should define variables outside the loop whenever possible, to not waste resources recalculating unnecessarily
