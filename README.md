# 10-Calculator
Made a Web Application using the Express framework in Node.js

-> Here are some key learnings from building a calculator app using Node.js and Express:
1. Server-Side Programming: The calculator app is a server-side application where the calculations are performed on the server using JavaScript. This allows for more complex operations and ensures that the user's input is processed securely on the server.
2. Express Framework: Express is a popular framework for building web applications in Node.js. It provides a set of features and utilities to simplify the development process, such as routing, middleware handling, and serving static files.
3. Routing: Express allows you to define different routes for handling different HTTP requests. In the calculator app, we define two routes: one for handling the GET request to display the calculator form, and another for handling the POST request to process the calculation.
4. Form Handling: The calculator app uses a form to collect user input. The body-parser middleware is used to parse the form data and make it available in the req.body object. This allows us to access the input values in the POST request handler.
5. Switch Statement: The calculator app utilizes a switch statement to perform different calculations based on the selected operator. It evaluates the operator value and executes the corresponding calculation logic.
6. Sending Responses: The app sends the response back to the client using the res.send() method. It displays the result of the calculation or an error message if an invalid operator is selected.
7. Static File Serving: Express serves static files, such as CSS stylesheets and client-side JavaScript, using the express.static() middleware. In this case, the index.html file and any associated CSS or client-side JavaScript files are served as static files.
8. Starting the Server: The app starts the server by calling the app.listen() method, specifying the port number (3000 in this case). The server listens for incoming requests and responds accordingly.

-> In summary, this code sets up a web server that serves an index.html file for GET requests to the root path ("/"), and performs a calculation based on the values received in the request body for POST requests to the same path ("/"). The server listens on port 3000.
