## Mastering the Basics of JavaScript

<details>
<summary>What is a variable in JavaScript?</summary>
<p>A variable is a container for storing a value. In JavaScript, you can declare a variable using the <code>var</code>, <code>let</code>, or <code>const</code> keywords. For example:</p>

```javascript
var message = “Hello, Zeeshan!”;
let count = 10;
const PI = 3.14;
```

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
    
   
```javascript
 let myString = "10"; // a string that represents a number
let myNumber = parseInt(myString); // convert string to integer

console.log(myNumber); // output: 10

````


</details>
<details>
<summary>What is a function in JavaScript?</summary>
<p>A function is a block of code that performs a specific task. It takes input in the form of arguments and returns output in the form of a return value. Functions allow you to reuse code, organize code into smaller, more manageable chunks, and make your code more modular and easier to understand.</p>

<p>Here is an example of a function that takes two arguments and returns their sum:</p>


```javascript
function addNumbers(num1, num2) {
let sum = num1 + num2;
return sum;
}
```

<p>You can call this function by passing in two numbers:</p>


```javascript
let result = addNumbers(5, 10);
console.log(result); // Output: 15
```


<p>In this example, the <code>addNumbers()</code> function takes two arguments, <code>num1</code> and <code>num2</code>, adds them together, and returns the sum.</p>
</details>
<details>
<summary>How do you declare a function in JavaScript?</summary>
<p>You can declare a function in JavaScript using the <code>function</code> keyword, followed by the function name and any parameters. For example:</p>


```javascript
function sayHello(name) {
console.log("Hello, " + name + “!”);
}
```


<p>You can then call the function by passing in any required arguments, like this:</p>


```javascript
sayHello(Zeeshan);
// Output: “Hello, Zeeshan!”
```

</details>
<details>
<summary>What is a conditional statement in JavaScript?</summary>
<p>A conditional statement allows you to execute different code depending on whether a certain condition is true or false. The most common conditional statement in JavaScript is the <code>if</code> statement. For example:</p>

```javascript
let age = 18;

if (age >= 18) {
console.log(“You are an adult!”);
} else {
console.log(“You are not yet an adult.”);
}
```


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

```javascript
let age = 18;
  if (age >= 18) {
  console.log("You can vote!");
  } else {
  console.log("You are too young to vote.");
  }
```
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


</details>
<details> <summary>Arrays in JavaScript</summary> <p>
In JavaScript, an array is a collection of values, which can be of any data type. Arrays can be created using the array literal notation [] or the Array() constructor function.


```javascript
// array literal notation
const myArray = [1, 'two', true];

// Array constructor function
const anotherArray = new Array(1, 'two', true);
```


You can access individual elements of an array using their index, which starts at 0 for the first element. You can also modify the value of an element by assigning a new value to its index.


```javascript
const myArray = ['apple', 'banana', 'orange'];

// access individual elements
const firstElement = myArray[0]; // 'apple'
const thirdElement = myArray[2]; // 'orange'

// modify element value
myArray[1] = 'pear';
console.log(myArray); // ['apple', 'pear', 'orange']
```


Arrays in JavaScript are dynamic, which means you can add or remove elements from an array at any time. There are several built-in methods that you can use to modify and work with arrays. Here are some of the most commonly used array methods in JavaScript:

- push(): adds one or more elements to the end of an array
- pop(): removes and returns the last element of an array
- shift(): removes and returns the first element of an array
- unshift(): adds one or more elements to the beginning of an array
- splice(): adds or removes elements from an array at a specified position
- slice(): returns a new array with a portion of the original array

Here are some examples of using these array methods:
```javascript


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
```

</p> </details>

## Next Level JavaScript Techniques

<details>
    <summary>Hoisting</summary>
    <p>Hoisting is a behavior in JavaScript that allows you to use variables and functions before they are actually declared in your code.
Think of it like a magician who pulls a rabbit out of a hat. Just like the rabbit is magically pulled out of the hat, hoisting pulls variables and functions to the top of your code so they can be used even before they are defined.
However, be careful when using hoisting because it can lead to confusion and errors in your code if you're not careful. So, it's always best to declare your variables and functions at the top of your code to avoid any unexpected behavior.</p>

```javascript
console.log(myNumber); // undefined
var myNumber = 10;
```


```javascript
console.log(myVariable); // output: undefined
var myVariable = "Hi Zeeshan!";
```


<p>In this example, we're trying to log the value of myVariable before we've assigned it a value. Normally, this would result in a ReferenceError, but because of hoisting, the variable declaration is moved to the top of its scope, and the output is undefined instead. This is because myVariable is still considered to exist, but has not yet been assigned a value.
It's important to note that hoisting only moves variable and function declarations to the top of their scope, not their assignments. So in the above example, only the var myVariable declaration is hoisted, not the assignment of "Hi Zeeshan!"</p>

</details>
<details>
    <summary>Scope and function stack</summary>
    <p>Think of scope as the space where variables are accessible in your code. Imagine you have a room with a desk and a lamp. The desk is your scope, and the lamp is your variable. You can see the lamp because it's on the desk, but you can't see the lamp in another room because it's outside your scope.

Now let's talk about function stack. It's like a stack of pancakes. When you call a function, it's like adding a new pancake to the top of the stack. And when the function finishes running, it's like removing the top pancake from the stack. This means that the last function you called is the first function that will finish running.

So, scope is like the space where you can see your variables, and function stack is like a stack of pancakes where you keep track of the functions you call.</p>

```javascript
let name = "Zeeshan"; // Global scope

