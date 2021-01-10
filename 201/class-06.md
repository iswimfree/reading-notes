# Problem Domain, Objects, and the DOM
> I see the crystal raindrops fall and the beauty of it all
is when the sun comes shining through - Bill Withers, Just The Two of Us.

## Chapter 3: “Object Literals” (pp.100-105)

+ Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.
+ If a function is part of an object, it is called a method.
+ If a variable is part of an object, it is called a property. Properties tell us about the object, such as the name of a hotel or the number of rooms it has.
+ variables and named functions, properties and methods have a name and a value. In an object,
that name is called a key.
+ HTML uses attribute names and values.
+ CSS uses property names and values.
  
## Chapter 5: “Document Object Model” (pp.183-242)

+ The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
+ The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas
+ The DOM is called an object model because the model (the DOM tree) is made of objects.
+ As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes.
+ Every element, attribute, and piece of text in the HTML is represented by its own DOM node.
At the top of the tree a document node is added; it represents the entire page and also corresponds to the document object, 
+ HTML elements describe the structure of an HTML page. (The < hl>  < h6> elements describe what parts are headings; the < p> tags indicate where paragraphs of text start and finish; and so on
+ Relationships between the document and all of the element nodes are described using the same terms as a family tree: parents, children, siblings, ancestors, and descendants. Every node is a descendant of the document node.
+ DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.

[Back to main](README.md)