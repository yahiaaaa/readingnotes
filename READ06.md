



# Understanding The Problem Domain Is The Hardest Part Of Programming



![alt text](https://www.skipprichard.com/wp-content/uploads/2019/06/bigstock-Problem-Solution-Concept-The-286309309.jpg "title")



** What is the hardest thing about writing code? **


There are many common answers to this question:


Learning a new technology
Naming things
Testing your code
Debugging
Fixing bugs
Making software maintainable


** Why problem domains are hard **


Have you ever tried to put together a jigsaw puzzle that didn’t have any picture on it? How about one like this one, that has a very similar pattern repeated on it and is double-sided?


hard puzzle problem domain


The reason why puzzles like this one are so hard, is because you can’t really see what you are trying to build very clearly. Normally when you put together a jigsaw puzzle you follow steps that might look something like this:



1- Figure out what the major components of the picture are


2- Sort the pieces by color or component
3- Put together all the border pieces


4- Put together each component of the picture from the piles you created


This all breaks down when you don’t have a picture with clear components that you can identify.


__ What can you do about it?__


If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:


Make the problem domain easier
Get better at understanding the problem domain
You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.


# JavaScript


** CALLING FUNICTION **


The call() method is a predefined JavaScript method. It can be used to invoke (call) a method with an owner object as an argument (parameter). With call() , an object can use a method belonging to another object



const myObject = {


firstName:"John",


lastName: "Doe",


fullName: function () {


return this.firstName + " " + this.lastName;
}


}


// This will return "John Doe":


myObject.fullName();


## getting MULTIPLE value out of function in javascript


function getSize (width, height, depth) {


var area = width * height;


}


var volume = width * height * depth;


var sizes= [area , volume];


return sizes;


var areaOne = getSize (3, 2, 3)[0];


var volumeOne = getSize (3, 2, 3)[1];


__ FUNCTION DECLARATION __


A function declaration creates a function that you
can call later in your code. It is the type of function
you have seen so far in this book.


function area (width, height)


return width * height;


};


var size= area (3, 4) ;


__ FUNCTION EXPRESSION __


var ar ea = f unction
(width, height) {


r eturn width * height;


} ;


var size = area (3, 4) ;


# WHILE LOOPS


The Do While Loop
The do while loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.


while (condition) {
// code block to be
executed


}


The key difference between
a whi 1 e loop and a do whi 1 e
loop is that the statements in
the code block come before the
condition. This means that those
statements are run once whether
or not the condition is met.
If you take a look at the
condition, it is checking that the
value of the variable called i is
less than 1, but that variable has
already been set to a value of 1.
Therefore, in this example the
result is that the 5 times table is
written out once, even though
the counter is not less than 1.
Some people like to write while
on a separate line from the
closing curly brace before it.




var table = 3;


var operator= 'addition';


var i = 1;


var msg = ' ' ;


if (operator=== 'addition')


whi l e (i < 11) {


msg += i + ' + ' + table +


'
i++;


}


else {


while ( i < 11) {


msg += i + ' x ' + table +
'


i++;


II Unit of table


II Type of calculation (defaults to addition)


II Set counter to 1


II Message


II If the operator
variable says addition


II While counter is less than 11


= ' + (i +table)+ '<br I>';
II Calculation


II Add 1 to the counter


II Otherwise


II Whi le counter is less than 11


= ' + (i *table) + '<br I>
';


II Calculation


II Add 1 to the counter


II Write the message into the page


var el = document.getElementByid{'bl ackboard');


el .innerHTML = msg;


#### Objects and properties


A JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation.


# The DOM
![alt text](https://i.ytimg.com/vi/RbQGn6vBlys/maxresdefault.jpg "title")
Introduction to the DOM


The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web. In this guide, we’ll briefly introduce the DOM. We’ll look at how the DOM represents an HTML or XML document in memory and how you use APIs to create web content and applications.


What is the DOM?


The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page.




