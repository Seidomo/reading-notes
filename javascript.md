


# HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER 

- Before diving into the JavaScript language, you need to know how it will fit       together with the HTML and CSS in your web pages. 

Web developers usually talk about three languages that are used to create web pages: HTML, CSS, and JavaScript. 

 
# html files 

This is where the content of the page lives. The HTML gives the page structure and adds semantics. 

Where possible, aim to keep the three languages in separate files, with the HTML page linking to CSS and JavaScript files. 


# CSS 

The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.). 
Programmers often refer to this as a separation of concerns. 
Each language forms a separate layer with a different purpose. Each layer, from left to right. builds on the previous one. 

# JavaScript

This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files. 

# HTML ONLY 
Starting with the HTML layer allows you to focus on the most important thing about your site: its content. 
Being plain HTML, this layer should work on all kinds of devices, be accessible to all users, and load quite quickly on slow connections. 

# HTML+CSS 
Adding the CSS rules in a separate file keeps rules regarding how the page looks away from the content itself. 
You can use the same style sheet with all of your site, making your sites faster to load and easier to maintain. Or you can use different style sheets with the same content to create different views of the same data.

# HTML+CSS+JAVASCRIPT 
The JavaScript is added last and enhances the usability of the page or the experience of interacting with the site. 
Keeping it separate means that the page still works if the user cannot load or run the JavaScript. You can also reuse the code on several pages (making the site faster to load and easier to maintain). 

# PLACING THE SCRIPT IN THE PAGE 
You may see JavaScript in the HTML between opening <script> and closing </script> tags (but it is better to put scripts in their own files). 
