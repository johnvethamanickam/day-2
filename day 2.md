Question 1: Difference Between Window Object And Document Object

Answer :

**Window Object** : The window object is the topmost object of the DOM hierarchy. It represents a browser window or frame that displays the contents of the webpage. Whenever a window appears on the screen to display the contents of the document, the window object is created.

syntax: 

```js
window.propertyname;
```
![image](https://user-images.githubusercontent.com/127470114/225083022-a2104653-d093-484b-af14-716414d2cc3e.png)

Window Object Model

**Document Object** : When a web page is loaded, the browser creates a Document Object Model of the page. The document object represents the whole html document as a tree of Objects(HTML, HEAD, BODY, and other HTML tags). It is the root element that represents the html document.

syntax:
```js
document.propertyname;
```

![image](https://user-images.githubusercontent.com/127470114/225083198-9295ee88-9689-4b3a-a2a5-1cc2df2109b9.png)

Document Object Model

Each HTML document that gets loaded into a window becomes a document object. The document contains the contents of the page. Using document object, JavaScript can modify, add and delete the HTML elements, attributes CSS styles in the page.

**Window Object Vs Document Object** :

The window object represents a window/tab containing a DOM document where as document object is property of window object that points to the DOM document loaded in that window.

The window is the object of the browser. The document is the object of window property.

Global objects, functions, and variables of JavaScript are members of the window object. All the tags, elements with attributes in HTML are part of the document object.

The window is part of BOM, not DOM. The document is part of BOM (Browser object model) and DOM (Document object model).

Properties of the window object cannot be accessed by the document object. Properties of document objects such as title, body, cookies, etc can also be accessed by a window.

The other major difference is that both window object and document object have properties and methods. Few method names are same in both objects but with different behavior. For example window.open() opens a new tab or window and document.open() creates a blank document within the window.
