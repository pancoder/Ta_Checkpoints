---
title: "Checkpoint One"
date: 2021-10-01T09:28:27-05:00
draft: false
weight: 100
hidden: false
---

## How to Store Data and Information

### Primitive variables
{{% notice orange "Question to Learner" %}}
Can you declare a variable?

Why do programmers do this?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
let name = Pan;
```

`Textbook Answer:`
[Data and Variables](https://education.launchcode.org/intro-to-professional-web-dev/chapters/data-and-variables/index.html)

`Video Reference` [Youtube Video Link at 56 seconds](https://www.youtube.com/watch?v=GqC82jZyCi8)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Explain how you would save and store an age of a cat.

`Answer`: A variable is a name that refers to a value
{{% /notice %}}


## Arrays 
{{% notice orange "Question to Learner" %}}
Can you declare an Array?

What is an index in an Array?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
let names = [];
```
`Textbook Answer:`
[Arrays](https://education.launchcode.org/intro-to-professional-web-dev/chapters/arrays/index.html)

`Arrays Video Reference` [Youtube Video Link at 1:32 seconds](https://www.youtube.com/watch?v=GqC82jZyCi8)
`Array Indexs Video Reference` [Youtube Video Link at 8:12 seconds](https://www.youtube.com/watch?v=GqC82jZyCi8)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Show me how to store/retrieve data with an array?

`Answer`: Once an Array is declared, use index value. 
```JavaScript
let dog = [Johnny, Barker];
console.log(dog[1]);
```
{{% /notice %}}


### Data types
{{% notice orange "Question to Learner" %}}
What does data type mean and why does it matter?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Programmers need to know what data types are so they 
know how to manipulate data. strings vs. Numbers etc

`Textbook Answer:`
[Data Types](https://education.launchcode.org/intro-to-professional-web-dev/chapters/data-and-variables/values-and-data-types.html)

`Video Reference` [Youtube Video Link at 2:03 seconds](https://www.youtube.com/watch?v=GqC82jZyCi8)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Show and Tell me what will happen with this code and why:
```JavaScript
let num = "1"; 
let num2 = 2; 
let newNum = num + num2;
```

`Answer`: The example code will generate an error because num is a string type and num2 is an int type.
{{% /notice %}}


### Functions
{{% notice orange "Question to Learner" %}}
Can you show me how to make a function?
What are the parts you need?
Can you explain what each part does?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Learner should remember that they need the word
function' and () and {}, and explain what each item does.  Minimum expectation
```JavaScript
function () {};
```
`Textbook Answer:`
[Functions](https://education.launchcode.org/intro-to-professional-web-dev/chapters/functions/creating-functions.html)

`Video Reference` [Youtube Video Link at 1:03 seconds](https://www.youtube.com/watch?v=GqC82jZyCi8)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Create a function and explain to me what you are doing in detail.

`Answer`: A function is a way to package instructions. I can declare the function with the word "function" There is an area marked with ( ) to allow me to pass in stuff if I need to, and { } denotes the body of the function. 
```JavaScript
let shelf = [apple, pear, peach];

let function countPies(shelf){
	numOfPies = shelf.length;
	return numOfPies;
}

console.log(countPies(shelf));
```
{{% /notice %}}


### Objects (covered in class 7)
{{% notice orange "Question to Learner" %}}
Can you tell me how to declare an object?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Learner should remember the syntax for how to create Objects
```JavaScript
let dogs = {name: Pepper; age: 14; breed: schnoodle};
```
`Textbook Answer:`
[Arrays](https://education.launchcode.org/intro-to-professional-web-dev/chapters/objects-and-math/background.html)

`Video Reference` [Youtube Video Link at 56:44 seconds](https://www.youtube.com/watch?v=G1YI0IFZF4g)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Create an object that holds information about a person?

`Answer`: 
```JavaScript
let person = {name: Peter; age: 14; sport: soccer};
console.log(person);
```
{{% /notice %}}


### Dot access operator
{{% notice orange "Question to Learner" %}}
What does the . (dot) mean when you see it?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
The dot is needed to access data with in an object.
 All things in JS are objects and therefore the dot can
 access data as well as special methods within a class.
```JavaScript
let dogs = {name: Pepper; age: 14; breed: schnoodle};
let theDogsName = dogs.name;
theDogsName = Pepper;

```
`Textbook Answer:`
[Dot Access Operator](https://education.launchcode.org/intro-to-professional-web-dev/chapters/strings/strings-as-objects.html?highlight=dot%20accesses%20operator)

`Video Reference` [Youtube Video Link at 7:48 seconds](https://www.youtube.com/watch?v=G1YI0IFZF4g)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Create an object about a person and explain to me how I can access data. 

`Answer`:
```JavaScript
let person = {name: Peter; age: 14; sport: soccer};

```
{{% /notice %}}


### How JS stores data
{{% notice orange "Question to Learner" %}}
How are the ways that JS stores data similar to each other?  
 How are ways JS manipulates data different to each other?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
All the methods (topic 1-5) variables, arrays, objects, functions
 holds data and allows me to access it. They differ in 3 ways,
 how the data is stored, ie structure, how to get that data out,
 and how I can manipulate that data?


`Video Reference` [Youtube Video Link at 1:32 seconds](https://www.youtube.com/watch?v=GqC82jZyCi8)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Create a variable ,an array, an object, and a function that all have the same return value.

`Answer`:
```JavaScript
let meal = "Meatloaf";

let mealArray = [Meatloaf, Pizza];

let mealObject = {firstMeal: Meatloaf; secondMeal: Pizza};

let food = "Meat";

let function mealMethod(food){
	let mix = food +'loaf';
}return mix; 

```
{{% /notice %}}

### How JS manipulates data
{{% notice orange "Question to Learner" %}}
How can you change the value of a string datatype using console.log()?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
You can concatenate two things together.
```JavaScript
console.log('Happy' + 'Birthday');
```
`Textbook Answer:`
[Manupulating Data](https://education.launchcode.org/intro-to-professional-web-dev/chapters/data-and-variables/variables.html)

`Video Reference` [Youtube Video Link at 4:09 seconds](https://www.youtube.com/watch?v=GqC82jZyCi8)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Show how to change the value of a string variable with the result showing on console.

`Answer`:
```JavaScript
let holiday = ["Birthday", "Easter"];
console.log('Happy' + holiday[2])

```
{{% /notice %}}

### How JS manipulates object data
{{% notice orange "Question to Learner" %}}
How do you change or access the value in an object?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
let dogOne = { breed: "pug", name: "Buddy"};
dogOne.name = "Charlie"; 
```
`Textbook Answer:`
[Manupulating Object Data](https://education.launchcode.org/intro-to-professional-web-dev/chapters/objects-and-math/codingwithobjects.html)

`Video Reference` [Youtube Video Link at 56:44 seconds](https://www.youtube.com/watch?v=G1YI0IFZF4g)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Create an object of an animal with four properties, add values to those properties with user input. 

`Answer`:
```JavaScript
let readlineSync= require('readline-sync');
let input = readlineSync.question(Enter a new animal name: );

let animal = {name: Archer; age: 8; type: canine; breed: Labrador}

animal.name = input;

console.log(animal.name);
```
{{% /notice %}}


### How JS manipulates data with functions
{{% notice orange "Question to Learner" %}}
How do you pass a value into a function and then get a value out of a function?  
How do you decide when a function needs to return a value?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Use "return" to get a value out of a function. Not all functions need return values.
You decide to use a return value if you need a data result out of the 
function, typically to bring it into another function.
```JavaScript
function addNumbers (num){ 
let total = num + num; 
return total} 
;
```
`Textbook Answer:`
[Manupulating Data with Functions](https://education.launchcode.org/intro-to-professional-web-dev/chapters/functions/function-input-and-output.html)

`Video Reference` [Youtube Video Link at 40:00 seconds](https://www.youtube.com/watch?v=G1YI0IFZF4g)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Write a function that takes in a number to add to another number. 
Have that function return the value of the sum of those numbers, console log 
the result of that function.

`Answer`:
```JavaScript
let num = 2;

function addNumbers(num){ 
let total = num + num; 
return total}
;

console.log(addNumbers(num));
```
{{% /notice %}}

 
### Console.log()
{{% notice orange "Question to Learner" %}}
1. Knowing what you know about functions and dot accessors, Can you 
break down how console.log() works?  

2. How would I print out the value of a function with a return?  

3. How do I print out an element in position 2 in an array?  `
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Console is an object with a method that is accessed by the dot. I know that log is a function/ or method because it is followed by ( ). The log method is designed to show information on a console display. The ( ) is where I enter the parameters required for log method to run.  I can put a any data type, data storage structure ( primitive variables, arrays, objects, or functions with return values)

`Textbook Answer:`
[Console.log()](https://education.launchcode.org/intro-to-professional-web-dev/chapters/how-programs-work/hello-world.html?highlight=console%20log)

`Video Reference` [Youtube Video Link at 40:00 seconds](https://www.youtube.com/watch?v=G1YI0IFZF4g)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Decribe as if to a total noob: How does this code work?   Can you spot the error?

`Answer`:
```JavaScript
let pie = "rubarb";
  
function taste(pie){ 
	if ( pie == 'strawberry') return "yuck!";   
	if (pie == " rubarb" ) return "yum!"};   
	console.log (taste);
}
```
{{% /notice %}}


### Getting user input
{{% notice orange "Question to Learner" %}}
1.How do you get user input?  
2. Given what you know about functions, variables, and assigning 
values can you break down how this code works?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
const is a declaration type to create a variable with a permanent value. input is the name of the variable. the = means input is equal or assigned the value of what comes after. require() is a method that instructs JS to bring in some functionality, in this case we give it the parameter of 'readline-sync' which gives JS the instruction to give the user a cursor and to save into my variable 'input'  whatever value a user entered. 
```JavaScript
const input = require('readline-sync'); 
let info = input.question("What is your name."); 
```
`Textbook Answer:`
[Getting User Input](https://education.launchcode.org/intro-to-professional-web-dev/chapters/data-and-variables/input.html)

`Video Reference` [Youtube Video Link at 00:55 seconds](https://www.youtube.com/watch?v=G1YI0IFZF4g)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Why do we need to set the require into a variable?

`Answer`: By making the require method equal to a value we can now use thd dot access operator to utilize its properties.
```JavaScript
let input= require('readline-sync');
```
{{% /notice %}}
