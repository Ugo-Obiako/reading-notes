# Read 02: State and Props

State and props are used to manage and pass data within components in a React application. 

#### 1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

render happens before componentDidMount.

#### 2. What is the very first thing to happen in the lifecycle of React?

The constructor for a React component is called first.

#### 3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

constructor, render, React Updates, componentDidMount, componentWillUnmount

#### 4. What does componentDidMount do?

componentDidMount method is invoked immediately after a component is mounted and is used to load anything using a network request or to initialize the DOM.

# React State Vs Props

#### 1. What types of things can you pass in the props?

Things that can be passed into props include:
strings, numbers, booleans, functions, objects and arrays, etc. 
etc

#### 2. What is the big difference between props and state?

Props are used to pass data from a parent component to a child component and are immutable (read-only) within the component receiving them. State, on the other hand, is managed within a component and is used to store mutable data that influences a component's behavior and rendering.

#### 3. When do we re-render our application?

The following scenarios can trigger re-rendering in a React application:

- state changes
- props Changes
- forceful re-rendering

#### 4. What are some examples of things that we could store in state?

- Form input values
- UI State
- Conditional rendering data
- API Data
- Counters or incremental values

# Things I want to know more about


