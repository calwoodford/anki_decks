<div align="center">
  <img height="60" src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png">
  <h1>JavaScript Questions and Answers</h1>
    <br>
  <a href="https://ankiweb.net/shared/info/376600095?cb=1696104749579"> Download the Anki deck here </a>
  <br><br>
</div>


Question 1.
What is JavaScript? (3)

<details><summary><b>Answer</b></summary>
1) High-level
2) Dynamically typed
3) Event-driven

</details>
<br><br>
Question 2.
What is a variable in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) A symbolic name for storing and managing data.

</details>
<br><br>
Question 3.
How do you declare a variable in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) Using var, let or const.

</details>
<br><br>
Question 4.
What is the difference between let and const in JavaScript? (2)

<details><summary><b>Answer</b></summary>

1) let is block-scoped and allows reassignment.
2) const is block-scoped but does not allow reassignment.
</details>
<br><br>
Question 5.
How do you assign a value to a variable in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) Using '='

</details>
<br><br>
Question 6.
List all primitive data types in JavaScript. (6)

<details><summary><b>Answer</b></summary>
1) String.
2) Number.
3) Boolean.
4) Undefined.
5) Null.
6) Symbol. 


</details>
<br><br>

Question 7.
What is a function in JavaScript? (3)

<details><summary><b>Answer</b></summary>
1) Reusable block of code
2) Allows you to encapsulate code.
3) First-class objects.

</details>
<br><br>
Question 8.
How do you define a function in JavaScript? Answer using an example. (1)

<details><summary><b>Answer</b></summary>
```javascript
function addNumbers(a, b) {
  return a + b;
}
```
</details>
<br><br>
Question 9.
How do you call a function in JavaScript? (1)

<details><summary><b>Answer</b></summary>

functionName(parameters);

</details>
<br><br>
Question 10.
What is an array in JavaScript?(4)

<details><summary><b>Answer</b></summary>
1) A data structure for storing values.
2) Creating using square brackets with elements separated by commas.
3) Has indexes.
4) Ordered. 

</details>
<br><br>
Question 11.
How do you create an array in JavaScript? (1)

<details><summary><b>Answer</b></summary>
variable = []

</details>
<br><br>
Question 12.
How do you access elements in an array in JavaScript? (1)

<details><summary><b>Answer</b></summary>
Using their index.

</details>
<br><br>
Question 13.
What is the length property of an array in JavaScript? (1)

<details><summary><b>Answer</b></summary>
Used for finding out the length (.length).

</details>
<br><br>
Question 14.
What is a JavaScript object? (3)

<details><summary><b>Answer</b></summary>
1) Uses key : value pairs.
2) Created using {} and by defining key value pairs.
3) Unordered.

</details>
<br><br>
Question 15.
How to access a key value? (2)

<details><summary><b>Answer</b></summary>
1) Dot notation.
2) Square bracket notation.

</details>
<br><br>
Question 16.
What must the keys be in a JS object? (1)

<details><summary><b>Answer</b></summary>
1) Unique.

</details>
<br><br>
Question 17.
What is the difference between null and undefined in JavaScript? (2)

<details><summary><b>Answer</b></summary>
1) null is an intentional absence of any object value.
2) undefined is the value assigned to a variable that is declared but not initialized.
</details>
<br><br>
Question 18.
What is a conditional statement in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) Used to perform different actions based on different conditions.

</details>
<br><br>
Question 19.
What does an if statement in JS allow? (1)

<details><summary><b>Answer</b></summary>
1) Allows you to execute a block of code if a specified condition is true.

</details>
<br><br>
Question 20.
What is a for loop in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) Control flow statement that allows you to execute a block of code repeatedly.

</details>
<br><br>
Question 21.
What is the purpose of the while loop in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) A while loop in JavaScript is used to execute a block of code as long as a specified condition is true. It repeatedly checks the condition before each iteration.

</details>
<br><br>
Question 22.
What is a switch statement in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) A switch statement is a conditional statement used to select one of many code blocks to be executed. 

</details>
<br><br>
Question 23.
What is an event in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) An event in JavaScript is an action or occurrence that happens as a result of something the user does or as a result of another program logic.

</details>
<br><br>
Question 24.
How do you add an event listener in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) addEventListener method. 

</details>
<br><br>
Question 25.
What is a callback function in JavaScript and what is it often used for? Give a basic syntax. (3)

