# CSS 
CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface. Once you have learned how to write a CSS rule, learning CSS mostly involves learning the different properties you can use. So this chapter will: 
* introduce you to how CSS works
 * Teach you how to write CSS rules 
 * Show you how CSS rules apply to HTML pages Understanding CSS: Thinking Inside the Box The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element. Using CSS, you could add a border around any of the boxes,specify its width and height, or add a background color. You could also control text inside a box — 
### for example,
 its color, size, and the typeface used. Here you can see a simple web page that is styled using CSS. This example uses two documents: the HTML file (example.html) and a separate CSS file (example.css). The fifth line of HTML uses the

**Element** to indicate where the CSS file is located. On the next page, you will see how CSS rules can also be placed in your HTML pages and we will discuss when you might want to do this. <!DOCTYPE html>

From Garden to Plate
A potager is a French term for an ornamental vegetable or kitchen garden ...

## What to Plant
Plants are chosen as much for their functionality as for their color and form ...

body { font-family: Arial, Verdana, sans-serif;} h1, h2 { color: #ee3e80;} p { color: #665544;} Using External CSS.

**The element** can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element. It should use three attributes: href This specifies the path to the CSS file (which is often placed in a folder called css or styles). type This attribute specifies the type of document being linked to. The value should be text/css. rel This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look. X Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like). X Different types of selectors allow you to target your rules at different elements. X Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface. X CSS rules usually appear in a separate document, although they may appear within an HTML page.

## color: 
The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways: rgb values These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90) hex codes These are six-digit codes that represent the amount of red,green and blue in a color, preceded by a pound or hash #sign. For example: #ee3e80 color names There are 147 predefined color names that are recognized by browsers. For example: DarkCyan