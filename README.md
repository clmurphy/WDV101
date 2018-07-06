# WDV101
Course Outline New
WDV101 Course Outline-PROPOSED


Terms and concepts

W3C – Internet Standard setting body
Deprecated elements
Browser Compatibility
Block Elements vs Inline Elements
Elements vs Tags (definition vs slang)
Render – browsers takes in the HTML and CSS then ‘renders’ it into the Document Object
Root Element, element heirarchy
CSS Frameworks
Responsive Design


Section 1: Introduction to HTML 

Objectives:
Define the role of HTML within the Internet
Discuss the progression of HTML to the current standard


Hypertext Markup Language
Explore the history of the Internet and World Wide Web.
Cornerstone technology of ALL websites on the Internet
Uses code but it is not a programming language. No loops, if statements, arrays, etc.
Defines the structure and content of a webpage.
Current Standard HTML5
Previous Standards 
HTML-HTML4 – Still work but not recommended
XHTML 1.0  Most recent standard and still in wide use.
Defined the following syntax rules for HTML. 
Now part of the HTML 5 standard
All elements and attributes in lowercase
All elements must closed
All elements must be properly nested
All attribute values must be quoted
Deprecated most HTML element related to presentation control in favor of CSS




Section: HTML Syntax

Objectives:
Identify HTML elements and attributes and discuss their purpose.
Compare block elements to inline elements and how they work
Build a well structured basic web page

Content
Define HTML elements (tags)
Element Format < element > …content goes here…</element>
Referred to as the ‘start’ or ‘open’ and ‘close’ element
Often referred to as a container because it holds content
A few elements do NOT have a close element.
Define HTML attributes
Attributes provide additional information or functionality of an element
Placed inside the ‘start’ element
<element attribute=’value’>…</element>
Sometimes referred to as a ‘name-value pair’. Attribute name = value to be used by the attribute.
Examples: <a href=”pagetwo.html”>Next Page</a>
Block Elements
Always start on a new line, some leave a blank line then start (p, h1-h6, )
Takes up the full available width
Controls the space around and within them
Usually contains content and inline elements
Examples: <h1>-<h6>, <p>, <ol>, <li>, <div>, <header>, <section>,…
Inline Elements
Does not start a new line, will stack left to right if available space
Only uses as much width as necessary
Used to identify parts of the content or pieces of content within a block container
Usually contained within a block element to control layout
Examples: <a>, <span>, <em>, <strong>, <em>, <img>, <input>
HTML Entities
Some characters have special definitions in HTML or are reserved for HTML’s use.
Space: 			&nbsp;
Currency symbols:	Euro 	&euro;
Copyright: 			&copy;
W3Schools link: https://www.w3schools.com/html/html_entities.asp
DOCTYPE Declaration
Not an HTML tag. Instruction to the browser that the document is HTML
First line in an HTML page
example: <!DOCTYPE html> for HTML5. More complicated for XHTML
HTML Page basic layout
<!DOCTYPE html>
<html>
<head>
Non display information
Information the browser needs to properly render the web page
</head>

<body>
Displaying information or Content
</body>
</html>


Section: Introduction to Git (consider adding this after course has been offered for a semester)

Objectives:
Discuss the purpose and use of Git software
Use Git to ‘backup’ course files and projects

Content
Version control software often used as a way to backup files
Discuss Git repositories
Download and install Git
Make the website folder a Git folder
Demonstrate how to use Git to save files to their repositories


Section: Creating and formatting basic web pages.

Objectives:
Create a website folder for each website project.
include and use an images sub folder 
Create a well structured HTML page with a variety of elements
Understand how to correctly size and implement an image for a web page
Use the relative pathname to store images in a sub folder

Content
Create web pages with basic HTML tags.
Explore resources for learning HTML.
Create HTML Comments
Non displaying information. Notes within the page.
example: <!-- comments go here --> 
Apply formatting tags to affect text on a Web page.
Understand image files, formats, color modes, and pixel dimensions.
Add images to web pages
store an image in the images folder
Use a relative pathname in the src attribute
Create ordered, unordered, and descriptions lists.
Define list styles.
Create nested lists.
Validate a web page. 
W3C link: https://validator.w3.org/ 
Development tools in the browser showing ‘red’ tags

Section: Folders, Pathnames & Creating Links

Objectives:
Understand how to define and use default, relative and absolute pathnames
Create hyperlinks to the primary targets
Create hyperlinks using default and relative pathnames