<details><summary><b>Answer</b></summary>
1) A callback function in JavaScript is a function that is passed as an argument to another function and is executed after that function has finished its work.
2) It is often used for asynchronous operations.
3)

```javascript
function myFunction(parameter1, parameter2, callback) {

  // ...

  // When you're ready, call the callback function
  callback(result); // You can pass some data (result) to the callback
}
```


</details>
<br><br>
Question 26.
What is the Document Object Model (DOM) in JavaScript? What does it allow? (2)

<details><summary><b>Answer</b></summary>
1) The Document Object Model (DOM) is a programming interface for web documents.
2) It represents the page so that programs can change the document structure, style, and content dynamically.

</details>
<br><br>
Question 27.
How do you manipulate the DOM in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) You can manipulate the DOM in JavaScript by selecting HTML elements using methods like getElementById, querySelector, and getElementsByClassName, and then changing their properties, attributes, or content.

</details>
<br><br>
Question 28.
What is JSON in JavaScript? What is it used for?

<details><summary><b>Answer</b></summary>
1) JSON (JavaScript Object Notation)
2) It is a lightweight data-interchange format used for data exchange between a server and a client or between different parts of an application.

</details>
<br><br>
Question 29.
How do you parse JSON in JavaScript? What does this turn it into? (2)

<details><summary><b>Answer</b></summary>
1) You can parse JSON in JavaScript using the JSON.parse() method.
2) This method converts a JSON string into a JavaScript object.

</details>
<br><br>
Question 30.
What is AJAX in JavaScript? (What does it stand for and what does it do?) (2)

<details><summary><b>Answer</b></summary>
1) AJAX (Asynchronous JavaScript and XML).
2) It is a set of web development techniques that allow web applications to send and receive data from a server asynchronously without reloading the entire page.

</details>
<br><br>
Question 31.
What is a promise in JavaScript? What is it used for? (2)

<details><summary><b>Answer</b></summary>
1) A promise in JavaScript is an object representing the eventual completion or failure of an asynchronous operation.
2) It is used to handle asynchronous operations more elegantly.

</details>
<br><br>
Question 32.
What is a closure in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) A closure in JavaScript is a function that has access to its own scope, the outer function's scope, and the global scope. It "encloses" its environment, allowing it to capture and remember variables from outer scopes.

</details>
<br><br>
Question 33.
What is a callback hell (Pyramid of Doom) in JavaScript? Where does it often occur? (2)

<details><summary><b>Answer</b></summary>
1) Callback hell, also known as the Pyramid of Doom, is a situation in JavaScript where multiple nested callbacks make the code hard to read and maintain.
2) It often occurs with asynchronous operations.

</details>
<br><br>
Question 34.
What is ECMAScript in JavaScript? What does it define? (2)

<details><summary><b>Answer</b></summary>
1) ECMAScript is a standardized scripting language specification that JavaScript follows.
2) It defines the core features and syntax of JavaScript.

</details>
<br><br>
Question 35.
What is a module in JavaScript? (2)

<details><summary><b>Answer</b></summary>
1) A module in JavaScript is a self-contained unit of code that can be reused and imported into other JavaScript files.
2) Modules help organize and modularize code.

</details>
<br><br>
Question 36.
How do you export and import modules in JavaScript? (2)

<details><summary><b>Answer</b></summary>
To export from a module, you use export statements, and to import in another module, you use import statements. For example,

```javascript
export function myFunction()
```
```javascript
import { myFunction } from './myModule.js'.
```

</details>
<br><br>
Question 37.
What is the 'this' keyword in JavaScript? (1)

<details><summary><b>Answer</b></summary>
The 'this' keyword in JavaScript refers to the object it belongs to. Its value is determined by how a function is called, and it can change dynamically.

Examples:
```javascript
// Example 1: 'this' in a global context
console.log(this); // 'this' refers to the global object (e.g., 'window' in a browser)

// Example 2: 'this' in an object method
const person = {
  firstName: 'John',
  lastName: 'Doe',
  fullName: function() {
    console.log(this.firstName + ' ' + this.lastName);
  }
};
```

</details>
<br><br>
Question 38.
What is a constructor function in JavaScript? What could be used analogously to describe it? (2)

<details><summary><b>Answer</b></summary>
1) A constructor function in JavaScript is a template for creating objects. It defines the structure and behavior of objects that will be created using the new keyword.
2) It is like a blueprint.

