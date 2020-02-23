# Problem domain :

understanding the problem is the most critical piece to the equation as it is very difficult to solve a problem before you understand exactly what is the question.

**Programming is easy if you understand the problem domain**



# CH:3 JS Object Literals 
100-105

- Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. 

- In an object, variables and functions take on new names.

 *variable: property*

 *function: method*

- you can access the properties or the methods of the object by using dot notation.

- you can access properties also by using square brackets.



# ch:5 JS Document Object Model
183-242

**DOM**:how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

*It consists of four main types of nodes*:

- THE DOCUMENT NODE 
- ELEMENT NODES 
- ATTRIBUTE NODES 
- TEXT NODES 

**Accessing and updating the DOM tree involves two steps**:

1- Locate the node that represents the element you want to work with.

2- Use its text content, child elements, and attributes. 

*individual element:*

- get El ement Byld () 
- querySe 1 ector () 

*multiple elements:*

- getElementsByClassName() 
- getElementsByTagName() 
- querySelectorAll() 

*traversing*

- parentNode 
- previousSibling / nextSibling
- firstChild / lastChild 

3- Work with those elements.

**DOM queries**:

METHODS THAT RETURN A SINGLE ELEMENT NODE: 

- getElementByld('id')
- querySelector( 'css selector') 

METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST): 

- getElementsByClassName('class')
- getElementsByTagName('tagName') 
- querySelectorAll ('css selector') 

**looping through a nodelist**

`var hotltems = document.querySelectorAll ('l i .hot');`

`if (hotltems.length > O) { `

`for (var i=O; i<hotltems.length; i++) {  hotltems[i] .className = 'cool';}`





