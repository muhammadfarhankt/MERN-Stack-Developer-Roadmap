# MERN-Stack-Developer-Roadmap
MERN Stack Developer Roadmap. Full Stack Developer Roadmap from scratch.

# 1. HTML:

## Structure:
- Document Type Definition (DOCTYPE) declaration.
- Basic HTML elements like `<html>, <head>, <body>, <title>.`
- Semantic elements like `<h1>` for headings, `<p>` for paragraphs, `<ul>` and `<ol>` for lists, `<img>` for images, and `<a>` for links.
- Nesting elements to create complex website structures.
  
## Attributes:
- Common attributes like `id, class, src, href, and alt.`
- Using attributes to provide additional information or functionality to elements.
- Form elements like `<input>, <textarea>, <select>, and <button>.`
- Understanding form attributes like `type, name, and value.`

## Tables:
- Creating tables with `<table>`, `<tr>` (table row), and `<td>` (table data) elements.
- Using attributes like `colspan` and `rowspan` to span cells.


# 1.1 CSS:

## Selectors:
- Targeting elements by tag name (e.g., h1, p)
- Using class selectors (.myClass) and ID selectors (#uniqueID) for specific styling.
- Combining selectors for more precise targeting.
## Properties and Values:
- Basic properties like color, font-family, font-size, background-color, text-align, margin, and padding.
- Understanding units like pixels (px), percentages (%), and ems.
- Exploring other properties for borders, positioning, and more.
## Box Model:
- Content box, padding, border, and margin.
- Using properties like padding, border, and margin to control element layout.
## Intermediate CSS:
- Applying styles with classes and IDs for maintainability.
- Pseudo-classes (e.g., :hover, :active) and pseudo-elements (e.g., ::before, ::after) for dynamic styling.
## Basic layouts with floats or flexbox:
- Floats for basic two-column layouts.
- Flexbox for more complex and responsive layouts (flexibility).
## Responsiveness:
- Understanding the concept of responsive design for different screen sizes.
- Using media queries to adjust styles for mobile, tablet, and desktop.

## Additional Tips:

- Practice writing valid HTML code using a code validator.
- Use developer tools in your browser to inspect and modify HTML and CSS.
- Build small projects to solidify your understanding and explore different features.
- There are many resources available online and in libraries to learn HTML & CSS in more detail.

# 2. Bootstrap, Basic Javascript, DOM Manipulation

## Under Development!

# 3. Deep Dive into Javascript

### 1. Foundational Concepts:

- Data Types & Operators: Numbers, strings, booleans, null/undefined, various operators (arithmetic, assignment, logical, etc.).
- Variables & Scope: Understanding how variables are declared and accessed in different scopes (global, function, block).
  
### 2. DOM Manipulation:

- querySelector: Selecting elements by CSS selector.
- textContent: Getting/setting text content of elements.
- addEventListener: Attaching event listeners to elements.

### 3. Events:

- Event Propagation: Understanding how events bubble up the DOM tree.
- Event Bubbling & Capturing: Understanding the order in which event listeners are triggered.
- stopPropagation: Stopping event propagation from reaching further elements.
- Event target: Identifying the element that triggered the event.

### 4. Functions:

- Function Types: Function statements, expressions, anonymous functions.
- Function Parameters & Arguments: Understanding how arguments are passed to functions.

### 5. Control Flow:

- Loops: for, while, do-while loops for iterating over code blocks.
- Conditional Statements: if, else if, else for branching code execution.

### 6. Arrays & Iteration:

- Array Methods: map, filter, reduce, find, sort, etc. for array manipulation.
- Looping through Arrays: Using for loops or forEach method to iterate over arrays.

### 7. Objects:

- Object Creation: Creating objects with literals or constructors.
- Object Properties: Accessing and modifying object properties.

### 8. Execution Context & Memory Management:

- Memory Allocation: Phases involved in memory allocation for code execution.
- Synchronous vs Asynchronous: Single-threaded nature of JavaScript execution.

### 9. Advanced Functions:

- Higher-Order Functions: Functions that accept other functions as arguments or return functions.
- IIFE (Immediately Invoked Function Expression): Self-contained functions.

### 10. Callbacks & Promises:

- Callbacks: Passing functions as arguments to other functions.
- Promises: Asynchronous operation handling with Promise objects.

### 11. Additional Concepts (can be learned in parallel with previous sections):

- Strict Mode: Enabling stricter JavaScript behavior to avoid errors.
- Hoisting: Variable and function declaration behavior before execution.
- This Keyword: Understanding the this keyword behavior in functions and objects.
- Debugging Techniques: Using console.log, breakpoints, and debugger tools.

### 12. ES6 Features (can be learned after core concepts):

- Let & Const: Block-scoped variables with let and constant variables with const.
- Arrow Functions: Concise syntax for writing functions.
- Template Literals: String literals with embedded expressions.
- Destructuring: Extracting properties/elements from objects/arrays.
- Classes: Syntactic sugar for object-oriented programming.

### 13. Advanced Topics (for deeper understanding):

- Prototypes & Inheritance: Object inheritance mechanism in JavaScript.
- Closures: Functions that remember their outer scope.
- Garbage Collection: Automatic memory management in JavaScript.
- Event Loop & Microtasks: Deep dive into JavaScript's asynchronous execution model.
- DOM & BOM: Interacting with the web page structure (DOM) and browser functionalities (BOM).
- Spread & Rest Operators: Using ... operator for spreading elements and collecting remaining arguments.
- Advanced Data Structures: Sets, Maps, Iterators, Generators for complex data management.

# 4. Learn Web Fundamentals & Node.js Express.js & Sample Login Project
### (Research & Learn following topics in detail. Watch videos & Read documentations / tutorial sites)

### 1. URL Structure: Break down the components of a URL (Uniform Resource Locator):
- Scheme: The protocol (e.g., http:, https:).
- Host: The domain name or IP address of the server.
- Path: The specific resource being requested.
- Query String: Optional parameters appended to the URL after a question mark (?).
- Fragment: Optional anchor part within a document (e.g., for scrolling to a specific section).
  
### 2. HTTP Fundamentals: Grasp the foundation of web communication:
- HTTP Protocol: Understand the Hypertext Transfer Protocol, the core protocol for communication between web clients (browsers) and servers. Learn about request methods (GET, POST, PUT, DELETE), request and response headers, and status codes.
- Stateless vs. Stateful Communication: Differentiate between stateless HTTP requests (independent) and stateful communication (where the server needs to maintain information about a user session across requests).
  
### 3. Session Management: Explore techniques for maintaining state in web applications:
- Sessions: Understand how sessions enable applications to store user-specific data (e.g., login status, preferences) between requests. Learn about different session storage mechanisms like cookies, server-side storage (in-memory or database), or session management frameworks.
- Cookies: Familiarize yourself with cookies, which are small pieces of data sent by a server and stored on the client-side (user's browser) that can be used to maintain some state information between requests.
  
### 4. HTTP Methods: Deepen your understanding of common HTTP request methods:
- GET: Used to retrieve data from a server (e.g., fetching a web page).
- POST: Used to submit data to a server (e.g., sending a form submission).
- PUT: Used to update existing data on a server.
- DELETE: Used to delete data from a server.
- Additional Methods: Explore other HTTP methods like PATCH (partial updates), HEAD (retrieve header information only), and OPTIONS (discover server capabilities).
  
### 5. HTTP Versions: Understand the different versions of the HTTP protocol and their key features:
- HTTP/1.1: The most widely used version, supporting persistent connections (keeping connections open for multiple requests).
- HTTP/2: A more efficient version with features like multiplexing (sending and receiving multiple requests/responses concurrently over a single connection) and header compression.

### 6. Node.js Foundational Concepts:

- What is Node.js: Understand the concept of Node.js and its role in server-side development.
- Why V8 Engine: Learn why Node.js leverages Google's V8 engine for efficient JavaScript execution.
- Advantages & Disadvantages of Node.js: Weigh the pros and cons of using Node.js for your project.
-  REPL (Read-Eval-Print-Loop): Experiment with Node.js interactively in the terminal.
-  CLI (Command Line Interface): Learn basic Node.js commands for running scripts and interacting with the environment.
-  NPX: Understand how to use npx to run npm packages without global installation (optional).
<br>

![image](https://github.com/muhammadfarhankt/MERN-Stack-Developer-Roadmap/assets/50117098/010d44f5-26dc-4ba9-975e-fa8df8cdecd5)
<br/> <center>Credits: Litslink</center>

### 7. Core Functionalities:

- Globals: Become familiar with built-in objects available in every Node.js program (e.g., __dirname, __filename).
- Module: Grasp the concept of modules as reusable units of code in Node.js.
- Process: Understand the process object that represents the currently running Node.js process.
- Node Module System: Learn about the CommonJS module system for organizing and managing code. This includes:
- Core Modules: Built-in modules shipped with Node.js (e.g., http, fs, path).
- Local Modules: Modules you create within your project.
- Third-party Modules: Modules installed from the npm registry using npm install.
- require: Importing modules for use in your code.
- module.exports: Exporting objects or functions from modules. (Optional: Explore ESM for modern projects)

### 8. Package Management:

- NPM: Learn about the Node Package Manager (npm) for installing and managing third-party modules.
- npm init: Understand how to initialize a package.json file for your project, which stores dependencies and configuration.
- npm install (or i): Learn how to install npm packages using these commands.
- package.json & package-lock.json: Understand the role of these files in managing project dependencies and ensuring reproducible builds.

### 9. Core Node.js Functionality:

- Event Loop: Grasp the fundamental concept of the event loop in Node.js for handling asynchronous operations.
- Events: Learn about events as a signaling mechanism for communication between different parts of your application.
- Event Emitter: Understand the concept of event emitters as objects that can emit and listen for events.

### 10. Building a Simple Node.js Application:

- Creating a Simple Server: Write your first Node.js application to serve static files or handle basic requests.
- Error Handling: Implement mechanisms to handle errors gracefully in your Node.js applications.

###  11. Advanced Concepts:

- Streams: Delve into the concept of streams for efficient handling of data flowing in chunks. (Writable, Readable, Duplex, Transform)
- Child Processes: Explore how to spawn new processes to execute tasks outside the main Node.js process. This can be useful for CPU-intensive operations.
- Worker Threads (Optional): Understand worker threads as a technique for simulating multithreading in Node.js for CPU-bound tasks.
- Cluster (Optional): Learn about scaling your application using multiple worker processes with the cluster module.

### 12. Security Concepts:

- Validation: Learn how to ensure data meets specific requirements before processing to prevent vulnerabilities.
- CORS (Cross-Origin Resource Sharing): Understand how to enable cross-domain requests between different web origins.
- XSS (Cross-Site Scripting): Learn about XSS vulnerabilities and how to prevent them in your applications.
- CSRF (Cross-Site Request Forgery): Understand CSRF vulnerabilities and how to prevent them in your applications.
- SQL Injection (Optional): Learn about SQL injection vulnerabilities and how to prevent them using prepared statements.

### 13. MVC Architecture

![image](https://github.com/muhammadfarhankt/MERN-Stack-Developer-Roadmap/assets/50117098/239789a6-f36e-46ea-a266-c94ec74e7136)
<br> Source : [`Medium`](https://medium.com/@sadikarahmantanisha/the-mvc-architecture-97d47e071eb2/)

- Design pattern for structuring web applications.
- Separates concerns: Model, View, and Controller.

#### Need for Architecture

- Improves maintainability by keeping code organized.
- Enhances code reusability by separating core functionalities.
- Makes testing easier by isolating components.
- Promotes scalability for complex applications.

#### MVC Components:

#### Model
  - Handles data and business logic.
  - Interacts with databases or APIs.
  - Defines data structures and validation rules.
### View
  - Presents data to the user.
  - Uses templates or UI frameworks for dynamic content.
  - Excludes business logic.
#### Controller
  - Mediates between Model and View.
  - Handles user interactions (clicks, submissions).
  - Retrieves data from the Model and updates the View.

### 14. Building a Web Application with Express:

- Express Introduction: Learn about the Express.js framework for simplifying web application development on top of Node.js.
- Installing Express: Understand how to install Express using npm install express --save.
- Core Express: Explore core functionalities of Express:
- App Creation: Creating an Express application instance.
- Routing: Defining routes to handle different URL paths and HTTP methods (GET, POST, PUT, etc.).
- Middleware: Using middleware functions for common tasks like request parsing, logging, and error handling.
- Building with Express: Start creating web applications using Express, leveraging features like routing, middleware, and templating engines (Recommended: EJS).

### 15. Additional Concepts:

- Static Files: Learn how to serve static files (e.g., HTML, CSS, JavaScript) from your application using Express.
- API Development: Understand how to build APIs (Application Programming Interfaces) using Express to provide programmatic access to your application's functionality.
- Sessions & Cookies: Explore user session management and cookie handling techniques in Express applications.
- Database Integration: Learn how to integrate databases (like MongoDB, MySQL) with your Node.js application for data persistence. (Optional: Explore various database drivers)
- Templating Engines (Optional): Understand how to use templating engines (e.g., EJS) to generate dynamic HTML content in your Express applications.

### 16. Built-in Modules:

- Explore commonly used built-in modules: This section can cover a brief overview of a few important built-in modules, but you can delve deeper as needed. Some examples include:

#### Essential Modules :

- http: This module provides the foundation for creating HTTP servers and handling requests/responses. It allows you to build web servers, APIs, and other network applications.
- fs (file system): This module offers functions for interacting with the file system. It includes both synchronous and asynchronous versions for reading, writing, creating, deleting, and manipulating files and directories.
- path: This module provides utilities for working with file and directory paths. It helps you construct valid paths, manipulate path components (dirname, basename, etc.), and ensure platform-compatibility across different operating systems.
- os: This module provides information about the operating system your Node.js application is running on. You can access details like the operating system name, architecture, uptime, and host name.
- events: This module serves as the core building block for implementing the event-driven programming paradigm in Node.js. It allows you to create event emitters, listen for events, and trigger callbacks when those events occur.

#### Network Modules:

- https: This module builds upon the http module and provides functionalities for creating secure HTTP servers using TLS/SSL encryption.

#### Utility Modules:

- url: This module provides utilities for parsing and manipulating URLs. It helps you extract components like protocol, hostname, port, path, and query string from URLs.
- querystring: This module deals with parsing and stringifying query strings, which are key-value pairs appended to URLs. It's useful for processing data sent through HTTP GET requests or form submissions.
- string_decoder: This module assists in decoding Buffers (used for binary data) into strings using appropriate character encodings.
- util: This module offers various utility functions for common tasks like inspecting objects, creating unique identifiers (UUIDs), and formatting error messages.

#### Modules for Working with Data:

- buffer: This module represents binary data chunks used for efficient data handling. Buffers are often used in conjunction with network I/O or stream processing.
- stream: This module provides the foundation for working with streams of data. Streams allow you to process data in chunks as it becomes available, rather than waiting for the entire data set to load at once. This is particularly useful for handling large files or real-time data sources. There are four types of streams in Node.js:
Readable streams, Writable streams, Duplex streams and Transform streams.

### 17. Node.js Core Architecture: (Node.js Runtime Architecture)

- Single-Threaded: Node.js uses a single-threaded event loop model, similar to what we discussed earlier.
- Non-Blocking I/O: Node.js employs a non-blocking I/O model to handle multiple requests efficiently.
- Event Loop: The event loop remains the heart of Node.js, continuously monitoring events and executing callbacks.
- Event Queue: Events are placed in an event queue for processing by the event loop.
- Callbacks: Callback functions are used to handle asynchronous operations.
- libuv: Here's where libuv comes into play. It's a multi-platform C library embedded within Node.js. libuv provides the underlying functionality for:
  - Asynchronous I/O: libuv efficiently handles various asynchronous I/O operations like network communication, file system access, DNS resolution, etc. It interacts with the operating system's I/O mechanisms to initiate these operations and manages them without blocking the event loop.
  - Event Loop Implementation: libuv provides the core implementation of the event loop, including managing the event queue, scheduling callbacks for execution, and ensuring smooth operation.
  - Platform Abstraction: libuv acts as an abstraction layer, providing a consistent API for asynchronous I/O across different operating systems (Windows, Linux, macOS, etc.). This allows Node.js code to work seamlessly without OS-specific modifications.

#### Working:

1. Request Arrives: When a request arrives (e.g., HTTP request), it's added to the event queue.
2. Event Loop: The event loop detects the new event (request) in the queue.
3. Synchronous Work: If the request involves any synchronous tasks, the event loop handles those first.
4. Non-Blocking Operations (with libuv): If the request requires asynchronous operations:
    - libuv steps in. It initiates the operation (e.g., database query, network request) using the operating system's I/O mechanisms.
    - The event loop doesn't wait for the operation to finish.
    - The event loop moves on to the next event in the queue.
5. Callbacks: When the asynchronous operation completes, it triggers a callback function that's been provided.
6. Callback Execution: The event loop adds the callback function to the event queue.
7. Event Loop Continues: The event loop continues monitoring the queue and executing tasks (including callbacks) as they become available.

#### Benefits:

- Efficiency: Non-blocking I/O (powered by libuv) allows Node.js to handle many concurrent requests efficiently without blocking the thread.
- Scalability: Node.js can handle a high volume of connections because it doesn't have to create a separate thread for each request.
- Simplicity: The single-threaded model with event loop (managed by libuv) makes Node.js easier to learn and program compared to multi-threaded architectures.
- Cross-Platform Compatibility: libuv's platform abstraction layer ensures consistent behavior across different operating systems.

#### Considerations:

- CPU-Bound Tasks: Node.js isn't ideal for CPU-intensive operations as there's only one thread to execute them. Techniques like worker threads can be used to mitigate this.
- Error Handling: Proper callback and error handling are crucial in Node.js applications to avoid issues like "callback hell."

#### In essence, libuv acts as the workhorse behind Node.js's asynchronous I/O capabilities, enabling the efficient execution of the event loop model and making Node.js well-suited for I/O-bound applications.

## Under Development!

# 5. MongoDB Database

# 6. Mini Project - Users & Admin Managment System

# 7. E-Commerce Project Planning & Designing
### Database Design, API Documentation & Modules List

# 8. Project Week 1
## User 

# 9. Project Week 2

# 10. Project Week 3

# 11. Project Week 4

# 12. Project Week 5 : Hosting

# 13 - 15. Data Structures Week 1 - 3

# 16. SQL Database

# 17. React Fundamentals
### Mini Project - Todo Application

# 18. React Mini Projects
### Mini Projects - NETFLIX & OLX Clone Mini Projects

# 19. React 3 - Redux Toolkit
### Mini Project - User Managment System

# 20. Revision Week

# 21. Project Design

# 22. Project Week 1

# 23. Project Week 2

# 24. Project Week 3

# 25. Project Week 4

# 26. Project Week 5 : Hosting

# 27. Revision 1

# 28. Revision 2

# 29. Final Interview Tips















