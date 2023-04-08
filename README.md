# Welcome to JSPlaybook!

This repository is a collection of my learning and cheat sheets for JavaScript. Here, you'll find code snippets, helpful tips, and resources that I've compiled to help me in my journey to master the language.

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
