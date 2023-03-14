### **Difference Between Window Object And Document Object**

**Window Object :** The window object is the topmost object of the DOM hierarchy. It represents a browser window or frame that displays the contents of the webpage. Whenever a window appears on the screen to display the contents of the document, the window object is created.

**syntax:** 

window.propertyname;

![Window object Model](https://cdn-images-1.medium.com/max/1000/0*JGTPBVSYzViU34rT)

Window Object Model

**Document Object :** When a web page is loaded, the browser creates a Document Object Model of the page. The document object represents the whole html document as a tree of Objects(HTML, HEAD, BODY, and other HTML tags). It is the root element that represents the html document.

**syntax:**

document.propertyname;

  

![](https://cdn-images-1.medium.com/max/1000/0*dQoKscGTCQw-_jyg.png)

Document Object Model

Each HTML document that gets loaded into a window becomes a document object. The document contains the contents of the page. Using document object, JavaScript can modify, add and delete the HTML elements, attributes CSS styles in the page.

**Window Object Vs Document Object**

The _window object_ represents a window/tab containing a DOM document where as _document object_ is property of window object that points to the DOM document loaded in that window.

The _window_ is the object of the browser. The _document_ is the object of window property.

Global objects, functions, and variables of JavaScript are members of the _window object_. All the tags, elements with attributes in HTML are part of the _document object_.

The _window_ is part of BOM, not DOM. The _document_ is part of BOM (Browser object model) and DOM (Document object model).

Properties of the _window object_ cannot be accessed by the document object. Properties of _document objects_ such as title, body, cookies, etc can also be accessed by a window.

The other major difference is that both window object and document object have properties and methods. Few method names are same in both objects but with different behavior. For example _window.open()_ opens a new tab or window and _document.open()_ creates a blank document within the window.