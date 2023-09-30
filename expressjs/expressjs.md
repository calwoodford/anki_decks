<div align="center">
  <img height="60" src="https://miro.medium.com/v2/resize:fit:1400/1*XP-mZOrIqX7OsFInN2ngRQ.png">
  <h1>Express.js Questions and Answers</h1>
    <a href="https://ankiweb.net/shared/info/1982258792?cb=1695936303593"> Download the Anki deck here </a>
    <br><br>

</div>

###### Question 1.

What does the following command do and what does it generate?

```javascript
npm init -y
```

<details><summary><b>Answer</b></summary>
<p>

The `npm init -y` command is used to initialize a new Node.js project and create a `package.json` file with default values without prompting you for any information. The `-y` flag stands for "yes" and is used to automatically accept all the default settings during the initialization process.

</p>
</details>

<br><br>

###### Question 2.

How might one install all npm dependencies needed in the project via the terminal?

<details><summary><b>Answer</b></summary>
<p>

```javascript
npm install
```

OR

```javascript
npm i
```

This command will read the `package.json` file in your project directory and install all the dependencies listed in it.

</p>
</details>

<br><br>

###### Question 3.

How might one install Express via the terminal?

<details><summary><b>Answer</b></summary>
<p>

```javascript
npm install express
```

OR

```javascript
npm i express
```

</p>
</details>

<br><br>

###### Question 4.

