# Error Handling & Debugging

**In this chapter you will learn about: **
*THE CONSOLE & 
DEV TOOLS 
*COMMON 
PROBLEMS
*HANDLING 
ERRORS

### A stack 

![alt text](https://www.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-Stack-Push-Operations.png "title")


A stack is a data structure that has way more limitations, compared to arrays.

We can add items to a stack only by adding them on top. And we can only remove the item on top of the stack.

var stack = [];

stack.push(2);       // stack is now [2]

stack.push(5);       // stack is now [2, 5]

var i = stack.pop(); // stack is now [2]

alert(i);            // displays 5


var queue = [];

queue.push(2);         // queue is now [2]

queue.push(5);         // queue is now [2, 5]

var i = queue.shift(); // queue is now [5]

alert(i);              // displays 2


**VARIABLE SCOPE**

* GLOBAL SCOPE
If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.

- FUNCTION-LEVEL SCOPE
When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

Examples

let x = 10; 

function timesTen(a){ 

    return a * 10;
}

let y = timesTen(x);

console.log(y); // 100

First, assign 10 to the x variable.
Second, declare a function timesTen() that multiplies its argument with 10.
Third, call the timesTen() function by passing in x as a parameter and store the return value in the variable y. Finally, output the variable y to the Console

### ERROR OBJECTS

properties of error object

PROPERTY	DESCRIPTION
name	Type of execution
message	Description
fileNumber	Name of the JavaScript file
lineNumber	Line number of error

**How to deal with the errors ?**

Debugging - it is all about deduction; eliminating potential causes of an error.
JavaScript console can help while debugging errors.

Breakpoints can pause the execution of a script on any line. You can use it to check the values stored in variables at that point in time. If you set mul
tiple breakpoints, you can step through them one-by-one to see where values change and a problem might occur.