function sayName() {
  let name = "Kamran"; // Local scope
  console.log(name);
}

sayName(); // Output: Kamran
console.log(name); // Output: Zeeshan
```

</details>
<details><summary>Javascript chrome dev tools</summary>
<p>Chrome DevTools is a set of web developer tools built directly into the Google Chrome browser. It allows developers to easily debug and profile JavaScript code, as well as inspect and modify the DOM and CSS of a web page.</p>
<p>To access Chrome DevTools in Google Chrome, follow these steps:
To access Chrome DevTools in Google Chrome, you need to open the browser, navigate to the desired web page, right-click on the page and select "Inspect" from the context menu. Alternatively, you can use the keyboard shortcut Ctrl+Shift+I (Windows, Linux) or Cmd+Opt+I (Mac). This will open the DevTools window, usually located at the bottom of the browser window.</p>

-  <b>Console</b> This tab allows you to view and interact with the JavaScript console. You can log messages, debug errors, and run JavaScript commands directly in the console.

- <b>Elements</b> The elements tab allows you to inspect and modify the HTML and CSS of a web page. You can also use it to view and modify the DOM and CSS in real-time.

- <b>Sources</b> This tab is where you can view and debug your JavaScript code. You can set breakpoints, step through your code, and inspect variables and objects.

- <b>Network</b> The network tab allows you to monitor the network activity of a web page. You can view the requests and responses, as well as performance metrics such as load time and file size.

</details>

<details>
  <summary>Lexical scoping</summary>
  <p>Lexical scoping is a way of determining the scope of a variable based on its position in the code. In other words, variables declared within a function are only accessible within that function, and variables declared outside of a function are accessible throughout the entire program</p>

```javascript
let x = 10;

function myFunction() {
let y = 20;
console.log(x); // Output: 10
console.log(y); // Output: 20
}

myFunction();

console.log(x); // Output: 10
console.log(y); // Output: Uncaught ReferenceError: y is not defined
```


<p>In this code, the variable `x` is declared outside of the function and is therefore accessible throughout the entire program. The variable `y` is declared within the `myFunction()` function and is only accessible within that function. If we try to access y outside of the function, we will get a `ReferenceError` because it is not defined in that scope.</p>

</details>
<details>
    <summary>Closures</summary>
    <p>Imagine you have a treasure box, and you want to keep it safe from others. So, you lock it with a key, and only you have that key to open it. The treasure box is like a function, and the key is like a closure.</p>
      <p>In JavaScript, closures are used to keep variables and functions private, just like a treasure box that is only accessible through a key. The key is nothing but a closure, which keeps the variables and functions inside a function safe and secure from the outer world.</p>
        <p>When you create a closure, you create a small space where variables and functions can live, and it can be accessed by its inner functions. But these variables and functions are not accessible by the outer world, making it private.</p>
          <p>For example, suppose you have a function that returns another function. The inner function can access the variables and functions of its outer function, but the outer function cannot access the variables and functions of the inner function.</p>


```javascript
function outer() {
let x = 10;

function inner() {
console.log(x);
}

return inner;
}

