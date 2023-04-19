🚀 About this Repository

Welcome to our JavaScript Playbook, designed to help you learn JavaScript from scratch with easy-to-understand code snippets and examples. This repository is a collection of learning resources, including cheat sheets, code snippets, and helpful tips that will guide you through the basics and enhance your skills in JavaScript. As a front-end developer, I’ve compiled these resources to help me in my journey to master the language, and I’m sharing them with you. Let’s learn together!

If you have any feedback, suggestions, or contributions to improve this repository for beginners, please feel free to reach out to me. You can connect with me on LinkedIn or find me on GitHub using the links provided below. I’m always open to hearing from you and improving this resource together.
Happy learning!

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zeeshanmukhtar1/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ZeshanMukhtar01)
[![instagram](https://img.shields.io/badge/instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/zeshanmukhtar01/)

## Mastering the Basics of JavaScript

<details>
  <summary>Introduction to JavaScript</summary>
  <p>JavaScript is a programming language that is used for creating interactive websites and web applications. It is used to add interactivity, dynamic content, and user interface effects to web pages.</p>
</details>
<details>
<summary>What is a variable in JavaScript?</summary>
<p>A variable is a container for storing a value. In JavaScript, you can declare a variable using the <code>var</code>, <code>let</code>, or <code>const</code> keywords. For example:</p>

<pre><code>var message = “Hello, Zeeshan!”;
let count = 10;
const PI = 3.14;
</code></pre>
</details>
<details>
<summary>What are data types in JavaScript?</summary>
<p>JavaScript supports several data types, including:</p>
<ul>
<li><strong>Numbers</strong>: Used for storing numeric values, such as <code>1</code>, <code>2.5</code>, or <code>-10</code>.</li>
<li><strong>Strings</strong>: Used for storing text values, such as <code>“Hello, Zeeshan!”</code> or <code>“123”</code>.</li>
<li><strong>Booleans</strong>: Used for storing true/false values, such as <code>true</code> or <code>false</code>.</li>
<li><strong>Undefined</strong>: Used for uninitialized variables.</li>
<li><strong>Null</strong>: Used to represent a null or empty value.</li>
<li><strong>Objects</strong>: Used for storing complex data structures.</li>
<li><strong>Arrays</strong>: Used for storing lists of values.</li>
</ul>
</details>
<details>
    <summary>Type casting</summary>
    <p>Type casting in JavaScript is like changing a toy into a different toy. When we write code, we use things called variables to store information. Sometimes we need to change the type of information in a variable. For example, we might have a number that looks like text, and we want to change it into a real number we can do math with. This is called type casting. JavaScript has special tools called functions that can help us change the type of information in a variable. Type casting is important because it helps us work with different kinds of information in our code and avoid mistakes.</p>
    <code>
    let myString = "10"; // a string that represents a number
let myNumber = parseInt(myString); // convert string to integer

console.log(myNumber); // output: 10
</code>

</details>
<details>
<summary>What is a function in JavaScript?</summary>
<p>A function is a block of code that performs a specific task. It takes input in the form of arguments and returns output in the form of a return value. Functions allow you to reuse code, organize code into smaller, more manageable chunks, and make your code more modular and easier to understand.</p>

<p>Here is an example of a function that takes two arguments and returns their sum:</p>

<pre><code>function addNumbers(num1, num2) {
let sum = num1 + num2;
return sum;
}
</code></pre>

<p>You can call this function by passing in two numbers:</p>

<pre><code>let result = addNumbers(5, 10);
console.log(result); // Output: 15
</code></pre>

<p>In this example, the <code>addNumbers()</code> function takes two arguments, <code>num1</code> and <code>num2</code>, adds them together, and returns the sum.</p>
</details>
<details>
<summary>How do you declare a function in JavaScript?</summary>
<p>You can declare a function in JavaScript using the <code>function</code> keyword, followed by the function name and any parameters. For example:</p>

<pre><code>function sayHello(name) {
console.log("Hello, " + name + “!”);
}
</code></pre>

<p>You can then call the function by passing in any required arguments, like this:</p>

<pre><code>sayHello(Zeeshan);
// Output: “Hello, Zeeshan!”
</code></pre>
</details>
<details>
<summary>What is a conditional statement in JavaScript?</summary>
<p>A conditional statement allows you to execute different code depending on whether a certain condition is true or false. The most common conditional statement in JavaScript is the <code>if</code> statement. For example:</p>

<pre><code>let age = 18;

if (age >= 18) {
console.log(“You are an adult!”);
} else {
console.log(“You are not yet an adult.”);
}
</code></pre>

<p>In this example, the <code>if</code> statement checks whether the <code>age</code> variable is greater than or equal to <code>18</code>. If it is, the first code block is executed, and if not, the second code block is executed.</p>
</details>
<details>
<summary>JavaScript Operators</summary>
<p>Operators are symbols used in JavaScript to perform different types of operations on values or variables. Here are some common types of operators in JavaScript:</p>
<ul>
<li><strong>Assignment Operators:</strong> These operators are used to assign a value to a variable. For example, the “=” operator is used to assign a value to a variable, like this: <code>let x = 5;</code></li>
<li><strong>Arithmetic Operators:</strong> These operators are used to perform mathematical calculations on values. For example, the “+” operator is used to add two numbers together, like this: <code>let sum = 2 + 3;</code></li>
<li><strong>Comparison Operators:</strong> These operators are used to compare two values and return a boolean value (true or false). For example, the “==” operator is used to compare whether two values are equal, like this: <code>let x = 5; let y = 10; console.log(x == y); // outputs false</code></li>
<li><strong>Logical Operators:</strong> These operators are used to combine multiple conditions and return a boolean value. For example, the “&&” operator is used to check if both conditions are true, like this: <code>let x = 5; let y = 10; console.log(x < y && y > 8); // outputs true</code></li>
</ul>
<p>There are many more types of operators in JavaScript, but these are some of the most common.</p>
</details>
<details>
<summary>JavaScript Loops</summary>
<p>Loops are used in JavaScript to execute a block of code repeatedly until a certain condition is met. Here are some common types of loops in JavaScript:</p>
<ul>
<li><strong>For Loop:</strong> This loop is used to execute a block of code a specific number of times. For example: <code>for (let i = 0; i < 10; i++) { console.log(i); }</code></li>
<li><strong>While Loop:</strong> This loop is used to execute a block of code as long as a certain condition is true. For example: <code>let i = 0; while (i < 10) { console.log(i); i++; }</code></li>
<li><strong>Do-While Loop:</strong> This loop is similar to a while loop, but it will always execute the code inside the curly braces at least once, even if the condition is false. For example: <code>let i = 0; do { console.log(i); i++; } while (i < 10);</code></li>
</ul>
<p>Loops are a powerful tool in JavaScript and are essential for many types of programming tasks.</p>
</details>
<details>
  <summary>About Control flow of JavaScript</summary>
  <p>Imagine you are making a cake, and you have a recipe that tells you what ingredients to add and in what order.The recipe is like the control flow of your program. In JavaScript, the Control flow is a way of how your computer runs code from top to bottom. It starts from the first line and ends at the last line unless it hits any statementthat changes the control flow of the program such as loops, conditionals, etc.</p>
<pre><code>let age = 18;
  if (age >= 18) {
  console.log("You can vote!");
  } else {
  console.log("You are too young to vote.");
  } </code></pre>
</details>
<details> 
<summary>Object literal notation</summary>
<p>
Object literal notation is a way to create an object in JavaScript by listing its properties and values inside curly braces. It’s a simple and common way to create objects in JavaScript.
</p>
</details>
<details> 
<summary>Primitive values</summary>
<p>
Primitive values in JavaScript are the basic data types, such as numbers, strings, booleans, null, and undefined. They are <a href="https://developer.mozilla.org/en-US/docs/Glossary/Immutable">immutable </a>and are stored directly in memory.
</p>
</details>
<details> <summary>Objects in JavaScript</summary>

<p>Objects in JavaScript are like containers that hold related data and functionality in key-value pairs. Imagine a box that contains things related to a particular thing, that’s what an object is. Each value in an object is called a property, and a property can be a primitive value like a string, number, or boolean, an object or even a function. Objects are widely used in JavaScript, and having a good understanding of objects is crucial for becoming a successful JavaScript developer.</p>

<p>To create an object in JavaScript, we use the object literal notation. It looks like a set of braces enclosing key-value pairs, separated by commas. Here’s an example:</p>

<pre><code>const zeeshan = { name: “Zeeshan”, age: 21, hobbies: [“reading”, “writing”, “coding”], greeting: function() { console.log("Hello, my name is " + this.name); } }; </code></pre>

<p>In this example, we’ve created an object called zeeshan that has several properties, including name, age, hobbies, and greeting. The greeting property is a function that can be called on the object.</p>

<p>You can access the properties of an object using dot notation or bracket notation. Here are some examples:</p>

<pre><code> console.log(zeeshan.name); // Output: “Zeeshan” console.log(zeeshan[“age”]); // Output: 21 </code></pre>

<p>You can also add or modify properties on an object using either dot notation or bracket notation. Here’s an example:</p>

<pre><code> zeeshan.job = “Bechlor Student”; zeeshan[“location”] = “Pakistan”; </code></pre>

<p>Objects in JavaScript are very powerful and can be used to represent complex data structures. Understanding how to create and manipulate objects is an essential skill for any JavaScript developer.</p> </details>
<details> <summary>Strings</summary>
A string is a sequence of characters enclosed in single quotes (‘’) or double quotes (“”). For example:
<pre><code>
const myString = 'Hello, Zeeshan!'; // using string literal
const anotherString = String('I am a string'); // using String() constructor 
</code></pre>
Strings are <a href="https://developer.mozilla.org/en-US/docs/Glossary/Immutable">immutable </a>, which means that their contents cannot be changed once created. However, you can create a new string based on the original string using string methods such as `slice()`, `concat()`, `replace()`, and others. For example:
<pre><code>
const myString = 'Hello, Zeeshan!';
const newString = myString.slice(0, 5); // returns 'Hello'
const concatenatedString = myString.concat(' How are you?'); // returns 'Hello, Zeeshan! How are you?'
const replacedString = myString.replace('Zeeshan', 'universe'); // returns 'Hello, universe!'
</code></pre>
You can also access individual characters of a string using bracket notation. For example:
<pre><code>
const myString = 'Hello, Zeeshan!';
const firstCharacter = myString[0]; // returns 'H'
const lastCharacter = myString[myString.length - 1]; // returns '!'
</code></pre>
JavaScript provides many built-in string methods that you can use to manipulate and work with strings. Some of the most commonly used methods include `toUpperCase()`, `toLowerCase()`, `trim()`, `split()`, `charAt()`, and others. For example:
<pre><code>
const myString = ' Hello, Zeeshan! ';
const uppercaseString = myString.toUpperCase(); // returns ' HELLO, Zeeshan! '
const lowercaseString = myString.toLowerCase(); // returns ' hello, Zeeshan! '
const trimmedString = myString.trim(); // returns 'Hello, Zeeshan!'
const splitString = myString.split(','); // returns [' Hello', ' Zeeshan! ']
const thirdCharacter = myString.charAt(2); // returns 'H'
</code></pre>
</details>
<details> <summary>Arrays in JavaScript</summary> <p>
In JavaScript, an array is a collection of values, which can be of any data type. Arrays can be created using the array literal notation [] or the Array() constructor function.

<pre><code>
// array literal notation
const myArray = [1, 'two', true];

// Array constructor function
const anotherArray = new Array(1, 'two', true);
</code></pre>

You can access individual elements of an array using their index, which starts at 0 for the first element. You can also modify the value of an element by assigning a new value to its index.

<pre><code>
const myArray = ['apple', 'banana', 'orange'];

// access individual elements
const firstElement = myArray[0]; // 'apple'
const thirdElement = myArray[2]; // 'orange'

// modify element value
myArray[1] = 'pear';
console.log(myArray); // ['apple', 'pear', 'orange']
</code></pre>

Arrays in JavaScript are dynamic, which means you can add or remove elements from an array at any time. There are several built-in methods that you can use to modify and work with arrays. Here are some of the most commonly used array methods in JavaScript:

- push(): adds one or more elements to the end of an array
- pop(): removes and returns the last element of an array
- shift(): removes and returns the first element of an array
- unshift(): adds one or more elements to the beginning of an array
- splice(): adds or removes elements from an array at a specified position
- slice(): returns a new array with a portion of the original array

Here are some examples of using these array methods:

<pre><code>
const myArray = ['apple', 'banana', 'orange'];

// add elements to the end of an array
myArray.push('pear', 'grape');
console.log(myArray); // ['apple', 'banana', 'orange', 'pear', 'grape']

// remove and return the last element of an array
const lastElement = myArray.pop();
console.log(lastElement); // 'grape'
console.log(myArray); // ['apple', 'banana', 'orange', 'pear']

// remove and return the first element of an array
const firstElement = myArray.shift();
console.log(firstElement); // 'apple'
console.log(myArray); // ['banana', 'orange', 'pear']

// add elements to the beginning of an array
myArray.unshift('kiwi', 'mango');
console.log(myArray); // ['kiwi', 'mango', 'banana', 'orange', 'pear']

// remove elements from an array at a specified position
const removedElements = myArray.splice(2, 2);
console.log(removedElements); // ['banana', 'orange']
console.log(myArray); // ['kiwi', 'mango', 'pear']

// create a new array with a portion of the original array
const newArray = myArray.slice(1, 3);
console.log(newArray); // ['mango', 'pear']
console.log(myArray); // ['kiwi', 'mango', 'pear']
</code></pre>
</p> </details>

## Next Level JavaScript Techniques

<details>
    <summary>Hoisting</summary>
    <p>Hoisting is a behavior in JavaScript that allows you to use variables and functions before they are actually declared in your code.
Think of it like a magician who pulls a rabbit out of a hat. Just like the rabbit is magically pulled out of the hat, hoisting pulls variables and functions to the top of your code so they can be used even before they are defined.
However, be careful when using hoisting because it can lead to confusion and errors in your code if you're not careful. So, it's always best to declare your variables and functions at the top of your code to avoid any unexpected behavior.</p> 
<pre><code>console.log(myNumber); // undefined
var myNumber = 10;
</code></pre>

<pre><code>console.log(myVariable); // output: undefined
var myVariable = "Hi Zeeshan!";
</code></pre>

<p>In this example, we're trying to log the value of myVariable before we've assigned it a value. Normally, this would result in a ReferenceError, but because of hoisting, the variable declaration is moved to the top of its scope, and the output is undefined instead. This is because myVariable is still considered to exist, but has not yet been assigned a value.
It's important to note that hoisting only moves variable and function declarations to the top of their scope, not their assignments. So in the above example, only the var myVariable declaration is hoisted, not the assignment of "Hi Zeeshan!"</p>

</details>
<details>
    <summary>Scope and function stack</summary>
    <p>Think of scope as the space where variables are accessible in your code. Imagine you have a room with a desk and a lamp. The desk is your scope, and the lamp is your variable. You can see the lamp because it's on the desk, but you can't see the lamp in another room because it's outside your scope.

Now let's talk about function stack. It's like a stack of pancakes. When you call a function, it's like adding a new pancake to the top of the stack. And when the function finishes running, it's like removing the top pancake from the stack. This means that the last function you called is the first function that will finish running.

So, scope is like the space where you can see your variables, and function stack is like a stack of pancakes where you keep track of the functions you call.</p>

<pre><code>let name = "Zeeshan"; // Global scope

function sayName() {
  let name = "Kamran"; // Local scope
  console.log(name);
}

sayName(); // Output: Kamran
console.log(name); // Output: Zeeshan
</code></pre>
</details>
<details>
  <summary>Lexical scoping</summary>
  <p>Lexical scoping is a way of determining the scope of a variable based on its position in the code. In other words, variables declared within a function are only accessible within that function, and variables declared outside of a function are accessible throughout the entire program</p>
  <pre><code>let x = 10;

function myFunction() {
let y = 20;
console.log(x); // Output: 10
console.log(y); // Output: 20
}

myFunction();

console.log(x); // Output: 10
console.log(y); // Output: Uncaught ReferenceError: y is not defined
</code></pre>

<p>In this code, the variable `x` is declared outside of the function and is therefore accessible throughout the entire program. The variable `y` is declared within the `myFunction()` function and is only accessible within that function. If we try to access y outside of the function, we will get a `ReferenceError` because it is not defined in that scope.</p>

</details>
<details>
    <summary>Closures</summary>
    <p>Imagine you have a treasure box, and you want to keep it safe from others. So, you lock it with a key, and only you have that key to open it. The treasure box is like a function, and the key is like a closure.</p>
      <p>In JavaScript, closures are used to keep variables and functions private, just like a treasure box that is only accessible through a key. The key is nothing but a closure, which keeps the variables and functions inside a function safe and secure from the outer world.</p>
        <p>When you create a closure, you create a small space where variables and functions can live, and it can be accessed by its inner functions. But these variables and functions are not accessible by the outer world, making it private.</p>
          <p>For example, suppose you have a function that returns another function. The inner function can access the variables and functions of its outer function, but the outer function cannot access the variables and functions of the inner function.</p>

<pre><code>
function outer() {
let x = 10;

function inner() {
console.log(x);
}

return inner;
}

let innerFunction = outer();

innerFunction(); // output: 10

</code></pre>
  <p>In this example, the `outer` function returns the `inner` function. The `inner` function has access to the variable x which is declared in the `outer` function. Even though the `outer` function has finished executing and its variables should have been destroyed, the `inne`r function is still able to access and use the value of `x`. This is possible because of closures.</p>

</details>
<details>
    <summary>Strict Mode</summary>
    <p>Strict mode is a way to write safer and more reliable code in JavaScript. It helps prevent mistakes and potential bugs that can occur when writing JavaScript code. When strict mode is enabled, certain actions that were previously ignored or caused errors will now trigger an error instead</p>
    <p>For example, strict mode prevents the use of undeclared variables, which can cause issues in your code. It also disallows certain syntax that is considered dangerous or problematic.
    </p>
    <p>To enable strict mode, you simply add the string "use strict" at the beginning of your JavaScript file or function. Once enabled, you cannot disable strict mode for that file or function
    </p>
    <pre><code>
'use strict'; // Enable strict mode

function myFunction() {
x = 3.14; // Throws an error in strict mode (variable x is not declared)
console.log(x);
}

myFunction()
</code></pre>

</details>

<details> <summary>Using "this" keyword</summary> <p> Let's say you have a car object in JavaScript that has properties such as "make", "model", and "year", and a method called "startEngine". You can use the "this" keyword in the "startEngine" method to refer to the current car object and modify its properties accordingly. Here's an example: </p> <pre><code> const car = { make: "Toyota", model: "Corolla", year: 2022, startEngine: function() { console.log(Starting engine for ${this.year} ${this.make} ${this.model}...); // code to start the engine } };

car.startEngine();

</code></pre> <p> In this example, the `this` keyword is used to refer to the current car object inside the `startEngine` method. When the method is called using the `car.startEngine()` syntax, the value of `this` is set to the `car` object. The method then uses the `this` keyword to access the `year`, `make`, and `model` properties of the `car` object to display a message in the console indicating that the engine is starting for that specific car. </p> </details>

<details> <summary>Promises in JavaScript</summary>
<p>A Promise is like a promise someone makes to you. It's like when your friend promises to give you a toy tomorrow. You trust your friend, but you don't have the toy yet. You have to wait until tomorrow to get it. In the meantime, you can do other things, like play with your other toys or go to sleep.</p>

<p>In JavaScript, a Promise is similar. It's like a promise that some code makes to you. The code promises to give you a value, but you don't have it yet. You have to wait until the code finishes running to get the value. In the meantime, you can do other things in your code.</p>

<p>Promises have three states: pending, fulfilled, and rejected. When a Promise is pending, it means that the code hasn't finished running yet. When a Promise is fulfilled, it means that the code has finished running successfully and has given you a value. When a Promise is rejected, it means that the code has finished running unsuccessfully and has given you an error.</p>

<p>Here's an example of using Promises in JavaScript:</p>

<pre><code> const fetchData = () => { return new Promise((resolve, reject) => { // code to fetch data asynchronously // resolve with data if successful // reject with error if unsuccessful }); };

fetchData() .then(data => { // do something with data when it's available }) .catch(error => { // handle error if something went wrong }); </code></pre>

<p>In this example, the <code>fetchData</code> function returns a Promise that fetches data asynchronously. When the Promise is fulfilled, the <code>.then</code> method is called, and you can do something with the data. If the Promise is rejected, the <code>.catch</code> method is called, and you can handle the error.</p>

</details>
