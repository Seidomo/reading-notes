 


 # DESIGN WEB PAGES WITH CSS

css properties affect how elements are displayed

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.


CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.

# <link>

The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element. It should use three attributes:

# href 

This specifies the path to the CSS file (which is often placed in a folder called css or styles).
type This attribute specifies the type of document being linked to. The value should be text/css.

# rel 

This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.
