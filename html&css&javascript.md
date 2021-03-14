# HTML, CSS, & Javascript Fit Together
- <html>: content layer, .html files
  - The content of the page lives here
  - gives structure and adds semantics
- {CSS}: presentation layer, .css files
  - The CSS enhances the HTML page with rules that state how
    the HTML content is presented (backgrounds, borders, box
dimensions, colors, fonts, etc.). 
- javascript()
  - BEHAVIOR LAYER .js files
    This is where we can change how the page behaves, adding
    interactivity. We will aim to keep as much of our JavaScript as
    possible in separate files. 

# Progressive Enhancement
## These three layers form the basis of a popular approach to building web pages called
## progressive enhancement. 
  - HTML ONLY
    - Starting with the HTML layer allows you to focus on the most
      important thing about your site: its content.
    - Being plain HTML, this layer should work on all kinds of
      devices, be accessible to all users, and load quite quickly on
      slow connections
  - HTML+CSS
    - Adding the CSS rules in a separate file keeps rules
      regarding how the page looks away from the content itself.  
    - You can use the same style sheet with all of your site, making your
      sites faster to load and easier to maintain. Or you can use
      different style sheets with the same content to create different
      views of the same data. 
  - HTML+CSS+JAVASCRIPT
    - The JavaScript is added last and enhances the usability of
      the page or the experience of interacting with the site. 
    - Keeping it separate means that the page still works if the
      user cannot load or run the JavaScript. You can also reuse
      the code on several pages (making the site faster to load
      and easier to maintain). 
## Creating a basic javascript
  - JavaScript is written in plain text, just like HTML and CSS, so you do not
    need any new tools to write a script. This example adds a greeting into an
    HTML page. The greeting changes depending on the time of day. 
  -  Create a folder to put the example in called cOl, then start
      up your favorite code editor, and enter the text to the right.
      A JavaScript file is just a text file (like HTML and CSS
      files are) but it has a .js file extension, so save this file with
      the name add-content .js
  - Example:
    - var today= new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
greeting= 'Good evening!';
else if (hourNow > 12) {
greeting = ' Good afternoon!';
else if (hourNow > 0) {
greeting = 'Good morni ng!';
else {
greeting = 'Welcome! ' ;
\# document .write( ' <h3>' +greeting + ' </ h3> ');  
- To keep the files organized, in the same way that CSS files
  often live in a folder called styles or css, your JavaScript
  files can live in a folder called scripts,javascript,or js.
  In this case, save your file in a folder called js
- Linking to a javascript file from an html page
  - In your code editor, enter the HTML shown on the left. Save
    this file with the name add-content.html 
-The HTML <script> element is used to load the JavaScript file
 into the page. It has an attribute called src, whose value is the
  path to the script you created.
- This tells the browser to find and load the script file (just like the
  src attribute on an <i mg> tag).
    - Example:
    <!DOCTYPE html>
<html>
<head>
<title>Constructive &amp; Co.</ title>
<link rel ="stylesheet" href="css/ cOl.css" />
</ head>
<body>
<hl>Constructive &amp ; Co. </ hl>
<script src="js/ add-content.js"></ script>
<p>For all orders and i nquiries please cal l
<em>SSS-3344</ em></ p>
</ body>
</html>
  
 






   


