let innerFunction = outer();

innerFunction(); // output: 10
```


  <p>In this example, the `outer` function returns the `inner` function. The `inner` function has access to the variable x which is declared in the `outer` function. Even though the `outer` function has finished executing and its variables should have been destroyed, the `inne`r function is still able to access and use the value of `x`. This is possible because of closures.</p>

</details>
<details>
    <summary>Strict Mode</summary>
    <p>Strict mode is a way to write safer and more reliable code in JavaScript. It helps prevent mistakes and potential bugs that can occur when writing JavaScript code. When strict mode is enabled, certain actions that were previously ignored or caused errors will now trigger an error instead</p>
    <p>For example, strict mode prevents the use of undeclared variables, which can cause issues in your code. It also disallows certain syntax that is considered dangerous or problematic.
    </p>
    <p>To enable strict mode, you simply add the string "use strict" at the beginning of your JavaScript file or function. Once enabled, you cannot disable strict mode for that file or function
    </p>

```javascript
'use strict'; // Enable strict mode

function myFunction() {
x = 3.14; // Throws an error in strict mode (variable x is not declared)
console.log(x);
}

myFunction()
```


</details>

<details> <summary>Using "this" keyword</summary> <p> Let's say you have a car object in JavaScript that has properties such as "make", "model", and "year", and a method called "startEngine". You can use the "this" keyword in the "startEngine" method to refer to the current car object and modify its properties accordingly. Here's an example: </p> <pre><code> const car = { make: "Toyota", model: "Corolla", year: 2022, startEngine: function() { console.log(Starting engine for ${this.year} ${this.make} ${this.model}...); // code to start the engine } };

car.startEngine();

</code></pre> <p> In this example, the `this` keyword is used to refer to the current car object inside the `startEngine` method. When the method is called using the `car.startEngine()` syntax, the value of `this` is set to the `car` object. The method then uses the `this` keyword to access the `year`, `make`, and `model` properties of the `car` object to display a message in the console indicating that the engine is starting for that specific car. </p> </details>

<details> <summary>Promises in JavaScript</summary>
<p>A Promise is like a promise someone makes to you. It's like when your friend promises to give you a toy tomorrow. You trust your friend, but you don't have the toy yet. You have to wait until tomorrow to get it. In the meantime, you can do other things, like play with your other toys or go to sleep.</p>

<p>In JavaScript, a Promise is similar. It's like a promise that some code makes to you. The code promises to give you a value, but you don't have it yet. You have to wait until the code finishes running to get the value. In the meantime, you can do other things in your code.</p>

<p>Promises have three states: pending, fulfilled, and rejected. When a Promise is pending, it means that the code hasn't finished running yet. When a Promise is fulfilled, it means that the code has finished running successfully and has given you a value. When a Promise is rejected, it means that the code has finished running unsuccessfully and has given you an error.</p>

<p>Here's an example of using Promises in JavaScript:</p>

```javascript
const fetchData = () => {
  return new Promise((resolve, reject) => { // code to fetch data asynchronously // resolve with data if successful // reject with error if unsuccessful }); };

fetchData() .then(data => {
  // do something with data when it's available }) .catch(error => { // handle error if something went wrong });
```

<p>In this example, the <code>fetchData</code> function returns a Promise that fetches data asynchronously. When the Promise is fulfilled, the <code>.then</code> method is called, and you can do something with the data. If the Promise is rejected, the <code>.catch</code> method is called, and you can handle the error.</p>

</details>
<details>
    <summary>Callbacks</summary>
    <p>A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action</p>

  ```javascript
  function add(a, b, callback) {
  let result = a + b;
  callback(result);
}

function displayResult(result) {
console.log(`The result is ${result}.`);
}

add(5, 3, displayResult);
```


 <p>In this example, the `add` function takes in two numbers `a` and b`, and a `callback` function callback. The `add` function computes the sum of `a` and `b`, and then calls the `callback` function with the result. </p>
<p>
The `displayResult` function is an example of a callback function. It takes in the result parameter and logs it to the console. </p>
<p>
Finally, we call the `add` function with the numbers 5 and 3, as well as the `displayResult` function as the callback. When ad`d computes the sum of 5 and 3, it calls the `displayResult` function with the result of 8. The `displayResult` function then logs "The result is 8." to the console.</p>

</details>

<details><summary>Async/Await</summary>
<p>In JavaScript, we sometimes need to perform tasks that take time to complete, such as fetching data from a remote server or waiting for a user to interact with a web page. These tasks are usually performed asynchronously, which means that the program does not wait for them to complete before moving on to the next task.</p>
<p>Async/await is a feature in JavaScript that allows you to write asynchronous code that looks like synchronous code. It makes your code easier to read and understand by simplifying the syntax for handling asynchronous operations.</p>

```javascript
// Define an asynchronous function called `getData`
async function getData() {
  // Wait for the response from the API using `fetch`
  const response = await fetch('https://api.example.com/data');
  // Wait for the JSON data to be extracted from the response
  const data = await response.json();
  // Return the data
  return data;
}

// Call the `getData` function and handle the data once it is available
getData()
  .then((data) => {
    // Print the data to the console
    console.log(data);
  })
  .catch((error) => {
    // Handle any errors that occur during the asynchronous operation
    console.error(error);
  });
````

</details>

<details><summary>Modules</summary>
<p>Modules are essentially reusable pieces of code that can be exported from one file and imported into another. They allow developers to break their code into smaller, more manageable pieces and organize their projects more effectively.</p>
<p>Suppose you have two files: `main.js` and `helper.js`. In` helper.js`, you define a function called `addNumber`s that adds two numbers together and `returns` the result:</p>

```javascript
// helper.js
function addNumbers(a, b) {
  return a + b;
}

export { addNumbers };
```

```javascript
// main.js
import { addNumbers } from './helper.js';

console.log(addNumbers(2, 3)); // Output: 5
```

<p>There are two types of exports: named exports and default exports. In the above example, we used a named export, where we explicitly exported the addNumbers function using the export keyword.</p>

<p>Named exports are used when you want to export multiple functions or objects from a module, and you want to explicitly name them when you import them in another file.</p>

```javascript
// helper.js
export function addNumbers(a, b) {
  return a + b;
}

export function subtractNumbers(a, b) {
  return a - b;
}
```

<p>In this code, we're exporting two functions, `addNumbers` and `subtractNumbers`, from `helper.js` using `named exports`.

In main.js, we can then import these functions individually using their names:</p>

```javascript
// main.js
import { addNumbers, subtractNumbers } from './helper.js';

console.log(addNumbers(2, 3)); // Output: 5
console.log(subtractNumbers(5, 3)); // Output: 2
```

<p>On the other hand, default exports are used when you want to export a single function or object from a module, and you don't care what name it's imported as.</p>

```javascript
// helper.js
export default function addNumbers(a, b) {
  return a + b;
}
```

<p>
In this code, we're exporting a single function, addNumbers, from helper.js using a default export.

In main.js, we can then import this function using any name we like:

</p>

```javascript
// main.js
import myFunction from './helper.js';

console.log(myFunction(2, 3)); // Output: 5
```

</details>

<details><summary>Local Storage</summary>
<p>Local storage is a web browser feature that allows developers to store data in a user's browser. It provides a way to store key-value pairs, similar to a JavaScript object. The data stored in local storage persists even after the browser is closed or the computer is restarted.</p>
<p>Here is an example of how to use local storage in JavaScript:</p>

```javascript
// Storing data in local storage
localStorage.setItem('username', 'Zeeshan');
localStorage.setItem('age', '21');

// Retrieving data from local storage
const username = localStorage.getItem('username');
const age = localStorage.getItem('age');

console.log(username); // Output: Zeeshan
console.log(age); // Output: 21

// Updating data in local storage
localStorage.setItem('age', '26');

const updatedAge = localStorage.getItem('age');
console.log(updatedAge); // Output: 26

// Removing data from local storage
localStorage.removeItem('username');

const removedItem = localStorage.getItem('username');
console.log(removedItem); // Output: null
```

<p>in the above example, we use the `localStorage` object to store and retrieve data. The `setItem` method is used to store key-value pairs, and the `getItem` method is used to retrieve the value associated with a given key. The `removeItem` method is used to remove a key-value pair from local storage.</p>
</details>

<details><summary>Session Storage</summary> <p>Session storage is a web browser feature that allows developers to store data in a user's browser for the duration of the session. The data stored in session storage remains accessible as long as the browser tab or window is open. Once the tab or window is closed, the session storage data is cleared.</p> <p>Here is an example of how to use session storage in JavaScript:</p>

```javascript
// Storing data in session storage
sessionStorage.setItem('username', 'Zeeshan');
sessionStorage.setItem('age', '21');

// Retrieving data from session storage
const username = sessionStorage.getItem('username');
const age = sessionStorage.getItem('age');

console.log(username); // Output: Zeeshan
console.log(age); // Output: 21

// Updating data in session storage
sessionStorage.setItem('age', '26');

const updatedAge = sessionStorage.getItem('age');
console.log(updatedAge); // Output: 26

// Removing data from session storage
sessionStorage.removeItem('username');

const removedItem = sessionStorage.getItem('username');
console.log(removedItem); // Output: null
```

<p>In the above example, we use the `sessionStorage` object to store and retrieve data. The `setItem` method is used to store key-value pairs, and the `getItem` method is used to retrieve the value associated with a given key. The `removeItem` method is used to remove a key-value pair from session storage.</p> </details>

<details><summary>Event Loop</summary>
The event loop is a fundamental mechanism in JavaScript that handles the execution of asynchronous code. It is responsible for managing the order of execution, handling events, and ensuring that JavaScript's single-threaded nature is maintained while still allowing non-blocking operations.

Here is a basic outline of how the event loop works in JavaScript:

1. **Call Stack**: It keeps track of the currently executing function or task. When code is executed, it is added to the call stack. When a function completes, it is removed from the stack.

2. **Event Queue**: It holds the asynchronous tasks and events that are ready to be processed. When an asynchronous task completes, it is added to the event queue.

The event loop follows a continuous cycle, which can be broken down into the following steps:

1. The main thread executes synchronous code, and functions are added to the call stack. Execution continues until there is no more synchronous code to execute.

2. When an asynchronous operation, such as making an API request or setting a timeout, is encountered, it is handed off to the browser's Web APIs. The asynchronous task completes independently, outside of the main thread.

3. Once the asynchronous task is complete, it is pushed into the event queue.

4. The event loop constantly checks if the call stack is empty. If it is, the event loop takes the first task in the event queue and moves it to the call stack.

5. The task from the event queue is executed, and any synchronous code within it is added to the call stack.

6. The cycle continues as long as there are tasks in the event queue and the call stack becomes empty.

Understanding the event loop is crucial for writing efficient JavaScript code that handles asynchronous tasks effectively. By leveraging the event loop, developers can create responsive web applications and manage complex operations without blocking the main thread.

#### Benefits of the event loop:

- **Non-blocking behavior**: Asynchronous tasks can be executed in the background while the main thread continues to execute other code without waiting.

- **Responsiveness**: The event loop ensures that the user interface remains responsive, even when time-consuming tasks are running in the background.

- **Concurrency**: By offloading tasks to separate threads or processes and using callback functions or promises, multiple operations can run simultaneously.

- **Avoiding deadlock**: As JavaScript is single-threaded, the event loop prevents deadlocks that can occur if operations are blocked and waiting for each other indefinitely.
</details>
<details><summary>What are Web APIs?</summary>
Web APIs enable developers to access and manipulate web-based features and functionality, such as retrieving data from a server, modifying the Document Object Model (DOM), or making asynchronous requests. They provide a standardized way for developers to interact with web-based resources and services.

Here are a few commonly used Web APIs in web development:

1. **DOM API**: The Document Object Model (DOM) API allows developers to access and manipulate HTML elements and their attributes within a web page. It provides methods and properties to dynamically modify the content and structure of a web page.

2. **XMLHttpRequest API**: The XMLHttpRequest API enables developers to send HTTP requests to a server and receive responses. It is commonly used for making asynchronous requests to fetch data from an API or send data to a server without reloading the whole web page.
3. **Fetch API**: The Fetch API is a modern alternative to the XMLHttpRequest API that provides a more powerful and flexible way to make HTTP requests. It uses Promises to handle asynchronous operations and offers a simplified syntax for fetching resources.
4. **LocalStorage and sessionStorage APIs**: These APIs provide a way to store key-value pairs locally in the browser. They allow developers to persist data on the client-side, even after the page is refreshed or closed.
</details>

If you found this repo helpful, please consider giving it a star 🌟 to help other students discover it and benefit from it as well. Thank you for your support!
