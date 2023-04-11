🚀 About this Repository

Welcome to our JavaScript Playbook, designed to help you learn JavaScript from scratch with easy-to-understand code snippets and examples. This repository is a collection of learning resources, including cheat sheets, code snippets, and helpful tips that will guide you through the basics and enhance your skills in JavaScript. As a front-end developer, I’ve compiled these resources to help me in my journey to master the language, and I’m sharing them with you. Let’s learn together!

If you have any feedback, suggestions, or contributions to improve this repository for beginners, please feel free to reach out to me. You can connect with me on LinkedIn or find me on GitHub using the links provided below. I’m always open to hearing from you and improving this resource together.
Happy learning!

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zeeshanmukhtar1/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ZeshanMukhtar01)
[![instagram](https://img.shields.io/badge/instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/zeshanmukhtar01/)

## Basic

<details>
  <summary>Introduction to JavaScript</summary>
  <p>JavaScript is a programming language that is used for creating interactive websites and web applications. It is used to add interactivity, dynamic content, and user interface effects to web pages.</p>
</details>
<details>
<summary>What is a variable in JavaScript?</summary>
<p>A variable is a container for storing a value. In JavaScript, you can declare a variable using the <code>var</code>, <code>let</code>, or <code>const</code> keywords. For example:</p>

<pre><code>var message = “Hello, world!”;
let count = 10;
const PI = 3.14;
</code></pre>
</details>
<details>
<summary>What are data types in JavaScript?</summary>
<p>JavaScript supports several data types, including:</p>
<ul>
<li><strong>Numbers</strong>: Used for storing numeric values, such as <code>1</code>, <code>2.5</code>, or <code>-10</code>.</li>
<li><strong>Strings</strong>: Used for storing text values, such as <code>“Hello, world!”</code> or <code>“123”</code>.</li>
<li><strong>Booleans</strong>: Used for storing true/false values, such as <code>true</code> or <code>false</code>.</li>
<li><strong>Undefined</strong>: Used for uninitialized variables.</li>
<li><strong>Null</strong>: Used to represent a null or empty value.</li>
<li><strong>Objects</strong>: Used for storing complex data structures.</li>
<li><strong>Arrays</strong>: Used for storing lists of values.</li>
</ul>
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
const myString = 'Hello, world!'; // using string literal
const anotherString = String('I am a string'); // using String() constructor 
</code></pre>
Strings are <a href="https://developer.mozilla.org/en-US/docs/Glossary/Immutable">immutable </a>, which means that their contents cannot be changed once created. However, you can create a new string based on the original string using string methods such as `slice()`, `concat()`, `replace()`, and others. For example:
<pre><code>
const myString = 'Hello, world!';
const newString = myString.slice(0, 5); // returns 'Hello'
const concatenatedString = myString.concat(' How are you?'); // returns 'Hello, world! How are you?'
const replacedString = myString.replace('world', 'universe'); // returns 'Hello, universe!'
</code></pre>
You can also access individual characters of a string using bracket notation. For example:
<pre><code>
const myString = 'Hello, world!';
const firstCharacter = myString[0]; // returns 'H'
const lastCharacter = myString[myString.length - 1]; // returns '!'
</code></pre>
JavaScript provides many built-in string methods that you can use to manipulate and work with strings. Some of the most commonly used methods include `toUpperCase()`, `toLowerCase()`, `trim()`, `split()`, `charAt()`, and others. For example:
<pre><code>
const myString = ' Hello, World! ';
const uppercaseString = myString.toUpperCase(); // returns ' HELLO, WORLD! '
const lowercaseString = myString.toLowerCase(); // returns ' hello, world! '
const trimmedString = myString.trim(); // returns 'Hello, World!'
const splitString = myString.split(','); // returns [' Hello', ' World! ']
const thirdCharacter = myString.charAt(2); // returns 'H'
</code></pre>
</details>
<!-- arrays -->
Sure, here’s an explanation of arrays in JavaScript with code snippets and markdown:

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
