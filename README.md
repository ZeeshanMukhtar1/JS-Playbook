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
