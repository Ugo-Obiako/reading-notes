# Read 04: React and Forms

#### 1. What is a ‘Controlled Component’?

Controlled component refers to a component whose state is controlled and managed by React. In a controlled component, The value of the input field is stored in the component's state.

#### 2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

Whether to store user responses in the component state immediately upon entry or wait until they submit the form depends on the specific requirements of the application and the user experience you want to deliver. Both options are possible. Storing responses immediately allows for real-time updates of the state as the user interacts with the form and can be used for immediate feedback and live validation. When data integrity is of high concern, delaying state update until submission reduces the chances of storing incomplete or incorrect data.

#### 3. How do we target what the user is entering if we have an event handler on an input field?

What the user is entering can be targeted by using the event object which is passed to the event handler function. The event object contains information about the event, including the value of the input field.

# The Conditional (Ternary) Operator Explained

#### 1. Why would we use a ternary operator?

Ternary operators can make code more concise.

#### 2. Rewrite the following statement using a ternary statement:

>if(x===y){
>
>   console.log(true);
>
>} else {
>
>   console.log(false);
>
>}

Ternary statement:

x === y ? (console.log(true)) : (console.log(false))

# Things I want to know more about