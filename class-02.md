# Reading Assignment 2
## HTML Chapter 2: "Text" (pp 40-61)
- Structural markup: elements that you can use to describe headings and paragraphs
  -`<h1-6>`, `<p>`, `<b>`, `<i>`, `<sup>`, `<sub>`, white space, `<br />`, `<hr />`
- Visual editors: word processors for code
- Semantic markup: extra information like emphasis, quotations, acronyms, etc
  - `<strong>`, `<em>`, `<blockquote>`, `<q>`, `<abbr>`, `<cite>`, `<dfn>`, `<address>`, `<ins>`, `<del>`, `<s>`
  
## HTML Chapter 10: "Introducing CSS" (pp 226-245)
- CSS can be understood to treat html content as though it's in a box and uses rules to indicate how that element should look.
- Rules are made up of selectors that specify the element(s) and declarations that indicate what the elements should look like.
- Declarations are made up of two parts: property to change and value of that property.
- CSS rules should be on an external stylesheet, but can also be internal rules in an html document
  - Use `<link>` in the head to connect an external stylesheet to the html
  - Use `<style>` in the head to contain internal CSS rules
- Selectors target rules to specific elements
  - Universal, type, class, id, child, descendant, adjacent sibling, general sibling selectors.
- When there are two or more conflicting rules, the last, more specific, or specially marked rule will take precedence.
- Some CSS properties are inherited by child elements.
  - Ex: font-family
  - Can be forced
  
## JAVASCRIPT AND JQUERY Chapter 2: "Basic Javascript Instructions" (pp 53-84)
- Statements should end with semicolons
- Comments with // and /* */
- Variables store data, can change
  - Ex var quantity = 10;
- Data types in Javascript:
  - Numeric
  - String
    - Can use \ to escape
  - Boolean
  - Don't need to specify on creation
- Rules for naming variables:
  - Can start with letter, $, or underscore
    - No numbers
  - Can contain letters, numbers, $, or underscore
    - No dashes or periods
  - Cannot be keywords or reserved words
  - Case-sensitive
  - Describe variable information
  - Camel case
- Arrays
  - List of values
  - Prefer to use array literals []
    - Also can use array constuctors ()
  - Index 2: array[2]
    - start at 0
  - array.length
- Can assign values to indices
  - Ex array[2] = 200
- Expressions result in a single value
  - Use operators
    - Assignment: =
    - Arithmetic: 2 * 3
      - `+, -, /, *, ++ (increment), -- (decrement), % (modulus)`
    - String: 'hello' + ' wprld'
      - Concatenation
      
## JAVASCRIPT AND JQUERY Chapter 4: "Decisions and Loops" (pp 145-162)
- We make decisions based on conditions
  - Conditions can be true or false
  - We can compare values with comparison operators
    - `>, <, >=, <=, == (is equal to), === (strict equal to (same type)), != (not equal to), !== (strict not equal to)`
    - Expressions can also be compared
  - Logical operators allow us to compare the result of more than one comparison operator
    - `&& (logical and), || (logical or), ! (logical not)`
    - logical operators will short-circuit if possible
  - If statements execute code within them when the condition is true
    - Can include else to run code if false
    - Cam include else if to run code if another condition is true
 
