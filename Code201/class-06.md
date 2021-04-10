Read 06 - JS Object Literals; The DOM

<p> the first thing we will talk a little bit about Object Literals, also Document Object Model.

Object Literals

What is an object, also how it works?
it's like a lot of variables and functions to create something or declare it.
also, the name will be different a little Variables become known as properties, also Functions become known as Methods.

let us see some photo to make my explanations more clear;

properties VS method

This to distinguish the difference between properties and vlaues;

Document Object Model;

DOM It is a word that refers to an abbreviation of Document Object Model it's responsible for how to model HTML formats, it's a tree model for HTML.

There is a 4 tree type of DOM
Document node used to access all other types of nodes.
Element node used to access specific element.
Attribute node used to access elements attributes.
Text node used to access elements text.

WORKING WITH DOM TREE, there are two main steps:

1-ACCESS THE ELEMENTS
>
>select an individual element: getElementByld () ,querySe1ector ()
>select multiple elements: getElementsByClassName(), getElementsByTagName(), querySelectorAll()
>
we can also move from one element  to a related element by using:
parentNode: Selects the parent of the current element node (which will return just one element).
previousSibl ing / nextSibl ing: Selects the previous or next sibling from the DOM tree.
firstChild / lastChild : Select the first or last child of the current element.

2-WORK WITH THOSE ELEMENTS:

ACCESS OR UPDATE ATTRIBUTE VALUES:
>Select the <li> .element
Use the firstChild property to get the text node
Use the text node’s only property (nodeValue).

WORK WITH HTML CONTENT
innerHTML : access to child elements and text content
extContent: just the text content
create new nodes, add nodes to a tree, and remove nodes from a tree:
>create Element(),
>createTextNode()
>appendChild ()
>removeChild ();

ACCESS OR UPDATE ATTRIBUTE VALUES
>getAttribute():gets its value.
>setAttribute():updates the value.

className /id :Lets you get or update the value of the class and id attributes.
hasAttribute(): checks if an attribute exists.

</p>

**_I hope you enjoyed your time reading._**

_**References :Ch.3 & Ch.5 / JavaScript & JQuery:Interactive Front-End Development.**_
