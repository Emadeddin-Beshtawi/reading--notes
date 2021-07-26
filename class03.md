# HTML & CSS

## HTML Lists:

* Unordered HTML List

**Example:**

< ul>
  < li>Coffee< /li >
  < li >Tea< /li >
  < li>Milk< /li >
< /ul>


* Ordered HTML List

**Example:**

< ol>
  < li>Coffee< /li>
  < li>Tea< /li>
  < li>Milk< /li>
< /ol>

* HTML Description Lists

**Example:**

< dl>
  < dt>Coffee< /dt>
  < dd>- black hot drink< /dd>
  < dt>Milk< /dt>
  < dd>- white cold drink< /dd>
< /dl>

## CSS Boxes

* Box Dimensions

Explanation of the different parts:

1. Content - The content of the box, where text and images appear

2. Padding - Clears an area around the content. The padding is transparent

3. Border - A border that goes around the padding and content

4. Margin - Clears an area outside the border. The margin is transparent


# JavaScript

## ARRAYS

An array is a special variable, which can hold more than one value at a time.

If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:

* let car1 = "Saab";

* let car2 = "Volvo";

* let car3 = "BMW";

However, what if you want to loop through the cars and find a specific one? And what if you had not 3 cars, but 300?

The solution is an array!

An array can hold many values under a single name, and you can access the values by referring to an index number.


## The else if Statement

### Conditional Statements

Very often when you write code, you want to perform different actions for different decisions.

You can use conditional statements in your code to do this.

In JavaScript we have the following conditional statements:

* Use if to specify a block of code to be executed, if a specified condition is true
* Use else to specify a block of code to be executed, if the same condition is false
* Use else if to specify a new condition to test, if the first condition is false
* Use switch to specify many alternative blocks of code to be executed


### The if Statement

Use the if statement to specify a block of JavaScript code to be executed if a condition is true.

**Syntax**

if (condition) {
  //  block of code to be executed if the condition is true
}
Note that if is in lowercase letters. Uppercase letters (If or IF) will generate a JavaScript error.

## Switch Statement

Use the switch statement to select one of many code blocks to be executed.

This is how it works:

1. The switch expression is evaluated once.

2. The value of the expression is compared with the values of each case.

3. If there is a match, the associated block of code is executed.

4. If there is no match, the default code block is executed.

![swi](https://www.codegrepper.com/codeimages/javascript-switch-statement-case-multiple-returns-value.png)

# Loops

## The For Loop

The for loop has the following syntax:

for (statement 1; statement 2; statement 3) {
  // code block to be executed
}

* Statement 1 is executed (one time) before the execution of the code block.

* Statement 2 defines the condition for executing the code block.

* Statement 3 is executed (every time) after the code block has been executed.


![for](https://www.javascripttutorial.net/wp-content/uploads/2020/01/JavaScript-for-Loop.png)


## The While Loop

The while loop loops through a block of code as long as a specified condition is true.

The while loop loops through a block of code as long as a specified condition is true.

Syntax while (condition) { // code block to be executed } 

**Example**

In the following example, the code in the loop will run, over and over again, as long as a variable (i) is less than 10:

while (i < 10) { text += “The number is “ + i; i++; }


![wh](https://www.codegrepper.com/codeimages/example-of-while-loop-in-javascript-with-array-length.png)

For more information [Click Here](https://www.w3schools.com/js/default.asp) 