Content:
Use the <a> element and the href attribute to make a hyperlink.
Format <a href=”desired target”>this will be the link</a>
Four main types of hyperlinks
Create a link to another Web site on the Internet. Uses http:// in the href value to access a website on the Internet
example: <a href=http://www.dmacc.edu>DMACC</a>
Create a link to another page or file on the same website. Uses the relative pathname to the desired file and the filename.
example: <a href=”pageTwo.html”>Next Page</a>
example: <a href=”files/brochure.pdf”>Download your copy</a>
Link to a specific location on the same web page. Uses “#” symbol in the href value to look for a named location or an id value.
Link example: To make the link <a href=”#leftHandColumn”>Menu</a> 
HTML5 target example:  <section id=”leftHandColum”>…</section>
XHTML target is still commonly used. Called a named target.
example: <section><a name=”leftHandColumn”></a>…</section
Link to a specific location on a different web page. Same symbol as the same page.
Link to a telephone number. Uses the tel: protocol.
example: <a href=”tel:+15551234567”>Call Support</a>
Additional Link attribute
target=”(_blank|_parent|_self|_top)”  Especially _blank
Use an image as a link
Create thumbnail links to larger images.
Create image maps.
Create rectangle, circle, and polygon hotspots.


Section: Introduction to CSS

Objectives:
Define and discuss the role of CSS
Discuss the concept of cascading stylesheets
Create examples of all three stylesheets
Define and discuss the following CSS terms
style conflict
specificity
precedence
inheritance
Apply CSS to a variety of elements using element, group, descendant, & pseudo selectors

Content:
Create a website folder with a css sub folder. It should contain external stylesheets
Define and discuss CSS
Discuss and demonstrate Cascading Style Sheets
Understand the advantages of using CSS.
Define a style rule.
selector {CSS property:value;…}
Discuss the selector and its purpose (connect the css to the HTML)
CSS Property -  A CSS command. 
CSS Reference https://www.w3schools.com/cssref/
Value - value assigned to the property
example: p {color: red}
Multiple properties may be assigned using the same selector
example: header {color: blue; background-color: red; } 
Apply color to text using CSS.
Discuss the concept of Inheritance
Create inline, embedded, and external CSS.
Discuss the concept of Specificity and Precedence
Change the appearance of a link using CSs.
Understanding the Box Model & Box Sizing.
Apply various borders to elements.
Create and use basic element & descendent selectors.
element selector
group selector
descendent selector
pseudo selector 	(links)

Section: Formatting Text

Objectives:
Compare and contrast absolute versus relative sized fonts and units of measure
Apply and implement web safe fonts
Apply and implement custom fonts
Apply CSS effects using class, id and universal selectors

Content:
Understand pros & cons of Web Safe fonts.
Apply fonts using font-family property.
Format size, style, weight, and size of fonts
Font size
Absolute Lengths
px or pixels
Relative Lengths
em relative to element font size
rem relative to font size of the root element
CSS sizing Reference: https://www.w3schools.com/cssref/css_units.asp 
Apply custom fonts.
@font-face Rule
Browser Compatibility reference: https://www.w3schools.com/cssref/css3_pr_font-face_rule.asp 
CSS Selectors
Class selectors
discuss class attribute
Create and apply independent and dependent class selectors.
Id selectors
discuss id attribute, unique to a page
create and apply Id selectors
Universal selector
Understand Specificity with conflicting CSS rules.

Unit 3 – Layout

Section: Layout Techniques

Objectives:
Create a web page using Source Order, Float and CSS Grid Layout
Apply CSS effects using id selectors
Create a page using semantic elements using a variety of layout techniques
Create a page using the div element with id attributes technique using a variety of layout techniques

Source Order
Works according to how the browser interprets or ‘render’s the HTML and CSS code. In the order it was written on the page.
This is the default way the browser will build and display the page
CSS Float Techniques
This technique is very common and has been heavily implemented over the years
Uses the CSS Float property to change the way the browser displays containers
The float property allows the developer to control where and how a container will be displayed
If you start a float you must ‘clear’ the float or the page could render incorrectly
CSS Grid Layout
A CSS alternative to layout a web page
Made for two dimensional layouts. Uses rows and columns to organize and control the layout
Organizes the structure of your page into containers for content
Good alternatively to Bootstrap is you all you need is a grid layout
Reference: https://www.w3schools.com/css/css_grid.asp 
Good article on the differences between Grid and Bootstrap: https://hackernoon.com/how-css-grid-beats-bootstrap-85d5881cf163
Flexbox Layout Module (may consider this to be optional or moved to Additional Topics)
A CSS alternative to layout a web page
Focuses on one dimensional control of either a row or a column
Works best when the layout goes in one direction, rows or columns. But not both.
Uses less code than Grid for a single dimension. 
Reference: https://www.w3schools.com/Css/css3_flexbox.asp 


