# Readings: In memory storage

# Understanding the JavaScript Call Stack

#### 1. What is a ‘call’?

A call refers to the act of invoking a function or method. When you "call" a function or method, you're instructing the program to execute the code within that function or method. 

#### 2. How many ‘calls’ can happen at once?

It depends on the type of broser. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

#### 3. What does LIFO mean?

Last In, First Out.

#### 4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![call stack](/images/call-stack.PNG)

The image above is a stack of 3 functions. When a function finishes its execution (returns), its frame is removed from the top of the stack, and the program returns to the previous function in the stack. This continues until the stack is empty, indicating that the program has finished executing all functions. Call stacks follow the last in, first out data structure principle. In the above example, function A entered the call stack first, but it is the last function to be returned. 

#### 5. What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser has a maximum stack call that it can accomodate before throwing a stack error.

# JavaScript error messages

#### 1. What is a ‘reference error’?

Reference error occurs when you try to use a variable that is not yet declared.

#### 2. What is a ‘syntax error’?

Syntax errors are caused by errors in programming syntax.

#### 3. What is a ‘range error’?

Range errors occur when you try to manipulate an object with some kind of length and give it an invalid length.

#### 4. What is a ‘type error’?

Type errors occur when incompatible data types are used e.g strings, numbers, etc. 

#### 5. What is a breakpoint?

When you set a breakpoint in your code, the debugger interrupts the execution of the program at that specific line (breakpoint), giving you an opportunity to examine the code.

#### 6. What does the word ‘debugger’ do in your code?

A debugger is a tool or software utility that assists developers to analyze code, identify issues and fix errors or bugs in the code. 

# Things I want to know more about
