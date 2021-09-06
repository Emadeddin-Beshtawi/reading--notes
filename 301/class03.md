# Passing Functions as Props

### Lists and Keys

Given the code below, we use the `map()` function to take an array of `numbers` and double their values. We assign the new array returned by `map()` to the variable `doubled` and log it:

```

const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map((number) => number * 2);
console.log(doubled);

```
This code logs `[2, 4, 6, 8, 10]` to the console.

In React, transforming arrays into lists of `elements` is nearly identical.


### Rendering Multiple Components

You can build collections of elements and `include them in JSX` using curly braces `{}`.

Below, we loop through the `numbers` array using the JavaScript `map()` function. We return a `<li>` element for each item. Finally, we assign the resulting array of elements to `listItems`:

```

const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);

```
We include the entire `listItems` array inside a `<ul>` element, and **render it to the DOM**:

```
ReactDOM.render(
  <ul>{listItems}</ul>,
  document.getElementById('root')
);

```

This code displays a bullet list of numbers between 1 and 5.

### Keys

Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:

```
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li key={number.toString()}>
    {number}
  </li>
);

```

The best way to pick a key is to use a string that uniquely identifies a list item among its siblings. Most often you would use IDs from your data as keys:

```
const todoItems = todos.map((todo) =>
  <li key={todo.id}>
    {todo.text}
  </li>
);

```

# How to Use the Spread Operator (…) in JavaScript

### What is the spread operator?

In **JavaScript**, spread syntax refers to the use of an ellipsis of three dots `(…)` to expand an iterable object into the list of arguments.


### What is `...` used for?

Spread operator to the rescue! It looks similar to rest parameters, also using `...`, but does quite the opposite.
