# Reading Assignment 1
## Introduction (pp. 2-11)
- HTML is not as complicated as it looks and is very useful for anyone who works on the web
- Structure of this Book:
  - 1: HTML
    - How HTML is used to create webpages: write words, add tags.
    - Introduces tags for text, lists, links, images, tables, forms, video/audio/flash, etc.
    - The examples we show are foundational to every web page.
  - 2: CSS
    - Explanation how CSS uses rules to control styling and layout.
    - Examination of the wide variety of properties. Generally properties are one of two categories:
      - Presentation: Controlling color of text, fonts, font size, colors, backgrounds.
      - Layout: Controlling positions of elements. Also includes some techniques from professionals.
  - 3: Practical
    - Helpful information for building better websites
    - New tags with HTML5.
    - Putting sites on the web, search engine optimization, and using analytics.
- How People Access the Web
  - Browsers
    - Chrome, Internet Explorer, Firefox, Safari, etc.
    - New versions, but users are not always up to date.
    - More in Ch 19.
  - Web Servers
    - Special computer that hosts a website, constantly connected to the internet.
    - People/companies either host their own servers or use a web hosting company.
  - Devices
    - People are using many different devices for web access.
      - Ex: Desktops, laptops, tablets, mobile phones.
      - Devices have different screen sizes and connection speeds.
  - Screen Readers
    - Programs that read out the contents of a screen to a user.
    - Commonly used for those with visual impairments.
    - Laws exist requiring websites be accessible to those with disabilities.
- How Websites are Created
  - What you see
    - Browser is receiving HTML and CSS from a web server, which it interprets.
    - Images, audio, video, and animations can also be inserted in a page.
    - Some sites also have Javascript and Flash for advanced functionality.
  - How it is created
    - Small websites might use just HTML and CSS
    - Larger websites that update regularly might use a content management system, blogging tools, e-commerce, etc. which require more complex technology, but even those technologies are still producing HTML and CSS.
      - These sites might have a database to store data, or use another language such as PHP, ASP.net, Java, or Ruby on the web server.
        - Do not need to know these to improve what the user sees, and the contents of these books should be enough.
  - HTML5 and CSS3
    - HTML and CSS have had several versions.
    - At time of writing, HTML5 and CSS3 were still being developed.
      - Book includes features from these new versions.
    - Knowing new versions gives you the ability to understand old versions.
- How the Web Works
  - To find a website, your browser connects to DNS server which finds the location of the web server hosting the requested site.
  - Connection happens first to ISP, then to DNS servers which provide the 12-digit IP address, then to web server denoted by the IP, and the web server sends the site to your browser.

## HTML Chapter 1: “Structure” (pp.12-39)
- How Pages Use Structure
  - Different documents have different structures in the real world, and we can do the same thing online.
  - Heading, introduction, subheadings, topics, paragraphs, etc.
- HTML Describes the Structures of Pages
  - Example text shows html version of content from Word document on pg 18.
    - HTML is shown in blue, text black.
      - HTML characters inside brackets are called **elements**, usually made up of two tags that open and close.
        - HTML elements tell the browser something about the content between open and closing tags.
- HTML Uses Elements to Describe the Structure of Pages
  - `<html></html>' Indicates anything within is HTML code.
  - `<body></body>` Indicates anything within should be shown in the main browser window.
  - `<h1></h1>` Indicates main heading(s)
  - `<p></p>` Indicates paragraph text
  - `<h2></h2>` Indicates sub-heading(s)
- A Closer Look at Tags
  - Opening tag: left-angle bracket, character, right-angle bracket
  - Closing tag: same as opening tag, but with forward slash before the character.
- Attributes Tell Us More About Elements
  - Attributes provide more information about the contents of an element, appear after the character in the opening tag, and consist of a **name** and a **value**, separated by an equals sign.
    - Name indicates what extra information you are supplying
    - Value is the information or setting for the attribute. Should be in double quotes.
- Body, Head, and Title
  - <body> Main browser window
  - <head> Information about the page
  - <title> Shown at the top of the browser or tab
- HTML: HyperText Markup Language
- Creating A Web Page On a PC
  1. Start notepad
  2. Type code into notepad file
  3. Save file as all files, with .html extension
  4. Open file in browser
- Creating a Web Page On a Mac
  1. Start textedit
  2. Type code into textedit file
  3. Save file as .html
  4. Open file in browser
- Code in a Content Management System
  - If working with CMS, blog, e-commerce site, etc., you will likely need to log into an admin section of the site.
  - Might have boxes to enter information into templates.
    - Allows people who do not know how to write web pages to add information.
    - Allows templates to be updated simultaneously.
  - Some sites will have a button to see HTML.
  - Some sites will let you edit template files, but be careful when doing so.
- Look at How Other Sites are Built
  - Can see the HTML of web pages by going to ***View*** menu of browser, and selecting ***Source*** or ***View Source***.
    - New window should show the website source code.
    - This is how early web designers learned HTML and discovered new techniques.
    - Might look complicated, but you will be able to understand it by end of next chapter.
  

  
    
