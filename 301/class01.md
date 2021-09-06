# React

#### Overview

React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.

**JSX** comes with the full power of JavaScript. You can put any JavaScript expressions within braces inside **JSX**. Each React element is a JavaScript object that you can store in a variable or pass around in your program.


**Example:**

```
const element = <h1>Hello, world!</h1>;

```

### JSX 

React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display. React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

**JSX is an Expression Too**

After compilation, JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects.

This means that you can use JSX inside of if statements and for loops, assign it to variables, accept it as arguments, and return it from functions:

**Example:**

```

function getGreeting(user) {
  if (user) {
    return <h1>Hello, {formatName(user)}!</h1>;
  }
  return <h1>Hello, Stranger.</h1>;
}

```

## Props in React

React is a component-based library which divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props.

**“Props” is a special keyword in React**, which stands for properties and is being used for passing data from one component to another.
But the important part here is that data with props are being passed in a uni-directional flow. (one way from parent to child)

Furthermore, **props** data is read-only, which means that data coming from the **parent** should **not** be changed by **child** components.