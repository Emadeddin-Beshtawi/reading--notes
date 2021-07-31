# Domain Modeling:

An object-oriented model is an entity that stores data in properties and encapsulates behaviors in methods. To define the same properties between many objects, a constructor function is used. In general, object-oriented programming in JavaScript looks like the following:

* The new keyword instantiates (i.e. creates) an object.

* The constructor function initializes properties inside that object using the this variable.

* The object is stored in a variable for later use.

**Example:**

var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}
var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);


Also, random number generators are useful when using objects and contructors.

# Tables in HTML:

A table represents information in a grid format. Each block in the grid is referred to as a table cell. In HTML, atable is written out row by row. The following is the structure of the table in HTML:

* < table>: creates a table.

* < tr>: rows.

* < td>: columns.

* < th>: table headings.

* colspan: stretchs the entry across more than one column.

* rowspan: stretchs the entry across more than one row.

* < thead>: the headings of the table should sit inside it.

* < tbody>: the body should sit inside it.

* < tfoot>: the footer belongs inside it.

# Functions, Methods, and Objects in Javascript:

To create an object using the constructor notation, the keyword new is used. Here's an example: var hotel = new object();, then you assign values to its properties. Also, the dot notation and square brackets are used to update the object's properties. To delete and objet, delete keyword is used. Furthermore, you can create an instance of the object using the constructor function.

**Example:**

function Hotel (name, rooms, booked) {
this .name = name;
this.rooms = rooms;
this.booked = booked;
this.checkAvailability = function()
return this.rooms - this.booked;
} ;
var quayHotel
var parkHotel
new Hotel('Quay', 40, 25);
new Hotel( ' Park', 120, 77);


**The following are significant features used in contructors and objects:**

* **this**: used to refer to the object, used inside of it, and it is often associated with a property of that object: this.name = "Emad".

* Storing properties: **variables** and **arrays**.

* **Declaring objects:**

- Literal Noration (Individual objects):

var hotel = {
name: ' Quay',
rooms: 40
};

- Constructor Function (Multiple Objects):

function Hotel (name, rooms){
this .name = name;
this.rooms = rooms;
}


* Arrays: arrays in objects can be accessed by their index: **costs.room1.items[ 0]**.


There are several built-in objects in javascript, such as the following:

- Browser Object Model.

- Document Object Model.

- Global Javascript Objects.