Example:

```javascript
// Constructor function for creating Person objects
function Person(firstName, lastName, age) {
  // Properties
  this.firstName = firstName;
  this.lastName = lastName;
  this.age = age;

  // Method to display full name
  this.getFullName = function() {
    return this.firstName + ' ' + this.lastName;
  }
}
```

</details>
<br><br>

Question 39.
What is an arrow function in JavaScript? Give an example of its basic syntax. What does it inherit from the containing function? (3)

<details><summary><b>Answer</b></summary>
1) An arrow function is a concise way to write functions in JavaScript. It has a shorter syntax and does not bind its own this value.
2)

```javascript
const add = (a, b) => {
  return a + b;
};

console.log(add(5, 3)); // Outputs 8
```


3) 'this'

</details>
<br><br>
Question 40.
What does map() create in JavaScript and how? Give a basic use of map(). (2)

<details><summary><b>Answer</b></summary>
1) The map() function is used to create a new array by applying a provided function to each element of an existing array.
2)

```javascript
const numbers = [1, 2, 3, 4, 5];

// Using the map function to square each number
const squaredNumbers = numbers.map((num) => num * num);

console.log(squaredNumbers);
// Output: [1, 4, 9, 16, 25]
```
</details>
<br><br>
Question 41.
What is a callback in the context of the map() function in JavaScript? (1)

<details><summary><b>Answer</b></summary>
A callback in the context of the map() function is the function provided as an argument to map(). It is called for each element of the array and returns a value that is added to the new array.

In the below example, it would be ```(num) => num * num```

```javascript
const numbers = [1, 2, 3, 4, 5];

// Using the map function to square each number
const squaredNumbers = numbers.map((num) => num * num);

console.log(squaredNumbers);
// Output: [1, 4, 9, 16, 25]
```

</details>
<br><br>
Question 42.
What is the filter() function in JavaScript used for? Give an example. (2)

<details><summary><b>Answer</b></summary>
1) The filter() function is used to create a new array with all elements that pass a provided test (predicate) function.

2)
```javascript
const numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

// Using the filter function to get even numbers
const evenNumbers = numbers.filter((num) => num % 2 === 0);

console.log(evenNumbers);
// Output: [2, 4, 6, 8, 10]
```

</details>
<br><br>
Question 43.
What is the reduce() function in JavaScript? Provide a basic example. (2).

<details><summary><b>Answer</b></summary>
1) The reduce() function is used to reduce an array to a single value. It applies a provided function against an accumulator and each element in the array.
2)

```javascript
const numbers = [1, 2, 3, 4, 5];

// Using reduce to calculate the sum
const sum = numbers.reduce((accumulator, current) => accumulator + current, 0);

console.log(sum);
// Output: 15
```

</details>
<br><br>
Question 44.
What is asynchronous programming in JavaScript? When is it often used? (2)

<details><summary><b>Answer</b></summary>
1) Asynchronous programming in JavaScript is a programming style that allows tasks to be performed concurrently without blocking the main program's execution.
2) It is often used for tasks like fetching data from a server.

</details>
<br><br>

Question 45.
What is the async and await syntax in JavaScript? What do they do? (1)(2)

<details><summary><b>Answer</b></summary>
1) Provide a more readable way to work with promises and perform asynchronous operations.
2) The async keyword is used to define an asynchronous function.
3) The await keyword is used to pause the execution of a function until a promise is resolved.

</details>
<br><br>
Question 46.
What is the purpose of the JavaScript try...catch statement? What does it allow? Give a basic example. (3)

<details><summary><b>Answer</b></summary>
1) The try...catch statement is used in JavaScript to handle exceptions (errors) that may occur during the execution of code.
2) It allows you to gracefully handle errors and prevent them from crashing your program.
3)
```javascript
function divide(a, b) {
  try {
    if (b === 0) {
      throw new Error("Division by zero is not allowed.");
    }
    return a / b;
  } catch (error) {
    console.error("An error occurred:", error.message);
    return null; // Return null to indicate an error.
  }
}
```

</details>
<br><br>
Question 47.
Is 'error' built-in to JavaScript? Give an example of where it may be used.(2)

<details><summary><b>Answer</b></summary>

1) Yes.

2)
```javascript
} catch (error) {
    console.error("An error occurred:", error.message);
    return null; // Return null to indicate an error.
  }
```

