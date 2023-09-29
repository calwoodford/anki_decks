<div align="center">
  <img height="60" src="https://miro.medium.com/v2/resize:fit:1400/1*XP-mZOrIqX7OsFInN2ngRQ.png">
  <h1>Express.js Questions and Answers</h1>
    <a href="https://ankiweb.net/shared/info/1982258792?cb=1695936303593"> Download the Anki deck here </a>
    <br><br>

<img src="../images/learning.gif" alt="Neo learning">

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
node -v
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

True

</p>
</details>

<br><br>

###### Question 6. 

How might one check the version of npm installed via the terminal?

<details><summary><b>Answer</b></summary>
<p>

```javascript
npm -v
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
const express = require('express');
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

What is `req`?

<details><summary><b>Answer</b></summary>
<p>

This is an object that represents the incoming HTTP request from the client, which includes information about the URL, headers, and more.

</p>
</details>

<br><br>

###### Question 15. 

What is `params`?

<details><summary><b>Answer</b></summary>
<p>

This is a property of the `req` object that specifically holds information about the parameters in the URL.

</p>
</details>

<br><br>

###### Question 16. 

In the below example, what is `:username`?

```javascript
app.get('/profile/:username', (req, res) => {
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
app.get('/profile/:username', (req, res) => {
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

###### Question 20. 

What is `req.params`?

<details><summary><b>Answer</b></summary>
<p>

An object that holds values from variable parts of the URL known as route parameters.

</p>
</details>

<br><br>

###### Question 21. 

When is `req.params` used?

<details><summary><b>Answer</b></summary>
<p>

When you want to capture and work with values from the URL in your routes.

</p>
</details>

<br><br>

###### Question 22. 

Give an example of a URL with route parameters.

<details><summary><b>Answer</b></summary>
<p>

An example URL with route parameters is 

```javascript
`http://example.com/users/:id`
```
Where `:id` is a route parameter.

</p>
</details>

<br><br>

###### Question 23. 

 In the URL `http://example.com/users/:id`, what would `req.params.id` contain if the user visits `/users/123`?

<details><summary><b>Answer</b></summary>
<p>

`req.params.id` would contain `"123"`.

</p>
</details>

<br><br>

###### Question 24. 

Why is `req.params` useful?

<details><summary><b>Answer</b></summary>
<p>

It allows one to make routes dynamic by capturing and using values from the URL, such as user IDs, product names, or other variable data.

</p>
</details>

<br><br>

###### Question 25. 

Can an Express.js route have multiple route parameters?

<details><summary><b>Answer</b></summary>
<p>

Yes, an Express.js route can have multiple route parameters, each can be captured and accessible via `req.params`.

</p>
</details>

<br><br>