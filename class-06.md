# Reading Assignment 6
## Article: Understanding the Problem Domain is the Hardest Part of Programming
- Ex: Protein Tracker
  - Easy to understand, which allowed focus on technology, not problem domain
  - Teaching new technology was much easier with a familiar problem domain
- Why Problem Domains are Hard
  - Ex: Dalmation jigsaw puzzle
    - Difficult because you can't see what you are trying to build very clearly
    - Normal process: figure out major components, sort the pieces by color or component, put together all border pieces, put together each component
    - Writing code is like a jigsaw puzzle
  - The real world is messy, and many problem domains are hard to understand and look different from different viewpoints
  - Programmers are also often not given complete information about the problem domain
  - Domain Driven Design book - good
- Programming is easy if you understand the problem domain
  - waterfall vs agile development
    - waterfall experience: gave clear problem domain, which allowed easy writing of code
  - Very difficult to solve the problem before knowing the question
- What can you do about it?
  - Make the problem domain easier
    - Cut out cases and narrow focus to a part of the problem
      - Games are good at this
  - Get better at understanding the problem domain
    - It is easy to fall into the trap of thinking you understand enough of the problem to start coding it
    - Developers tend to think sitting down and talking to business people and customers is a waste of time
- Marketing and branding is important

## JAVASCRIPT AND JQUERY Chapter 3: "Object Literals" (pp 100-105)
- What is an object?
  - Group of variables and functions together to create a model of something
  - Inside an object:
    - Variables become properties
    - Functions become methods
    - Keys: names of properties and methods
      - No two keys with the same name
    - Value still called value
    - HTML and CSS both use these:
      - HTML: attribute - value
      - CSS: property - value
    - Javascript:
      - variables have name - value
      - arrays have name - group of values (each item is name - value)
      - named functions have name and value (value is set of statements to run if function called)
      - Objects consist of name - value pairs, but called key - value pairs
    - Creating an Object: literal notation
      - `var <objectname> {<list of keys and values>}`
        - keys and values can include variable and function declarations
    - Accessing objects
      - Ex property: `var hotelName = hotel.name;`
      - Ex function: `var roomsFree = hotel.checkAvailabilty();`
    
## JAVASCRIPT AND JQUERY Chapter 5: "Document Object Model" (pp 183-242)
- Document Object Model: specifies how browsers should create a model of an html document and how javascript can access and update content in a browser
  - DOM tree specifies the way a browser structures this model.
    - Is an object model
  - API: Application Programming Interface - lets programs and scripts talk to each other
    - DOM tree is an API
  - DOM tree - model of a webpage
    - Starts with document node
    - branches to element nodes
      - branch to attribute and text nodes
  - Working with the DOM tree
    - Step 1: access elements
      - `getElementById();` - single element
      - `querySelector();` - CSS selector, returns first match
      - `getElementsByClassName();` - multiple elements by class
      - `getElementsByTagName();` - selects all elements by tag
      - `querySelectorAll();` - selects all elements matching CSS
      - `parentNode` - selects parent
      - `previousSibling/nextSibling`
      - `firstChild/lastChild`
      - `nodeValue` - accesses contents of a text node
      - `innerHTML` - accesses child elements and text content
      - `textContent` - text only
      - `createElement()`
      - `createTextNode()`
      - `appendChild()/removeChild()`
      - `hasAttribute()`
      - `getAttribute()`
      - `setAttribute()`
      - `removeAttribute()`
    - Caching DOM queries
      - Ex: `var itemOne = getElementById('one');
    - Can loop through a NodeList
    - Browsers except IE treat whitespace as text elements
    - Updating HTML content - different methods:
      - `document.write` - easy, but only works on page load, can accidentally overwrite entire page, generally frowned upon
      - `<element>.innerHTML` - (string) can add markup, can be faster than DOM manipulation, allows simple removal of content, should not add content that comes from user (security risk)
      - DOM manipulation - suited to changing one element with many siblings, does not affect events, allows scripts to add elements incrementally, slower than innerHTML, requires code
  - Cross-site scripting attacks
    - XSS
    - To defend: validate input going to server, escape data coming from server
    - Use templates
      
      