Content:
<div> element versus semantic elements
demonstrate XHTML technique  <div id=”menu”>…</div> vs. <menu>…</menu>
The element name is self describing of its content and purpose
Understand the uses of Sematic Elements.
Non semantic elements are generic in their description of content
examples: <div>, <span>, …
HTML5 introduced many semantic elements
<header>, <menu>, <footer>, <section>, <aside>, <article>, <form>, <table>,…

Layout a web page using semantic containers using source order
Layout a web page using semantic containers using CSS float property
Layout a web page using non-semantic containers using CSS Grid
Layout a web page using semantic containers using CSS Grid
CSS Selectors
Id selector
Descendent selector


Section: Responsive Design Concepts

Objectives:
Discuss the primary concepts of responsive design
mobile first design
fixed versus fluid layout
absolute versus relative sizing
media queries to control changes in screen size
Create a web page using fluid layouts including images on a variety of screen sizes
Create a web page using CSS media queries on a variety of screen sizes

Content:
Building web pages that will display well on a variety of devices and screen sizes
It is a function of HTML and CSS techniques
Fixed versus Fluid Layout and units of CSS measure
Setting the Viewport
<meta name=”viewport” content=”width=device-width, initial-scale=1.0”>
CSS Media Queries
CSS tool that senses the size of the screen and provides different CSS commands to be applied as the screen size changes
@media rule
More needed here
Create and test a web page with a custom media query for mobile devices
Reference: https://www.w3schools.com/css/css_rwd_intro.asp 


Section: Introduction to Bootstrap Framework

Objectives:
Define and discuss the concept of a framework and why they are used
Discuss the role of the Bootstrap Framework focusing on responsive design
Implement Bootstrap for responsive design on a website

Content:
Bootstrap is the most common and best established Responsive Design Framework
It is a combination of HTML techniques, CSS files and Javascript files which are made available to the website application. It is pre-written CSS commands and Javascripts that work together to ensure the application will display well on multiple sizes of devices and screens
It is implemented using a cdn (content delivery network) which can be local to the site or global in the Internet
A Bootstrap stylesheet, jquery.js and a Bootstrap Javascript file are required in order to implement Bootstrap on your page. 
Understand the uses of Bootstrap
focus on Bootstrap responsive design features not its theming ability
discuss the grid layout concepts
The developer will need to learn Bootstrap’s CSS selectors and what they do so they can be implemented in the web page’s HTML. 
Create a web page that implements the Bootstrap Framework and test on multiple devices including mobile devices
Reference: https://www.w3schools.com/bootstrap/
Bootstrap Reference and Documentation: https://getbootstrap.com/ 


Unit 4 – Forms & Styling

Section: Creating html forms

Objectives:
Discuss the use of the form element and its attributes for form processing
Discuss the role of the input element on a form
Create and style a well structured and correctly coded form

Content:
Understand how data is collected and processed.
form element
method attribute
action attribute
input elements
name attributes
value attributes
Construct a basic html contact form using text fields and text area.
Use CSS to align fields and style basic form.
Create buttons for submitting and clearing data.

Section: Creating Complex Forms

Objectives:
Create and style a well structured and correctly coded form with a variety of form fields

Content:
Use fieldsets to organize form controls.
Use CSS flexbox to organize and align form elements.
Understand how to determine which types of input fields to use.
Construct a form using a variety of input fields including radio buttons, check boxes and select list.
Restrict the number of characters in a text box.

Section ?: Connecting a form to PHP processing

Objectives:
Discuss the purpose of using forms in a website application
Connect a form to PHP form processor on your host
Implement your form and discuss the results of the form processing

Content:
Introduce basic concepts of client-server processing
Discuss the form data
name-value pairs based upon the elements within the form
proper use of the name attribute
Discuss using the action attribute to send the form data to the server
Discuss the response from the server and its presentation in the browser



Unit 5 – Additional Topics
Understand how to construct data tables.
Use Googlemaps to include a map in a web page.
Understand how to had video and other media to web pages.
CSS positioning
Gradients
