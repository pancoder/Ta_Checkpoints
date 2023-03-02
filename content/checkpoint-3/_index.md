---
title: "Checkpoint Three"
date: 2021-10-01T09:28:27-05:00
draft: false
hidden: false
weight: 110
---


## This is Checkpoint 3 title 
here is top## Classes

### Classes
{{% notice orange "Question to Learner" %}}
What are classes?

How are they used?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
A general structure for creating objects

`Textbook Answer:`
[Classes](https://education.launchcode.org/intro-to-professional-web-dev/chapters/classes/index.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: What are classes? How are they used?

`Answer`: A general structure for creating objects
{{% /notice %}}



### Class Constructors
{{% notice orange "Question to Learner" %}}
Tell me what a constructor is?
What it does it do?
Where dose it go?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
A constructor is directions for how to create objects or values in a class. This is done by using a constructor method that takes in a value as a parameter and then in the body of the function makes the passed in value equal to the variable the programer decides to use, In most cases the 'this." is used to refer to the instance of the object itself.   Constructors are built in the class object. 

`Textbook Answer:`
[Constructors](https://education.launchcode.org/intro-to-professional-web-dev/chapters/classes/index.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: Tell me what a constructor is?
What it does it do?
Where dose it go?

`Answer`: A constructor is directions for how to create objects or values in a class. This is done by using a constructor method that takes in a value as a parameter and then in the body of the function makes the passed in value equal to the variable the programer decides to use, In most cases the 'this." is used to refer to the instance of the object itself.   Constructors are built in the class object. 
{{% /notice %}}


### Classes Constructors 2
{{% notice orange "Question to Learner" %}}
How would you declare a constructor method?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript 
 constructor(arguments) { //logic }
```
This is done by using a constructor method that takes in a value as a parameter and then in the body of the function makes the passed in value equal to the variable the programer decides to use, In most cases the 'this." is used to refer to the instance of the object itself.

`Textbook Answer:`
[Constructors](https://education.launchcode.org/intro-to-professional-web-dev/chapters/classes/index.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: How would you declare a constructor method?

`Answer`:
```JavaScript
  constructor(arguments) { //logic }
```
This is done by using a constructor method that takes in a value as a parameter and then in the body of the function makes the passed in value equal to the variable the programer decides to use, In most cases the 'this." is used to refer to the instance of the object itself. 
{{% /notice %}}



### Classes Methods
{{% notice orange "Question to Learner" %}}
How would you declare a method on a Class?

{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
function myMethod(arguments) { //logic }
```

`Textbook Answer:`
[Class Methods]((https://education.launchcode.org/intro-to-professional-web-dev/chapters/classes/index.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: How would you declare a method on a Class?

`Answer`:
 ```JavaScript
function myMethod(arguments) { //logic }
```
{{% /notice %}}


### Class Methods (outside constructors)
{{% notice orange "Question to Learner" %}}
How would you declare a method outside a class?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
class Dog { constructor (parameters) { //assign properties with this.key = value } methodName (parameters) { //function code } }```

`Textbook Answer:`
[Classes](https://education.launchcode.org/intro-to-professional-web-dev/chapters/classes/index.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: How would you declare a method outside a class?

`Answer`: A general structure for creating objects
{{% /notice %}}



### Class Methods (inside constructor)
{{% notice orange "Question to Learner" %}}
How would you declare a method inside the class?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
class Dog { constructor (parameters) { this.methodName = function (parameters) { //code within function goes here} }
```
`Textbook Answer:`
[Classes](https://education.launchcode.org/intro-to-professional-web-dev/chapters/classes/index.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
`Question`: How would you declare a method inside the class?

`Answer`:
```JavaScript
 class Dog { constructor (parameters) { this.methodName = function (parameters) { //code within function goes here} }```

{{% /notice %}}


### Classes (properties)
{{% notice orange "Question to Learner" %}}
How would you create properties for a class?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
class Dog { constructor (name, breed, color) {this.name = name; this.breed = breed; this.color = color;
```

`Textbook Answer:`
[Classes](https://education.launchcode.org/intro-to-professional-web-dev/chapters/classes/index.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
How would you create properties for a class?

`Answer`: 
```JavaScript
class Dog { constructor (name, breed, color) {this.name = name; this.breed = breed; this.color = color;
```
{{% /notice %}}


### TDD 1
{{% notice orange "Question to Learner" %}}
How do I find tests in a project package? Where is it located and how do you know it is a test file?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
I look in the spec file. Each file has ---.spec.js

`Textbook Answer:`
[TDD](https://education.launchcode.org/intro-to-professional-web-dev/chapters/unit-testing/tdd.html#test-code-cycle)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
How do I find tests in a project package? Where is it located and how do you know it is a test file?

`Answer`: 
I look in the spec file. Each file has ---.spec.js
{{% /notice %}}



### TDD 2
{{% notice orange "Question to Learner" %}}
What does TDD stand for?  What is the procedure to TDD
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Test Driven Development, The procedure is to write the test that expects a specific outcome and has a way of catching or throwing an error if that outcome is not met. 

`Textbook Answer:`
[TDD](https://education.launchcode.org/intro-to-professional-web-dev/chapters/unit-testing/tdd.html#test-code-cycle)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
What does TDD stand for?  What is the procedure to TDD

`Answer`: 
Test Driven Development, The procedure is to write the test that expects a specific outcome and has a way of catching or throwing an error if that outcome is not met. 
{{% /notice %}}






### TDD 3
{{% notice orange "Question to Learner" %}}
What is the syntax for creating a test? 
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
it("descriptive string of what this test does")function() { expect(function(){new Command();}).toThrow(new Error('Error message")). ```

`Textbook Answer:`
[TDD](https://education.launchcode.org/intro-to-professional-web-dev/chapters/unit-testing/tdd.html#test-code-cycle)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
What is the syntax for creating a test? 

`Answer`: 
```JavaScript
it("descriptive string of what this test does")function() { expect(function(){new Command();}).toThrow(new Error('Error message")). ```
{{% /notice %}} 


### TDD 4
{{% notice orange "Question to Learner" %}}
How many nested function or methods are in the  it  test?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
5, it(), function (), expect(), function() , .toThrow() ```

`Textbook Answer:`
[TDD](https://education.launchcode.org/intro-to-professional-web-dev/chapters/unit-testing/tdd.html#test-code-cycle)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
How many nested function or methods are in the  it  test?

`Answer`: 
```JavaScript
5, it(), function (), expect(), function() , .toThrow() ```
{{% /notice %}}


### TDD 5
{{% notice orange "Question to Learner" %}}
The test you write is supposed to check if an object is created properly. When we run a test where is the instance of a new class object created?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
it creates an instance of the object inside of the test itself. 

`Textbook Answer:`
[TDD](https://education.launchcode.org/intro-to-professional-web-dev/chapters/unit-testing/tdd.html#test-code-cycle)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
The test you write is supposed to check if an object is created properly. When we run a test where is the instance of a new class object created?

`Answer`: 
it creates an instance of the object inside of the test itself. 
{{% /notice %}}



### Classes (inheritance)
{{% notice orange "Question to Learner" %}}
How would you create a parent class?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
Parent Class  = Animal Properties: name, behavior Methods: .incrementBehavior() Child Class  = Dog Properties: name, behavior Methods: .incremementBehavior Child Class - Cat Properties: name, behavior, usesLitter Methods: .incrementBehavior()
```
`Textbook Answer:`
[Inheritance](https://education.launchcode.org/intro-to-professional-web-dev/chapters/classes/inheritance.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
How would you create a parent class?

`Answer`: 
```JavaScript
Parent Class  = Animal Properties: name, behavior Methods: .incrementBehavior() Child Class  = Dog Properties: name, behavior Methods: .incremementBehavior Child Class - Cat Properties: name, behavior, usesLitter Methods: .incrementBehavior()
```
{{% /notice %}}




### Extends
{{% notice orange "Question to Learner" %}}
How would you create a child class? 
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Your child class extends the parent class. This is the syntax difference between child vs parent. Child classes also have a super () constructor in order to pull the properties from the parent class. 
```JavaScript
 class Cat extends Animal {constructor ( ) { super ( ); //code properties here  }
```
`Textbook Answer:`
[Inheritance](https://education.launchcode.org/intro-to-professional-web-dev/chapters/classes/inheritance.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
How would you create a child class? 

`Answer`: 
Your child class extends the parent class. This is the syntax difference between child vs parent. Child classes also have a super () constructor in order to pull the properties from the parent class. 
```JavaScript
 class Cat extends Animal {constructor ( ) { super ( ); //code properties here  }
```
{{% /notice %}}


### Unit Tests
{{% notice orange "Question to Learner" %}}
How do you write a unit test using a unit-testing framework [Jasmine]? Explain how unit tests can assist with regression.
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
How do you write a unit test using a unit-testing framework [Jasmine]? Explain how unit tests can assist with regression.

`Textbook Answer:`
[Unit Testing]()

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
How do you write a unit test using a unit-testing framework [Jasmine]? Explain how unit tests can assist with regression.

`Answer`: 

{{% /notice %}}


### Setting-Up Jasmine
{{% notice orange "Question to Learner" %}}
Explain each line of code for installing the program Jasmine.
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
```JavaScript
const Jasmine = require('jasmine');
const jasmine = new Jasmine();

jasmine.loadConfig({
   spec_dir: 'spec',
   spec_files: [
      "**/*[sS]pec.js"
   ],
});

jasmine.execute();
```

`Textbook Answer:`
[Unit Testing](https://education.launchcode.org/intro-to-professional-web-dev/chapters/unit-testing/hello-jasmine.html)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
Explain each line of code for installing the program Jasmine.

`Answer`: 
```JavaScript
const Jasmine = require('jasmine');
const jasmine = new Jasmine();

jasmine.loadConfig({
   spec_dir: 'spec',
   spec_files: [
      "**/*[sS]pec.js"
   ],
});

jasmine.execute();
```
{{% /notice %}}


### Modules
{{% notice orange "Question to Learner" %}}
What is a module and how do you use it?  What does it do? How do you include it into your project?  
{{% /notice %}}

{{% notice blue "Expected Answer" %}}


`Textbook Answer:`
[Modules]()

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
What is a module and how do you use it?  What does it do? How do you include it into your project?  

`Answer`: 

{{% /notice %}}



### Scope
{{% notice orange "Question to Learner" %}}
What does scope mean?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Scope is the reach of information through project files


`Textbook Answer:`
[Unit Testing]()

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
What does scope mean?

`Answer`: 

{{% /notice %}}


### Test Reporting
{{% notice orange "Question to Learner" %}}

{{% /notice %}}

{{% notice blue "Expected Answer" %}}


`Textbook Answer:`
[Extends]()

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}


`Answer`: 

{{% /notice %}}



### Debugging
{{% notice orange "Question to Learner" %}}
What is your debugging strategies?  Where do you look for information?  How do you know where the issue is?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Learners at this point should have at least two solid debugging strategies. including reading the error, and commenting out code to see what happens, and/ or tracking where information begins and where it changes

`Textbook Answer:`
[Debugging](https://education.launchcode.org/intro-to-professional-web-dev/chapters/errors-and-debugging/debugging-logic-errors.html?highlight=debugging)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
What is your debugging strategies?  Where do you look for information?  How do you know where the issue is?

`Answer`: 
Learners at this point should have at least two solid debugging strategies. including reading the error, and commenting out code to see what happens, and/ or tracking where information begins and where it changes

{{% /notice %}}


### Jasmine
{{% notice orange "Question to Learner" %}}
What is Jasmine? and how do we use it?
{{% /notice %}}

{{% notice blue "Expected Answer" %}}
Jasmine is a unit testing framework used for unit testing our code. This  npm module that can be installed and used in a manner similar to readline-sync. 

`Textbook Answer:`
[Jasmine](https://education.launchcode.org/intro-to-professional-web-dev/chapters/unit-testing/hello-jasmine.html?highlight=jasmine)

`Video Reference` [)
{{% /notice %}}

{{% notice green "Mastery Question" %}}
What is Jasmine? and how do we use it?

`Answer`: 
Jasmine is a unit testing framework used for unit testing our code. This  npm module that can be installed and used in a manner similar to readline-sync. 

{{% /notice %}}