</details>
<br><br>
Question 48.
What is a closure in the context of callbacks and asynchronous JavaScript? Where are they commonly used? (2)

<details><summary><b>Answer</b></summary>
1) A closure in the context of callbacks and asynchronous JavaScript is a function that captures and remembers the variables from its containing scope even after that scope has exited.
2) Closures are commonly used when working with asynchronous operations to maintain access to variables across multiple function calls.

</details>
<br><br>
Question 49.
What does dynamically typed language mean in JavaScript? (1)

<details><summary><b>Answer</b></summary>
1) Dynamically typed languages mean that the data type of a variable is determined by the value it has at runtime and can change throughout the program as you assign different values to it.

</details>
<br><br>
Question 50.
List all composite data types in JavaScript. (7)

<details><summary><b>Answer</b></summary>
1) Object.
2) Array.
3) Function.
4) Date.
5) RegExp(Regular Expression).
6) Map.
7) Set. 

</details>
<br><br>

Question 51.
List all composite data types in JavaScript. (5)

<details><summary><b>Answer</b></summary>
1) NaN (Not-a-Number).
2) Infinity and - Infinity.
3) BigInt.
4) Undefined.
5) Null.

</details>
<br><br>

Question 52.
Define a function that turns a number to a string. What method do you need? (2)

<details><summary><b>Answer</b></summary>
1)
```javascript
function numberToString(num) {
  return num.toString();
}
```
2) toString();
</details>
<br><br>

Question 53.
What does 'Math.floor' do?(1)

<details><summary><b>Answer</b></summary>
1) The Math.floor() method rounds a number DOWN to the nearest integer.
</details>
<br><br>

Question 54.
What does 'Math.round' do?(1)

<details><summary><b>Answer</b></summary>
1) The Math.round() method rounds a number to the nearest integer. 2.49 will be rounded down (2), and 2.5 will be rounded up (3).
</details>
<br><br>

Question 55.
What is a first-class object in JavaScript?(1)

<details><summary><b>Answer</b></summary>
1) In JavaScript, functions are considered first-class objects. This means that functions can be treated like any other data type, such as numbers, strings, or objects.
</details>
<br><br>

Question 56.
What is 'block-scoped' in JavaScript? Give an example. (2)

<details><summary><b>Answer</b></summary>
1) "Block-scoped" refers to the concept of variable scope within a specific block of code, typically delimited by curly braces {}.
2) 

```javascript
if (true) {
  let x = 10; // x has block scope
  const y = 20; // y also has block scope
}

console.log(x); // Error: x is not defined
console.log(y); // Error: y is not defined
```

</details>
<br><br>

Question 57.
How might one split a string into individual characters? (Answer via a code example). (1)

<details><summary><b>Answer</b></summary>

```javascript
variable = str.split(''); // that's two single quotes, not one double quote.
```

</details>
<br><br>

Question 58.
How does pop() do in JavaScript? Use it in a code example. (2)

<details><summary><b>Answer</b></summary>

1) pop() is a method in Javascript whose function is to remove the final element from an array and to return that element.

2)

```javascript
const myArray = [1, 2, 3, 4, 5];

const lastElement = myArray.pop();

console.log(lastElement); // Outputs the removed element, which is 5
console.log(myArray);     // Outputs the modified array, which is [1, 2, 3, 4]

```

</details>
<br><br>

Question 59.
How does unshift() do in JavaScript? Use it in a code example. (2)

<details><summary><b>Answer</b></summary>

1) The unshift() method adds new elements to the beginning of an array.

2)

```javascript
const myArray = [2, 3, 4, 5];

myArray.unshift(1); // Add the number 1 to the beginning of the array
myArray.unshift(-1, 0); // Add -1 and 0 to the beginning of the array

console.log(myArray); // Outputs the modified array: [-1, 0, 1, 2, 3, 4, 5]
```

</details>
<br><br>

Question 60.
How does shift() do in JavaScript? Use it in a code example. (2)

<details><summary><b>Answer</b></summary>

1) The shift() method removes the element at the zeroth index and shifts the values at consecutive indexes down, then returns the removed value. 

2)

```javascript
const myArray = [1, 2, 3, 4, 5];

const firstElement = myArray.shift();

console.log(firstElement); // Outputs the removed element, which is 1
console.log(myArray);     // Outputs the modified array, which is [2, 3, 4, 5]
```

</details>
<br><br>