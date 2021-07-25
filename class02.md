# HTML & CSS :

## HTML Text:

### Headings:

#### HTML has six “levels” of headings:

< h1> < /h1> up to < h6> < /h16>

#### Paragraphs: (< p> tag)
 <p ></p >

#### Bold & Italic:

Bold: < Strong >< /Strong> 

Italic: < em>< /em>


#### Superscript & subscript:

< sup>

The < sup> element is used to contain characters that should be superscript

< sub>

The < sub> element is used to contain characters that should be subscript.

#### White Space:

When the browser comes across two or more spaces next to each other, it only displays one space.

Line Breaks & Horizontal Rules:

< br />

If you wanted to add a line break inside the middle of a paragraph you can use the line break tag < br />.

< hr />

To add a horizontal rule between sections using the < hr /> tag.

#### Quotations:

< blockquote > for long quotes.


< q > for short quotes.


#### Abbreviations & Acronyms:

< abbr> to define shortcuts like html, who (refers to person).

#### Changes to Content:

< del > make a line on the text to mean this text deleted.


< ins> element can be used to show content that has been inserted into a document.

## CSS Introduction:


![image css](https://3.bp.blogspot.com/-mWabh9GjNx4/WFFtM3Qqe0I/AAAAAAAAAbg/PSoxAfX20yo73E76um_DPan_rnTzZCluwCLcB/s1600/css-2-how-to-write.png)



#### Summary:

* CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.

* Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).

* Different types of selectors allow you to target your rules at different elements.

* Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.


* CSS rules usually appear in a separate document, although they may appear within an HTML page.


# JavaScript


![ja](https://1.bp.blogspot.com/-EPrHJaCTGoU/X3MajXYktEI/AAAAAAAAB5E/qgkmTg0A0s0aRzvsmhmGpa3z2r9bQjIYwCLcBGAsYHQ/w400-h281/668dfc002312ab58e0d1cb15e0b98a5e.png)



#### Comments in JS

//----> this for single line comment like

      //  single comment
/* */ ----> this for multi-line comment.like

     /* multi
         line
           comment   */


#### Variables in JS

* **Example**


 var Name;
 var x;
 let y;

How to assign it? by using assignment operator. ex: var x=6;

* **variable datatypes**


 ** Number: it can be any number int, float,...etc

 ** Boolean: true or false

 ** String: anything inside double-quotation or single-quotation.

 
#### How to trigger JavaScript from HTML

Within a browser, JavaScript doesn't do anything by itself. You run JavaScript from inside your HTML webpages. To call JavaScript code from within HTML, you need the < script> element. There are two ways to use script, depending on whether you're linking to an external script or embedding a script right in your webpage.


#### Linking an external script

Usually, you'll be writing scripts in their own .js files. If you want to execute a .js script from your webpage, just use < script> with an src attribute pointing to the script file, using its URL:

< script src="path/to/my/script.js"></ script >


#### Writing JavaScript within HTML

You may also add JavaScript code between < script> tags rather than providing an src attribute.

< script >
window.addEventListener('load', function () {
  console.log('This function is executed once the page is fully loaded');
});
< /script >

That's convenient when you just need a small bit of JavaScript, but if you keep JavaScript in separate files you'll find it easier to

* focus on your work

* write self-sufficient HTML

* write structured JavaScript applications

#### How to Write a Git Commit Message

1) Separate subject from body with a blank line

2) Limit the subject line to 50 characters

3) Capitalize the subject line

4) Do not end the subject line with a period

5) Use the imperative mood in the subject line

6) Wrap the body at 72 characters

7) Use the body to explain what and why vs. how


#### Editor method

Run git commit without a message or option and it'll open up your default text editor to write a commit message.

To configure your "default" editor:

git config --global core.editor nano

This would configure Git to use nano as your default editor. Replace "nano" with "emacs," "vim," or whatever your preference is.

In the opened editor, the first line is the subject (short description), leave a blank line after it, and everything else is the extended description (body).

< Summarize change(s) in around 50 characters or less>

< More detailed explanatory description of the change wrapped into about 72 characters >

#### Command Line method

git commit -m "Subject" -m "Description..."

The first -m option is the subject (short description), and the next is the extended description (body)

For more information [click here](https://chris.beams.io/posts/git-commit/#separate)
