# Forms and JS Events

### Forms

An HTML form is used to collect user input. The user input is most often sent to a server for processing.


**Text Boxs**

```

<form>
  <input type="text" id="firstName" name="firstName" placeholder="first name">
  <input type="text" id="lastName" name="lastName" placeholder="last name">
</form>


```

**Check-Boxes**

```

<form>
  <input type="checkbox" id="colorBlack" name="firstName" placeholder="first name">
  <label for="car1" >one of my fav. color black</label><br>
</form>


```

**Radio Buttons**

```

<form>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">male</label><br>
</form>

```

and so on, there are a lot of `forms` in HTML



### Lists, tables and Forms

**Define an HTML Table:**


The `<table>` tag defines an HTML table.

Each table row is defined with a `<tr>` tag. Each table header is defined with a `<th>` tag. Each table data/cell is defined with a `<td>` tag.

By default, the text in `<th>` elements are bold and centered.

By default, the text in `<td>` elements are regular and left-aligned.


**Example**

```
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>

```


**HTML lists** allow web developers to group a set of related items in lists.


* Unordered HTML List.

* Ordered HTML List.

* HTML Description Lists.



### JavaScript Events

HTML events are **"things"** that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can **"react"** on these events.

**HTML Events:**

An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

* An HTML web page has finished loading

* An HTML input field was changed

* An HTML button was clicked

Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

With single quotes:

```

<element event='some JavaScript'>

```

With double quotes:

```

<element event="some JavaScript">

```



