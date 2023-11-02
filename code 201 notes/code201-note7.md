# Read 07: Object-Oriented Programming, HTML Tables

Object-Oriented Programming promotes the creation of modular code by encapsulating related data and functions into objects. This modularity makes it easier to understand, maintain, and extend the code.

#### 1. Explain why we need domain modeling.

Domain models serve as valuable documentation for the system.

Domain modeling guides software design and architecture decisions. It helps in defining the structure and relationships between various components of the system.

Domain models facilitates communication. It makes it easier for developers to discuss and validate requirements.

# HTML Table Basics

#### 1. Why should tables not be used for page layouts?

1. Table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.

2. Layout tables reduce accessibility for visually impaired users.

3. Tables are not automatically responsive. Tables are sized according to their content by default and does not default to 100% of the width of their parent element container, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

#### 2. List and describe 3 different semantic HTML elements used in an HTML `<table>.`

`<tr>` element defines the table rows.

`<th>` element defines the table header.

`<td>` element defines the data cells of the HTML table.

# Introducing Constructors

#### 1. What is a constructor and what are some advantages to using it?

A constructor is a special function that is used to create and initialize objects. Constructors are used to define and create instances of user-defined object types. Constructors are typically called with the `new` keyword, which results in the creation of a new object based on the constructor's template.

__Adavantages of Constructors__

- Constructors can be used to create multiple instances of objects with the same structure and behavior.

- Constructors ensure consistency and make code more organized and readable.



#### 2. How does the term `this` differ when used in an object literal versus when used in a constructor?

In object literal, the term `this` refers to the object that is described by the object literal. However the term `this` in a constructor does not refer to particular object, but it refers to the any new object created by the constructor.

# Object Prototypes Using A Constructor

#### Explain prototypes and inheritance via an analogy from your previous work experience. NOTE: This is a very common front end developer interview question.

Prototypes and inheritance are used to create new objects that inherit common properties and methods from existing prototypes while allowing for customization and extension as needed. This is a powerful concept that enables code reusability, modularity, and object-oriented programming in JavaScript, similar to how books in a library share common information while having their unique content.