# ***Read06***

## ***JavaScript***

### **Objects: **
-	*Objects* group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.
-	If a variable is part of an object, it is called a *property* .
-	If a function is part of an object, it is called a *method* .
-	This object represents a variable. It has five properties and one method. The object is in curly braces.
-	To access a property of this object, the object name is followed by a dot (the period symbol) and the name of the property that you want.
-	Similarly, to use the method, you can use the object name followed by the method name.
-	If you had two objects on the same page, you would create each one using the same notation but store them in variables with different names.

### **Document object model**
-	The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
-	The DOM is called an object model because the model (the DOM tree) is made of objects.
-	The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser.
-	You will hear people call the DOM an Application Programming Interface (API). User interfaces let humans interact with programs; APls let programs (and scripts) talk to each other.
-	Accessing and updating the DOM tree involves two steps: 1: Locate the node that represents the element you want to work with. 2: Use its text content, child elements, and attributes.
-	DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.
-	get ElementByid () allows you to select a single element node by specifying the value of its id attribute.
-	The get ElementsByClass Name() method allows you to select elements whose c 1 ass attribute contains a specific value.
-	The get ElementsByTagName () method allows you to select elements using their tag name.
-	querySelector() returns the first element node that matches the CSS-style selector. querySelectorA11 () returns a Nodelist of all of the matches.
-	***If you want to apply the same code to numerous elements, looping through a Nodelist is a powerful technique.***
-	An element node can contain multiple text nodes and child elements that are siblings of each other.
-	Browsers offer tools for viewing the DOM tree .
