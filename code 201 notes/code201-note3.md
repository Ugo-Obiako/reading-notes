# Read 03: HTML Lists, Control Flow with JS, and the CSS Box Model

Flow control is important in software engineering because it determines the order in which individual statements, instructions or function calls of a program are executed or evaluated.

#### 1. When should you use an unordered list in your HTML document?
Unordered list is used when the order of the list items is not necessary.

#### 2. How do you change the bullet style of unordered list items?
By using the CSS list-style-type property.

#### 3. When should you use an ordered list vs an unorder list in your HTML document?
Unordered list is used when the order of the list items is not necessary, but ordered list
when the order of the list items is meaningful. For example:

- Steps in a recipe
- Turn-by-turn directions
    
#### 4. Describe two ways you can change the numbers on list items provided by an ordered list?

- By using the start attribute of the `<ol>` tag.
- Custom CSS Styles e.g list-style-type, list-style-image, and list-style-position can be used to control how the numbers or markers appear.

# The Box Model

#### 1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements. The padding sits around the content as white space

#### 2. List and describe the four parts of an HTML elements box as referred to by the box model.

Content box: The area where your content is displayed.

Padding box: The padding sits around the content as white space.

Border box: The border box wraps the content and any padding.

Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements.

# Arrays. Operators and Expressions. Conditionals. Loops.

#### 1. What data types can you store inside of an Array?

Strings, numbers, objects, and even other arrays.

#### 2. Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?

`const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`

`people` is a valid array. You can access individual items in the array using bracket notation and supplying the item's index. For a multidimensional array, you can access an item inside an array that is itself inside another array by chaining two sets of square brackets together.

#### 3. List five shorthand operators for assignment in javascript and describe what they do.

Assignment: x = f(); Meaning: x = f()

Addition Assignment: x += f(); Meaning: x = x + f()

Subtraction assignment: x -= f(); Meaning: x = x - f()

Multiplication assignment: x *= f(); Meaning: x = x * f()

Division assignment: x /= f(); Meaning: x = x / f()

#### 4.  Read the code below and evaluate the last expression and explain what the result would be and why.

> let a = 10;
>
> let b = 'dog';
>
> let c = false;
>
> // evaluate this
>
>(a + c) + b;

- JavaScript will perform type coercion and treat c (a boolean) as 0 when used in a numeric context. (a + c) becomes 10 + 0, which equals 10 (a number).

- JavaScript converts the number 10 to a string. 10 is then concatenated with the string 'dog', resulting in the string '10dog'.

#### 5.  Describe a real world example of when a conditional statement should be used in a JavaScript program.

A conditional statement can be used when making a decision between two alternatives. 

#### 6.  Give an example of when a Loop is useful in JavaScript.

A loop can be used for performing repetitive tasks as long as a certain condition remains valid. The loop stops when the condition is no longer valid.

# Things I want to know more about:
