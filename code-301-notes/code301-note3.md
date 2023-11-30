# Read 03: Passing Functions as Props

#### 1. What does .map() return?

The `map()` method is used to iterate over an array and create a new array by applying a function to each element of the original array. 

#### 2. If I want to loop through an array and display each value in JSX, how do I do that in React?

By using the `map()` method.

#### 3. Each list item needs a unique ____.

Key

#### 4. What is the purpose of a key?

A key uniquely identifies each item in an array.

# The Spread Operator

#### 1. What is the spread operator?

The spread operator allows an iterable (such as an array, string, or object) to be expanded or spread into individual elements.

#### 2. List 4 things that the spread operator can do.

- Copying arrays
- Concatenating arrays
- Adding elements to arrays
- Spread in array literlas, object literals and function calls

#### 3. Give an example of using the spread operator to combine two arrays.

let arr1 = [a, b, c];
const arr2 = [d, g, h];

arr1 = [...arr1, ...arr2];
// arr1 is now [a, b, c, d, g, h]


#### 4. Give an example of using the spread operator to add a new item to an array.

const isSummer = true;
const fruits = ["apple", "banana", ...(isSummer ? ["watermelon"] : [])];
// ['apple', 'banana', 'watermelon']


#### 5. Give an example of using the spread operator to combine two objects into one.

const obj1 = { a: "bar", x: 22 };
const obj2 = { b: "bar2", y: 15 };

const ObjCombined = { ...obj1, ...obj2 };
// { a: "bar", x: 22, b: "bar2", y: 15 }


# How to Pass Functions Between Components

#### 1. In the video, what is the first step that the developer does to pass functions between components?

The first step is to define the function in the parent or higher-level component, and then pass it down to the child or lower-level component as a prop or parameter.

#### 2. In your own words, what does the handleClick function do?

handleClick function is the callback or event handler function which allows you to define the actions that will occur as a result of an event. 

#### 3. How can you pass a method from a parent component into a child component?

Through props.

#### 4. How does the child component invoke a method that was passed to it from a parent component?

By calling the function.

# Things I want to know more about
