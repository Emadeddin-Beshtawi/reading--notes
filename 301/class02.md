# React: 

### Component Lifecycle Events

React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

**Mounting**, **Updating**, and **Unmounting** are the **three phases** of the component lifecycle.


### React Docs - handling events

Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences:

React events are named using camelCase, rather than lowercase. With JSX you pass a function as the event handler, rather than a string

**Example:**

```

<button onclick="activateLasers()">
  Activate Lasers
</button>

```

However in React it's slightly different

**Example:**

```

<button onclick="activateLasers()">
  Activate Lasers
</button>

<button onClick={activateLasers}>
  Activate Lasers
</button>

```

### Conditional Rendering

In React, you can create distinct components that encapsulate behavior you need. Then, you can render only some of them, depending on the state of your application.

**Example:**

```
function UserGreeting(props) {
  return <h1>Welcome back!</h1>;
}

function GuestGreeting(props) {
  return <h1>Please sign up.</h1>;
}

```
### Element Variables

We can use variables to store elements. This can help us conditionally render a part of the component while the rest of the output doesn’t change.

