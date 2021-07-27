# HTML

## HTML Links

#### HTML Links - Hyperlinks

HTML links are hyperlinks.

You can click on a link and jump to another document.

When you move the mouse over a link, the mouse arrow will turn into a little hand.

Note: A link does not have to be text. A link can be an image or any other HTML element!


#### HTML Links - Syntax

The HTML < a> tag defines a hyperlink. It has the following syntax:

< a href="url" >link text< /a >
The most important attribute of the < a > element is the href attribute, which indicates the link's destination.

The link text is the part that will be visible to the reader.

Clicking on the link text, will send the reader to the specified URL address.


#### HTML Links - The target Attribute

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The **target** attribute specifies where to open the linked document.

The **target** attribute can have one of the following values:

* **_self** - Default. Opens the document in the same window/tab as it was clicked

* **_blank** - Opens the document in a new window or tab

* **_parent** - Opens the document in the parent frame

* **_top** - Opens the document in the full body of the window

#### HTML Links - Use an Image as a Link

![ds](https://image.slidesharecdn.com/html-link-image-comments-141030053653-conversion-gate02/95/html-link-image-comments-12-638.jpg?cb=1414647662)



#### **Summary**

* Use the < a > element to define a link

* Use the href attribute to define the link address

* Use the target attribute to define where to open the linked document

* Use the < img> element (inside < a>) to use an image as a link

* Use the mailto: scheme inside the href attribute to create a link that opens the user's email program


## Layout

#### HTML Layout Elements

HTML has several semantic elements that define the different parts of a web page:

* < header> - Defines a header for a document or a section

* < nav> - Defines a set of navigation links

* < section> - Defines a section in a document

* < article> - Defines an independent, self-contained content

* < aside> - Defines content aside from the content (like a sidebar)

* < footer> - Defines a footer for a document or a section

* < details> - Defines additional details that the user can open and close on demand

* < summary> - Defines a heading for the < details> element


![sd](https://www.w3schools.com/html/img_sem_elements.gif)



#### HTML Layout Techniques

There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:

1. CSS framework

2. CSS float property

3. CSS flexbox

4. CSS grid



##  JS Functions

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

#### Why Functions?
You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.


![g](https://raw.githubusercontent.com/learn-co-curriculum/cssi-2.3-functions/master/images/functions.png)


## JavaScript Objects

Objects are variables too. But objects can contain many values.

This code assigns many values (Fiat, 500, white) to a variable named car:

const car = {type:"Fiat", model:"500", color:"white"};

The values are written as name:value pairs (name and value separated by a colon).


#### Object Definition

You define (and create) a JavaScript object with an object literal:

const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};


#### Object Methods

Objects can also have methods.

Methods are actions that can be performed on objects.

Methods are stored in properties as function definitions.



![hd](https://www.javascripttutorial.net/wp-content/uploads/2016/09/Create-Objects-in-JavaScript-Prototype-Pattern.png)


For more information [Click Here](http://htmlandcssbook.com/extras/)
