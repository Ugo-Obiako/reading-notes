# Read 09: Forms and JS Events

Events are occurrences that take place in a web page which are typically triggered by users' actions. Events allow you to define specific JavaScript code or other actions to be executed in response to these events.

#### 1. Why are forms so important in web development?

Forms allow users to enter data, which is generally sent to a web server for processing and storage or used on the client-side to immediately update the interface.

#### 2. When designing a form, what are some key things to keep in mind when it comes to user experience?

- Make the form as simple as possible by only including the essential fields.

- Use clear and concise labels for each input field to explain what's expected.

- Make input fields large enough to comfortably enter data. Use text areas for longer text.

- Ensure your form is accessible to all users, use appropriate HTML attributes and labels.

#### 3. List 5 form elements and explain their importance.

- Textarea: Textarea elements are used for collecting multi-line text data, such as comments, messages, and longer text entries.

- Text Input: Text input fields are fundamental for collecting single-line text data, such as names, email addresses, and search queries.

- Checkbox: Checkboxes are used to present users with multiple options, and users can select one or more options by checking the corresponding checkboxes.

- Email Input: Email input fields are designed for collecting email addresses and can provide email validation.

- Submit Button: They are essential for allowing users to submit their form data for processing. 


# Introduction To Events.

#### 1. How would you describe events to a non-technical friend?

An event is an action or occurrence that takes place in a web page, typically triggered by a user's interaction with the page. Events allow you to 

define specific JavaScript code (or other actions) to be executed in response to these events, making the web page dynamic and interactive.

#### 2. When using the addEventListener() method, what 2 arguments will you need to provide?

Event Type (String): This argument specifies the name of the event that you want to handle. Common event types include "click," "mouseover," "submit," "keydown," "change," etc.

Event Handler (Function): The second argument is a JavaScript function that will be executed when the specified event occurs.

#### 3. Describe the event object. Why is the target within the event object useful?

The event object is a JavaScript object that provides information and properties related to an event when an event listener is triggered. It is 

passed as a parameter to the event handler function when an event occurs.

One of the most important properties of the event object is event.target.

The event.target property allows you to identify the specific HTML element that initiated the event.

The event.target property allows you to manipulate the properties and attributes of the target element. For example, you can read the value of an input field, change its style, or update its content in response to an event.

#### 4. What is the difference between event bubbling and event capturing?

In event bubbling, the event starts from the target element that triggered the event and then "bubbles up" through its ancestor elements in the DOM hierarchy, from the innermost to the outermost. In event capturing the event is first captured by the outermost element (the root of the DOM tree) and then propagates down to the target element.

# Things I want to know more about