How might one check the version of Node installed via the terminal? (Also checks to see if it's installed at all)

<details><summary><b>Answer</b></summary>
<p>

```javascript
node - v
```

OR

```javascript
node --version
```

</p>
</details>

<br><br>

###### Question 5.

`npm` (Node Package Manager) comes bundled with Node.js when you download and install it, true or false?

<details><summary><b>Answer</b></summary>
<p>

True (for most cases)

</p>
</details>

<br><br>

###### Question 6.

How might one check the version of npm installed via the terminal?

<details><summary><b>Answer</b></summary>
<p>

```javascript
npm - v
```

OR

```javascript
npm --version
```

</p>
</details>

<br><br>

###### Question 7.

What is Express.js?

<details><summary><b>Answer</b></summary>
<p>

Express.js is a web application framework for Node.js. It simplifies the process of building robust, scalable, and maintainable web applications by providing a set of features and tools.

</p>
</details>

<br><br>

###### Question 8.

What is a route in Express.js?

<details><summary><b>Answer</b></summary>
<p>

A route in Express.js defines how an application responds to a client request to a specific endpoint (URL) and HTTP method (e.g., GET, POST).

</p>
</details>

<br><br>

###### Question 9.

What are the four elements required to make a simple server using Express.js?

<details><summary><b>Answer</b></summary>
<p>

```javascript
const express = require("express");
```

```javascript
const app = express();
```

```javascript
const port = 3000;
```

```javascript
app.listen(port, () => {
  console.log(`Server is running on port ${port}`);
});
```

</p>
</details>

<br><br>

###### Question 10.

What is middleware in Express.js?

<details><summary><b>Answer</b></summary>
<p>

Middleware functions in Express.js are functions that have access to the request and response objects. They can be used to perform tasks like authentication, logging, or modifying the request or response.

</p>
</details>

<br><br>

###### Question 11.

How do you define a route in Express.js?

<details><summary><b>Answer</b></summary>
<p>

```javascript
app.method(path, callback);
```

Where `method` is a HTTP method (e.g., GET, POST), `path` is the URL path, and `callback` is a function that handles the request and response.

</p>
</details>

<br><br>

###### Question 12.

What is a middleware stack in Express.js?

<details><summary><b>Answer</b></summary>
<p>

A middleware stack in Express.js is a series of middleware functions that are executed in the order they are defined for a specific route. Each middleware function can process the request or response and pass control to the next middleware in the stack using `next()`.

</p>
</details>

<br><br>

###### Question 13.

What is the purpose of the Express.js response object (`res`)?

<details><summary><b>Answer</b></summary>
<p>

The `res` object in Express.js is used to send responses to the client. It provides methods for sending data, setting headers, and controlling the HTTP response.

</p>
</details>

<br><br>

###### Question 14.

What is `req` in Express.js?

<details><summary><b>Answer</b></summary>
<p>

This is an object that represents the incoming HTTP request from the client, which includes information about the URL, headers, and more.

</p>
</details>

<br><br>

###### Question 15.

What is `params` in Express.js?

<details><summary><b>Answer</b></summary>
<p>

This is a property of the `req` object that specifically holds information about the parameters in the URL.

</p>
</details>

<br><br>

###### Question 16.

In the below example, what is `:username`?

```javascript
app.get("/profile/:username", (req, res) => {
  // Use req.params.username to access the username from the URL
  const username = req.params.username;
  // Now, you can do something with the username, like tell the client which user's profile they're viewing.
  res.send(`You are viewing the profile of ${username}`);
});
```

<details><summary><b>Answer</b></summary>
<p>

A placeholder for a variable value in the URL (it's a placeholder like with normal functions).

</p>
</details>

<br><br>

###### Question 17.

In the below example, what does `req.params.username` allow the user to access?

```javascript
app.get("/profile/:username", (req, res) => {
  // Use req.params.username to access the username from the URL
  const username = req.params.username;
  // Now, you can do something with the username, like tell the client which user's profile they're viewing.
  res.send(`You are viewing the profile of ${username}`);
});
```

<details><summary><b>Answer</b></summary>
<p>

It allows the user to access the actual value that was provided in the URL for that placeholder.

</p>
</details>

<br><br>

###### Question 18.

What is `req.params` in Express.js?

<details><summary><b>Answer</b></summary>
<p>

An object that holds values from variable parts of the URL known as route parameters.

</p>
</details>

<br><br>

###### Question 19.

When is `req.params` used?

<details><summary><b>Answer</b></summary>
<p>

When you want to capture and work with values from the URL in your routes.

</p>
</details>

<br><br>

###### Question 20.

Give an example of a URL with route parameters.

<details><summary><b>Answer</b></summary>
<p>

An example URL with route parameters is

```javascript
`http://example.com/users/:id`;
```

Where `:id` is a route parameter.

</p>
</details>

<br><br>

###### Question 21.

In the URL `http://example.com/users/:id`, what would `req.params.id` contain if the user visits `/users/123`?

<details><summary><b>Answer</b></summary>
<p>

`req.params.id` would contain `"123"`.

</p>
</details>

<br><br>

###### Question 22.

Why is `req.params` useful?

<details><summary><b>Answer</b></summary>
<p>

It allows one to make routes dynamic by capturing and using values from the URL, such as user IDs, product names, or other variable data.

</p>
</details>

<br><br>

###### Question 23.

Can an Express.js route have multiple route parameters?

<details><summary><b>Answer</b></summary>
<p>

Yes, an Express.js route can have multiple route parameters, each can be captured and accessible via `req.params`.

</p>
</details>

<br><br>

###### Question 24.

How might one install "morgan" via the terminal?


<details><summary><b>Answer</b></summary>
<p>

```javascript
npm install morgan
```

OR

```javascript
npm i morgan
```

</p>
</details>

<br><br>

###### Question 25.

What is "morgan"?

<details><summary><b>Answer</b></summary>
<p>

A popular middleware in Express.js used for logging HTTP requests, including details like request method, status code, and response time. It simplifies the process of tracking and analyzing server activity for debugging and monitoring purposes in web applications.

</p>
</details>

<br><br>

###### Question 26.

How is "morgan" implemented?

<details><summary><b>Answer</b></summary>
<p>

```javascript
app.use(morgan('dev'));
```

OR

```javascript
npm i express
```

</p>
</details>

<br><br>

###### Question 27.

What is the 'dev' argument in "morgan"?

<details><summary><b>Answer</b></summary>
<p>

The 'dev' argument in the "morgan" middleware is one of the predefined logging formats provided by "morgan." When you specify 'dev' as the argument, it configures "morgan" to log HTTP requests in a developer-friendly and concise format. Here's what the 'dev' format typically includes:

</p>
</details>

<br><br>

###### Question 28.

What four things does the 'dev' argument in "morgan" log?

<details><summary><b>Answer</b></summary>
<p>

1. HTTP METHOD
2. URL
3. Status Code
4. Response Time

For example:

`GET /users 200 32.123 ms`


</p>
</details>

<br><br>

###### Question 29.

What is wrong with this code?

```javascript
app.get("/", function (req, res) {
  const queryKey = Object.keys(req.query);
  const queryValue = Object.values(req.query);
  if (queryKey[0] == "genre") {
    const returnData = await genreQuery(queryValue[0]);
    res.send(returnData);
  } else {
    res.send("Welcome to the inspirational games API");
  }
});
```

<details><summary><b>Answer</b></summary>
<p>

Not an async function. The `await` keyword can only be used inside an async function.


</p>
</details>

<br><br>

###### Question 30.

What is `req.body` in Express.js?

<details><summary><b>Answer</b></summary>
<p>

`req.body` is an object that holds data sent by a client as part of an HTTP request's body. It is commonly associated with POST requests.

</p>
</details>

<br><br>

###### Question 31.

When is `req.body` typically used?

<details><summary><b>Answer</b></summary>
<p>

`req.body` is commonly used to handle data sent by clients via HTML forms or API requests.

</p>
</details>

<br><br>

###### Question 32.

When using `app.post` to make a route, what is one doing?

<details><summary><b>Answer</b></summary>
<p>

 Defining how the server should handle incoming HTTP POST requests. Specifically, specifying what should happen on the server when a client (e.g., a web browser or another application) makes a POST request to a particular URL path.

</p>
</details>

<br><br>

###### Question 33.

 How does one access data sent in the request body using req.body in an Express.js route handler?

<details><summary><b>Answer</b></summary>
<p>

```javascript
app.post('/submit', (req, res) => {
  const name = req.body.name; // Accessing the "name" property in req.body
  const email = req.body.email; // Accessing the "email" property in req.body
  // ... (use name and email data)
});
```

</p>
</details>

<br><br>

###### Question 34.

Inside an `app.post` route handler, how might one assign all the incoming JSON data to a variable?

<details><summary><b>Answer</b></summary>
<p>

```javascript
  const jsonData = req.body;
```

Where `method` is a HTTP method (e.g., GET, POST), `path` is the URL path, and `callback` is a function that handles the request and response.

</p>
</details>

<br><br>

###### Question 35.

How might one assign all of the keys (property names) from an object to a variable? (Not specific to Express.js)

<details><summary><b>Answer</b></summary>
<p>

```javascript
const keys = Object.keys(obj);
```

For example:

```javascript
const user = {
  name: 'John Doe',
  email: 'johndoe@example.com',
  age: 30
};

const keys = Object.keys(user);

console.log(keys); // Output: ['name', 'email', 'age']
```

</p>
</details>

<br><br>

###### Question 36.

How are query parameters typically included in a URL?

<details><summary><b>Answer</b></summary>
<p>

Query parameters are included in a URL by appending them after a question mark (`?`) and separating them with ampersands (`&`).
For example: `http://example.com/search?query=express&category=node`

</p>
</details>

<br><br>

###### Question 37.

 How can you access query parameters from the URL `http://example.com/search?query=express&category=node` using `req.query` in an Express.js route handler?

<details><summary><b>Answer</b></summary>
<p>

```javascript
const query = req.query.query;       // Accessing the "query" parameter
const category = req.query.category; // Accessing the "category" parameter
```
</p>
</details>

<br><br>

###### Question 38.

What would the output from `req.query` be when console logged, assuming it's in relation to the following URL?
`http://example.com/search?query=express&category=node`

<details><summary><b>Answer</b></summary>
<p>

```javascript
// { query: 'express', category: 'node' }
```
</p>
</details>

<br><br>

###### Question 39.

What would you use to get the values of an object's properties? (Not specific to Express.js)

<details><summary><b>Answer</b></summary>
<p>

```javascript
Object.values
```

For example:

```javascript
const person = {
  name: 'John',
  age: 30,
  city: 'New York'
};

const values = Object.values(person);
// values will be ['John', 30, 'New York']
```

</p>
</details>

<br><br>

###### Question 40.

Can `Object.values` work with objects that have nested properties?

<details><summary><b>Answer</b></summary>
<p>

Yes, for example:

```javascript
const car = {
  make: 'Toyota',
  model: 'Camry',
  specs: {
    engine: 'V6',
    horsepower: 268
  }
};

const specs = Object.values(car.specs);
// specs will be ['V6', 268]
```

</p>
</details>

<br><br>

###### Question 41.

What is `res.send`?

<details><summary><b>Answer</b></summary>
<p>

`res.send` is a method in Express.js used to send a response (data) back to the client's web browser or application.

</p>
</details>

<br><br>

###### Question 42.

How might one use `res.send` to send a simple text response?

<details><summary><b>Answer</b></summary>
<p>

```javascript
res.send('string')
```

</p>
</details>

<br><br>

###### Question 43.

How might one send JSON data as a response using `res.send`?

<details><summary><b>Answer</b></summary>
<p>

```javascript
const data = {
  name: 'John',
  age: 30
};
res.send(data);
```

</p>
</details>

<br><br>

###### Question 44.

What is the PATCH HTTP method used for?

<details><summary><b>Answer</b></summary>
<p>

The PATCH method is used to partially update an existing resource on the server.

</p>
</details>

<br><br>

###### Question 45.

How can one use the PATCH method in an Express.js route?

<details><summary><b>Answer</b></summary>
<p>

```javascript
app.patch
```

</p>
</details>

<br><br>

###### Question 46.

How can one use the DELETE method in an Express.js route?

<details><summary><b>Answer</b></summary>
<p>

```javascript
app.delete
```

</p>
</details>

<br><br>

###### Question 47.

When should one use PATCH instead of PUT in an API?

<details><summary><b>Answer</b></summary>
<p>

Use PATCH when you want to make partial updates to a resource (e.g., updating just one field), and use PUT when you want to replace the entire resource with a new version.

</p>
</details>

<br><br>

###### Question 48.

When using `app.delete`, `app.get`, `app.post` etc, why are we using the `app` keyword?

<details><summary><b>Answer</b></summary>
<p>

`app` is the instance of your Express application. When you create an Express application, you typically create it using the `express()` function, for example:

```javascript
const express = require('express');
const app = express();
```

</p>
</details>

<br><br>

###### Question 49.

What is `res.status` used for in Express.js?

<details><summary><b>Answer</b></summary>
<p>

`res.status` is used to set the HTTP status code for the response.

</p>
</details>

<br><br>

###### Question 50.

How can one set a specific HTTP status code using `res.status`?

<details><summary><b>Answer</b></summary>
<p>

```javascript
res.status(404); // Set the status code to 404 (Not Found).
```

</p>
</details>

<br><br>

###### Question 51.

Can one set a status code and send a response message in a single line of code?

<details><summary><b>Answer</b></summary>
<p>

Yes, for example:

```javascript
res.status(200).send('Success'); // Set the status code to 200 and send the message 'Success'.
```

</p>
</details>

<br><br>

###### Question 52.

How might one use `res.status` to indicate a successful operation (status code 200)?

<details><summary><b>Answer</b></summary>
<p>

```javascript
res.status(200).json({ message: 'Operation successful' }); // Set status code to 200 and send JSON response.
```
</p>
</details>

<br><br>

###### Question 53.

What does the `200` status code mean?

<details><summary><b>Answer</b></summary>
<p>

OK: This status code indicates that the request was successful, and the server has returned the requested data. It's often used for successful responses.

</p>
</details>

<br><br>

###### Question 54.

What does the `404` status code mean?

<details><summary><b>Answer</b></summary>
<p>

Not Found: This code signifies that the requested resource could not be found on the server. It's used when a URL or resource doesn't exist.

</p>
</details>

<br><br>

###### Question 55.

What does the `403` status code mean?

<details><summary><b>Answer</b></summary>
<p>

Forbidden: When the server understands the request but refuses to fulfill it due to insufficient permissions, it responds with a 403 status code.

</p>
</details>

<br><br>

###### Question 56.

What does the `500` status code mean?

<details><summary><b>Answer</b></summary>
<p>

Internal Server Error: This status code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request. It's used for general server errors.

</p>
</details>

<br><br>

###### Question 57.

How might one import functions from another `.js` file into one's project? (Not specific to Express.js)

<details><summary><b>Answer</b></summary>
<p>

```javascript
import {
  exampleFunctionOne,
  exampleFunctionTwo,
  exampleFunctionThree,
} from "./otherjsfile.js";
```

</p>
</details>

<br><br>
