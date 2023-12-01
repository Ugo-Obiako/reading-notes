# Read 05

# React Docs - Thinking in React

#### 1. What is the single responsibility principle and how does it apply to components?

According to the single responsibility principle, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

#### 2. What does it mean to build a ‘static’ version of your application?
It means to build a version that renders the UI from your data model without adding any interactivity.

#### 3. Once you have a static application, what do you need to add?

Interactive features.

#### 4. What are the three questions you can ask to determine if something is state?

- Does it remain unchanged over time? If so, it isn’t state.
- Is it passed in from a parent via props? If so, it isn’t state.
- Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!


#### 5. How can you identify where state needs to live?
Identify every component that renders something based on that state.
Find their closest common parent component—a component above them all in the hierarchy.
Decide where the state should live: Often, you can put the state directly into their common parent. You can also put the state into some component above their common parent. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.


Higher-Order Functions

#### 1. What is a “higher-order function”?

Higher order functions are functions that can be passed around as arguments to other functions, returned as values from other functions, and assigned to variables. 

#### 2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

The function takes a single parameter n and compares if m is greater than n. 

#### 3. Explain how either map or reduce operates, with regards to higher-order functions.

Both map and reduce are higher-order functions because they take other functions (callbacks) as arguments:
In map, the callback function passed as an argument is applied to each element of the array.
In reduce, the callback function provided is used to accumulate values.

# Things I want to know more about
