# call stack and debuging 

## call stack 

At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).(2)

The call stack is used by JavaScript to keep track of multiple function calls. It is like a real stack in data structures where data can be pushed and popped and follows the Last In First Out (LIFO) principle. We use call stack for memorizing which function is running right now.(1)

The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.(2)

###  stack overflow problem 

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser or (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.(2)

## javascript error message 

The first thing that indicates you that something is wrong with your code is the (in)famous error message that the one we saw just moments ago, it usually appears on your console (being developer tools of the browser, terminal or whatever else you are using).(3)

### Types of error messages

1. Reference errors

2. Syntax errors

3. Range errors

4. Type errors

### Debugging

The most common way its to simply console.log() the variables you want to check .

## Referennces

1. https://www.geeksforgeeks.org/what-is-the-call-stack-in-javascript/

2. https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/

3. https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c