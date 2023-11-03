# Read 06: Problem Domain, Objects, and the DOM

#### 1. How would you describe an object to a non-technical friend you grew up with?

An object is a collection of related data and/or functionality

#### 2. What are some advantages to creating object literals?

Object literals can be used to store and transfer a series of structured, related data items.

#### 3. How do objects differ from arrays?

Objects are collections of key-value pairs, where each key is a unique string (or symbol) that maps to a value while Arrays are ordered collections of values, where each value is assigned an index starting from 0. 

Object data is accessed using the keys (strings or symbols) associated with the values while array data is accessed using the numerical index.

#### 4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.



#### 5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using this?

The `this` keyword refers to the current object the code is being written inside. `this` enables you to use the same method definition for every object you create.

>const dog = {
>
>  name: 'Spot',
>
>  age: 2,
>
>  color: 'white with black spots',
>
>  humanAge: function (){
>
>    console.log(`${this.name} is ${this.age*7} in human years`);
>
> }
>
>}

# Introduction To The DOM

#### 1. What is the DOM?

The Document Object Model (DOM) is a programming interface for web documents.

#### 2. Briefly describe the relationship between the DOM and JavaScript.

JavaScript is a scripting language that can be used to modify a web page (document) throught the Document Object Model (DOM).

# Things I want to know more about

