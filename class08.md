# Layouts in CSS:

#### CSS and HTML

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box:


Block-level: start on a new line. `<h1> <p> <ul> <li>`

Inline-level: flow in between surrounding text. `<img> <b> <i>`


#### Position Property

Using the position property, CSS has the following positioning schemes that allow you to control the layout of a page:

* normal flow. `position:static`

* relative positioning. `position:relative`

* absolute positioning. `position:absolute`

* fixed positioning. `position:fixed`




#### Float Property

Also, the float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. This can be float:right or float-left. Furthermore, float can be cleared using the clear property, the values can be left, right, both and none. To create multi-column layouts with floats, The following three CSS properties are used to position the columns next to each other:


* `width`: sets the width of the columns.

* `float`: positions the columns next to each other.

* `margin`: creates a gap between the columns.




#### Layout Design

Because screen sizes and display resolutions vary so much, web pages might not be displayed as desired by the designer. However, designers follow two methods in terms of layout design, described as follows:


* Fixed-width layout: do not change size as the user increases or decreases the size of their browser window. `px`

* Liquid layout: stretch and contract as the user increases or decreases the size of their browser window. `%`