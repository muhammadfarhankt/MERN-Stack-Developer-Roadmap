# MERN-Stack-Developer-Roadmap

### MERN Stack Developer Roadmap. Full Stack Developer Roadmap from scratch.

#### Research & Learn topics in detail. Watch videos & Read documentations / tutorial sites.
#### Under Development (Star this repository for future references)

<details> 
  <summary> <h2> 1. HTML (Click for expanding)</h2> </summary>
  
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

</details>




<details> 
  
  <summary> <h2> 2. Bootstrap, Basic Javascript, DOM Manipulation </h2> </summary>

### 1. JavaScript & DOM Manipulation: 

- Focus on basic JavaScript concepts through tutorials and practice.
- Learn DOM manipulation methods (e.g., getElementById, querySelector) to control HTML elements. This will be crucial for interacting with Bootstrap components later.

### 2. Bootstrap in Detail :

- Grid System:
  - Understand Bootstrap's grid system for creating responsive layouts.
  - Learn about grid classes (columns, rows), responsive breakpoints (e.g., .col-sm-4 for small screens), and how they define website structure.
  - Practice creating layouts with different column configurations for various screen sizes.
- Components:
  - Explore Bootstrap's pre-built components like buttons, navigation bars, cards, modals, etc.
  - Learn how to integrate these components into your HTML code using their class names and customization options.
  - Practice adding and customizing components to enhance your website's functionality and user interface.
- Utilities:
  - Discover Bootstrap's utility classes for styling (margins, padding, colors, positioning).
  - Learn how to use these utilities to fine-tune the appearance of your website elements without extensive custom CSS.
  - Explore responsive utilities like .d-none and .d-flex to show/hide elements and adapt layout for different devices.
- Include Bootstrap's CSS library by adding to the <head> section of your index.html: 
  <br> `<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">`
- Include Bootstrap's JavaScript library for interactive components.
<br> `<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>`

### 3. Build with HTML, CSS & Bootstrap :

- Create basic HTML structure with header, navigation, content sections, and footer.
- Apply CSS styles using Bootstrap's pre-built classes or custom styles for layout and design.
- Integrate Bootstrap components to enhance user experience (buttons, forms, carousels, etc.).
- Utilize Bootstrap's grid system and utilities to ensure your website is responsive and adapts to different screen sizes.

### 4. Responsiveness with Media Queries : 

- While Bootstrap provides a responsive foundation, you can further enhance responsiveness with media queries.
- Learn how to use media queries in your CSS to adjust layouts for specific screen sizes (desktop, tablet, mobile) on top of Bootstrap's built-in responsiveness.
- Use media queries to fine-tune the behavior of Bootstrap components or override default styles for a more customized responsive experience.

### 5. Additional Learning :

- Delve deeper into DOM manipulation techniques for dynamic content changes based on user interactions or events (e.g., adding/removing elements, updating content).
- Explore advanced selectors for more precise element selection in your JavaScript code when working with Bootstrap components.
- Learn about addEventListener to attach event handlers to elements and respond to user interactions (clicks, scrolling, form submissions, etc.). This can be used to trigger actions within Bootstrap components.

### 6. Clone a Public Website

- Start with basic HTML structure for each page, including header, navigation, content sections, and footer.
- Apply CSS styles for typography, colors, backgrounds, and layout using Bootstrap's pre-built classes or custom styles.
- Integrate Bootstrap components to enhance user experience (buttons, forms, carousels, etc.).

#### Responsiveness with Media Queries:

- Implement media queries to adjust your website's layout for different screen sizes (desktop, tablet, mobile).
- Use responsive utilities like .d-none and .d-flex to show/hide elements and adapt layout for different devices.

### 7. Build a Personal Website with Template

- Template Selection:
  
  - Choose a website template that aligns with your personal brand and style (e.g., portfolio, blog) from free or paid sources like Bootstrap Themes, ThemeForest, etc.

- Customize the Template:

  - Replace placeholder content with your own text, images, and videos.
  - Modify the layout and styles using the template's settings or custom CSS to reflect your preferences.

- Enquiry Form with Validation:

  - Integrate a form with fields for name, email, message, etc.
  - Implement JavaScript validation to ensure users enter required information and provide error messages for invalid input.

- Integrate Contact Form:
  - Within the contact form section (`<section id="contact">...</section>`), create an HTML form:

```bash
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        /* Add custom styles for error messages */
        .error-message {
            color: red;
            font-size: 0.875rem; /* Adjust font size as needed */
        }
    </style>
</head>
<body>

<section class="container mt-5">
    <h2>Contact Form</h2>
    <form id="contact-form">
        <div class="form-group mb-3">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" class="form-control" required>
            <div id="name-error" class="error-message"></div>
        </div>
        <div class="form-group mb-3">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" class="form-control" required>
            <div id="email-error" class="error-message"></div>
        </div>
        <div class="form-group mb-3">
            <label for="message">Message:</label>
            <textarea id="message" name="message" class="form-control" rows="5" required></textarea>
            <div id="message-error" class="error-message"></div>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
    </form>
</section>

<footer class="container py-4 text-center">
    <!-- Footer content -->
</footer>

<script>
    // --- Form Validation ---

    const form = document.getElementById('contact-form');
    const nameInput = document.getElementById('name');
    const emailInput = document.getElementById('email');
    const messageInput = document.getElementById('message');
    const submitButton = document.querySelector('form button');

    function validateForm() {
        let isValid = true;

        // Name Validation
        if (nameInput.value.trim() === '') {
            nameInput.classList.add('is-invalid'); // Add Bootstrap's invalid class
            document.getElementById('name-error').textContent = 'Please enter your name.'; // Display error message
            isValid = false;
        } else {
            nameInput.classList.remove('is-invalid'); // Remove Bootstrap's invalid class
            document.getElementById('name-error').textContent = ''; // Clear error message
        }

        // Email Validation (Using regular expression)
        const emailRegex = /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
        if (!emailRegex.test(emailInput.value)) {
            emailInput.classList.add('is-invalid'); // Add Bootstrap's invalid class
            document.getElementById('email-error').textContent = 'Please enter a valid email address.'; // Display error message
            isValid = false;
        } else {
            emailInput.classList.remove('is-invalid'); // Remove Bootstrap's invalid class
            document.getElementById('email-error').textContent = ''; // Clear error message
        }

        // Message Validation
        if (messageInput.value.trim() === '') {
            messageInput.classList.add('is-invalid'); // Add Bootstrap's invalid class
            document.getElementById('message-error').textContent = 'Please enter your message.'; // Display error message
            isValid = false;
        } else {
            messageInput.classList.remove('is-invalid'); // Remove Bootstrap's invalid class
            document.getElementById('message-error').textContent = ''; // Clear error message
        }

        return isValid;
    }

    // --- Form Submission Handling ---
    form.addEventListener('submit', function(event) {
        event.preventDefault(); // Prevent default form submission

        if (validateForm()) {
            // If form is valid, submit the form data
            const formData = new FormData(form);

            // AJAX request to submit form data to server
            fetch('YOUR_SERVER_ENDPOINT', {
                method: 'POST',
                body: formData
            })
            .then(response => {
                // Handle response from server
                if (response.ok) {
                    // Clear form inputs
                    nameInput.value = '';
                    emailInput.value = '';
                    messageInput.value = '';

                    // Optionally display success message or redirect to a thank you page
                    alert('Form submitted successfully!');
                } else {
                    // Handle error response from server
                    alert('Failed to submit form. Please try again later.');
                }
            })
            .catch(error => {
                // Handle network errors or other exceptions
                console.error('Error:', error);
                alert('An error occurred while submitting the form. Please try again later.');
            });
        }
    });
</script>

</body>
</html>
```

- Social Media Links & Contact Details:

  - Add social media icons linking to your profiles on platforms like LinkedIn, Twitter, etc.
  - Include clear contact information (email address, phone number, etc.) to facilitate communication.


### 8. Website Performance Optimization

- Learn about Lighthouse:
  - Go through the guide at https://developer.chrome.com/docs/lighthouse/overview to understand how Google's Lighthouse tool evaluates website performance.
- Run Lighthouse Audit:
  - Use Lighthouse (integrated in most browsers' developer tools) to assess your website's performance metrics like Largest Contentful Paint (LCP), First Input Delay (FID), and Cumulative Layout Shift (CLS).
- Improve Performance:

  - Based on Lighthouse recommendations, optimize your website for speed and user experience.
  - Consider strategies like image optimization, code minification, leveraging browser caching, etc. (Resources available online)

### 9. CDNs (Content Delivery Networks)

- Geographically distributed servers caching website content for faster loading times.
- Benefits for HTML pages:
  - Faster loading: Serves content from closer servers, improving website speed globally.
  - Reduced server load: Handles traffic, reducing pressure on your main server.
  - Improved scalability: Handles traffic spikes for better website performance.
  - Increased availability: Redundancy ensures content delivery even if a server goes down.
  - Enhanced security: Some CDNs offer protection from malicious attacks.
- Importing from CDN: Use <link> or <script> tags with the CDN URL for content (CSS, JS libraries).
  
</details>



<details> 
  <summary> <h2> 3. Deep Dive into Javascript </h2> </summary>

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

</details>

<details> 
  <summary> <h2> 4. Learn Web Fundamentals & Node.js Express.js & Sample Login Project</h2> </summary>

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

</details>

<details> 
  <summary> <h2> 5.  MongoDB Database </h2> </summary>

### 1. Introduction

- SQL vs. NoSQL: Understand the key differences between relational databases (SQL) and document-oriented databases (NoSQL) like MongoDB.
- What is MongoDB? Gain a basic understanding of MongoDB, its purpose, and its core features.
- Run on JS Engine: Briefly explore how MongoDB leverages JavaScript for data manipulation and querying.

### 2. Core Concepts

- Non-relational Document Based: Delve deeper into the concept of document-oriented databases and how data is stored in MongoDB documents (JSON-like structures).
- Advantages & Disadvantages: Weigh the pros and cons of using MongoDB for your project.
- BSON: Learn about BSON (Binary JSON), the data format used internally by MongoDB for efficient storage and transmission.
- MongoDB Structure: Understand the fundamental structure of MongoDB, including databases, collections (akin to tables in SQL), and documents.
- MongoDB Architecture: Explore the core architecture of MongoDB, including the server process, storage engines, and communication protocols.

### 3. Data Manipulation

- JSON vs BSON: Differentiate between JSON and BSON, understanding their similarities and the role of BSON in MongoDB.
- MongoDB Shell: Get familiar with the MongoDB shell, a command-line interface for interacting with your MongoDB instance.
- CRUD Operations: Master the fundamental CRUD (Create, Read, Update, Delete) operations for working with documents in MongoDB collections.
- Cursors: Learn how cursors are used to iterate through query results in MongoDB.
- Understand methods like `toArray` and `forEach` for working with cursor data.

### 4. Data Types and Storage

- Data types in MongoDB (BSON): Explore the various data types supported by MongoDB, including their BSON representations (e.g., `ObjectId, timestamps, strings, arrays`, etc.).
- Storage Engines: Understand the different storage engines available in MongoDB (e.g., WiredTiger, in-memory) and their characteristics.
- GridFS: Learn about GridFS, a file storage solution for storing large files efficiently within MongoDB.

### 5. Querying and Filtering

- Finding / Querying: Explore various techniques for querying and filtering documents in MongoDB using the find method.
- Learn operators like `$gt, $lt, $eq,` and logical operators like `$and, $or.`
- Understand concepts like projection, filtering with the find method, and method chaining for complex queries.
- Counting Documents: Learn methods like count to retrieve the number of documents in a collection.
- Sorting and Limiting: Explore functionalities like sort and limit to order and limit the number of documents returned in a query.

### 6. Advanced Operations

- Aggregation Framework: Delve into the Aggregation Framework for performing complex data transformations and aggregations on collections.
- Understand stages like `$match, $group, $sort, $count, and $lookup` for manipulating and combining data.
- Indexes: Learn about indexes, data structures that enhance query performance by enabling faster retrieval of specific document fields.
- Explore creating indexes, their types (single field, compound, etc.), and managing them (dropping, renaming).

### 7. Data Modeling

- Schema (Optional): Understand the concept of schema in MongoDB, its pros and cons, and how it can guide data structure design.
- Relationships: Explore different approaches for modeling relationships between documents in MongoDB (embedding vs. referencing).
- Learn about one-to-one, one-to-many, many-to-many relationships and their implementation strategies.

### 8. Scalability and Replication

- Replication: Understand the concept of replication for ensuring data availability and redundancy.
- Explore replica sets, their architecture (primary, secondary nodes), election process, and advantages.
- Sharding: Learn about sharding, a technique for distributing data across multiple servers (shards) for horizontal scaling and handling large datasets.
- Understand sharding architecture (mongos, config servers), shard key selection, and balancing mechanisms.

### 9. Administration and Monitoring

- MongoDB Drivers: Learn about drivers, software libraries that interact with MongoDB from various programming languages.
- Capped Collections: Explore capped collections, a special type of collection with a fixed size, useful for data streams or logs.
- Profiling: Understand how to use the profiler to monitor MongoDB performance and identify potential bottlenecks.
- Explain: Learn about the explain command used to analyze query execution plans and optimize performance.

### 10. Advanced Topics

- Soft Deleting: Learn techniques for "soft deleting" documents in MongoDB, marking them inactive instead of permanent removal.
- Interview Questions: Explore common MongoDB interview questions to prepare for technical assessments.
- Examples: Optimizing slow queries, handling large files, condensing data volumes, searching text, schema evolution, backup and restore strategies, etc.

### 11. Good to Know

- Atomicity: Understand the concept of atomicity in database transactions and how MongoDB handles operations.
- Type Bracketing: Learn about type bracketing, a technique for explicitly specifying data types in queries for better optimization.
- Dot Notation: Deepen your understanding of dot notation for accessing nested fields within documents.
- Cursor Behavior: Explore advanced cursor functionalities like timeouts, batching, and closing connections efficiently.
- Aggregation Pipeline: Gain further insights into the Aggregation Pipeline, including stages, performance considerations, and handling large datasets.
- Retryable Writes and Reads: Learn how MongoDB handles retries for failed write and read operations.

### 12. Additional Concepts

- CRUD Concepts: Revisit CRUD operations at a deeper level, understanding their implications on data consistency and performance.
- B-Tree: Explore B-Tree data structures, the foundation for indexing in MongoDB, and how they facilitate efficient data retrieval.
- ACID Compliance: Understand the concept of ACID transactions (Atomicity, Consistency, Isolation, Durability) and how MongoDB handles these properties.

### 13. Frameworks and Tools

- Mongoose (This framework will be using in our First E Commerce Project): Learn about Mongoose, a popular ODM (Object Data Modeling) library for interacting with MongoDB from Node.js, providing a more object-oriented approach.

### 14. Security

- Network Components: Understand the role of network components like load balancers and firewalls in securing your MongoDB deployment.
- CAP Theorem: Explore the CAP theorem (Consistency, Availability, Partition Tolerance) and its implications for distributed databases like MongoDB.
- Firewall: Learn about configuring firewalls to restrict access to your MongoDB instance.

### 15. Administration Tools 

- Mongo Utilities: Explore various command-line utilities like `mongoexport, mongoimport, mongodump, mongorestore`, etc., for data manipulation, backup, and restoration.
- Monitoring Tools (Optional): Learn about tools like `mongostat, mongotop, and mongooplog` for monitoring server performance, active connections, and operation logs.

### 16. Advanced Deployment (Optional)

- Clustered Collections: Understand clustered collections, a storage optimization technique for frequently accessed data together on disk.
- Write-Ahead Logging (WAL): Explore the Write-Ahead Logging (WAL) mechanism used by MongoDB to ensure data durability.

</details>

<details> <summary> <h2> 6. Mini Project - Users & Admin Managment System (Under Development) </h2> </summary>

</details>

<details> <summary> <h2> 7. E-Commerce Project Planning & Designing (Under Development) </h2> </summary>

### Database Design, API Documentation & Modules List

</details>

<details> <summary> <h2> 8. Project 1 <h2> (Under Development) </h2> </summary>

### User

### Admin

</details>

<details> <summary> <h2> 9. Project 2 (Under Development) </h2> </summary>

</details>

<details> <summary> <h2> 10. Project 3 (Under Development) </h2> </summary>

</details>

<details> <summary> <h2> 11. Project 4 - Project Completion (Under Development) </h2> </summary>

</details>

<details> <summary> <h2> 12. Project 5 - Hosting (Under Development) </h2> </summary>

</details>

## 13 - 15 [Data Structures and Algorithms Roadmap. 3 Weeks (Basics, Intermediate, Advanced)](https://github.com/muhammadfarhankt/Data-Structures-Algoithms-Resource-for-Beginners/)

<details>
<summary><h2>16. Learn SQL with PostgreSQL</h2></summary>

#### Understanding SQL vs. NoSQL
- **Relational (SQL) Databases**: Store data in tables with rows and columns.
  - Examples: PostgreSQL, MySQL.
- **Non-Relational (NoSQL) Databases**: Store data in various formats like JSON, key-value pairs, graphs, or documents.
  - Examples: MongoDB, Redis.
- **Web-scaled**: Learn how databases handle large amounts of data across many servers.
- **When to Use SQL vs. NoSQL**: SQL for structured data and complex queries, NoSQL for flexible, large-scale data storage.

#### SQL Data Types
- **null**: Represents missing or undefined data.
- **bit**: Stores binary values (0 or 1).
- **int**: Stores integer numbers.
- **real / float**: Stores floating-point numbers.
- **char, varchar, text**: Store text data.
  - `char` is fixed-length.
  - `varchar` is variable-length.
  - `text` is for long texts.
- **boolean**: Stores true/false values.
- **date, datetime, timestamp**: Store date and time information.
- **xml/json**: Store XML or JSON data.

#### SQL Operators
- **Arithmetic**: +, -, *, / (addition, subtraction, multiplication, division).
- **Logical**: AND, OR, NOT (used in conditions).
- **Comparison**: =, <>, >, <, >=, <= (comparing values).
- **Bitwise**: &, |, ^ (operations on binary representations).

#### PostgreSQL-Specific Data Types
- **interval**: Time intervals.
- **point**: Geometric points.
- **bigserial**: Auto-incrementing large integers.
- **Custom Types**: Create your own data types.

#### Database Fundamentals
- **Client/Server Model**: The database server manages data, clients connect to perform operations.
- **Database Cluster**: A collection of databases managed by a single server instance.
- **Constraints**: Rules to ensure data integrity.
  - **UNIQUE**: No duplicate values allowed.
  - **NOT NULL**: Data must be present.
  - **PRIMARY KEY**: Unique identifier for table rows.
  - **FOREIGN KEY**: Links to data in another table.
  - **CHECK**: Custom conditions for data.

#### SQL Commands and Migrations
- **List Databases**: Show all databases.
  - Command: `\l` in psql.
- **Connect to Database**: Use to switch databases.
  - Command: `\c <dbname>` in psql.
- **List Tables**: Show all tables in the current database.
  - Command: `\dt` in psql.
- **Create Database/Table**: Define new databases and tables.
  - Example: `CREATE DATABASE <name>;` `CREATE TABLE <name> (...);`.
- **Drop Database/Table**: Remove databases and tables.
  - Example: `DROP DATABASE <name>;` `DROP TABLE <name>;`.
- **Migrations**: Version control for database changes.
  - **Add/Delete**: Add or remove columns or tables.
  - **Up/Down Migration**: Apply or rollback changes.

#### SQL Functions and Clauses
- **SELECT**: Retrieve data from tables.
- **LIMIT**: Restrict the number of rows returned.
- **OFFSET**: Skip a number of rows before returning the data.
- **AS**: Rename columns or tables in the result set.
- **DISTINCT**: Return unique values only.
- **GROUP BY**: Group rows that have the same values in specified columns.
- **HAVING**: Filter groups based on conditions.
- **JOIN**: Combine rows from multiple tables.
  - **INNER JOIN**: Only matching rows.
  - **LEFT JOIN**: All rows from the left table, with matching rows from the right.
  - **RIGHT JOIN**: All rows from the right table, with matching rows from the left.
  - **FULL JOIN**: All rows when there is a match in either table.
- **WHERE**: Filter rows based on conditions.
- **ORDER BY**: Sort rows by specified columns.

#### Views and Indexes
- **Views**: Virtual tables created from queries.
  - **CREATE VIEW**: Define a view.
  - **Materialized View**: Stores results of the view query.
- **Indexes**: Speed up searches by creating a fast lookup.
  - **AUTO_INCREMENT**: Automatically increment values for a primary key.

#### Advanced SQL Functions
- **Aggregate Functions**: Perform calculations on sets of values.
  - Examples: `AVG`, `SUM`, `MIN`, `MAX`, `COUNT`.
- **Scalar Functions**: Operate on individual values.
  - Examples: `UPPER`, `CONCAT`, `SUBSTR`.

#### SQL Commands Categories
- **DDL (Data Definition Language)**: Commands to define database structure.
  - Examples: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`.
- **DML (Data Manipulation Language)**: Commands to manipulate data.
  - Examples: `INSERT`, `SELECT`, `UPDATE`, `DELETE`.
- **DCL (Data Control Language)**: Commands to control access to data.
  - Examples: `GRANT`, `REVOKE`.
- **TCL (Transaction Control Language)**: Commands to manage transactions.
  - Examples: `COMMIT`, `ROLLBACK`, `SAVEPOINT`.
- **DQL (Data Query Language)**: Command to query data.
  - Example: `SELECT`.

#### 3-Schema Architecture
- **Internal Level**: Physical storage structure.
- **Conceptual Level**: Logical structure of the entire database.
- **External Level**: Individual user views.

#### Database Normalization
- **Normalization Levels**: Organize data to reduce redundancy.
  - Levels: 1NF, 2NF, 3NF, BCNF.
- **Anomalies**: Problems like insertion, deletion, or update issues.

#### Relationships and Transactions
- **One-to-One, One-to-Many, Many-to-Many**: Types of relationships between tables.
- **Transactions**: Group of SQL statements executed as a unit.
  - **ACID Properties**: Ensure reliability.
    - **Atomicity**: All-or-nothing.
    - **Consistency**: Data remains consistent.
    - **Isolation**: Concurrent transactions do not interfere.
    - **Durability**: Once committed, changes are permanent.

#### Performance Optimization
- **EXPLAIN**: Analyze query performance.
  - **Heap Scan**: Read rows from a table in no particular order.
  - **Parallel Scan**: Multiple processes scan the table concurrently.

</details>

<details>
<summary><h2> 16.1 Create SQL CRUD REST API with Node.js (Optional)</h2></summary>

#### Project Setup
- **Initialize Project**: Create a new Node.js project using npm.
  - Command: `npm init -y`.
- **Dependencies**: Install necessary packages for SQL and HTTP handling.
  - Example: `npm install express pg pg-hstore sequelize body-parser`.

#### Database Integration
- **Connect to PostgreSQL**: Use a connection string to link your Node.js application to the PostgreSQL database.
  - Example using `pg`:
    ```javascript
    const { Pool } = require('pg');
    const pool = new Pool({
      user: 'username',
      host: 'localhost',
      database: 'dbname',
      password: 'password',
      port: 5432,
    });
    ```
- **Database Models**: Define Sequelize models to map to your database tables.
  - Example:
    ```javascript
    const { Sequelize, DataTypes } = require('sequelize');
    const sequelize = new Sequelize('database', 'username', 'password', {
      host: 'localhost',
      dialect: 'postgres',
    });

    const User = sequelize.define('User', {
      username: {
        type: DataTypes.STRING,
        allowNull: false,
      },
      password: {
        type: DataTypes.STRING,
        allowNull: false,
      },
    });
    ```

#### CRUD Operations
- **Create (INSERT)**: Add new records to the database.
  - Example:
    ```javascript
    app.post('/users', async (req, res) => {
      const { username, password } = req.body;
      try {
        const user = await User.create({ username, password });
        res.json(user);
      } catch (error) {
        res.status(500).json({ error: 'Failed to create user' });
      }
    });
    ```
- **Read (SELECT)**: Retrieve records from the database.
  - Example:
    ```javascript
    app.get('/users/:id', async (req, res) => {
      const { id } = req.params;
      try {
        const user = await User.findByPk(id);
        res.json(user);
      } catch (error) {
        res.status(500).json({ error: 'Failed to retrieve user' });
      }
    });
    ```
- **Update (UPDATE)**: Modify existing records in the database.
  - Example:
    ```javascript
    app.put('/users/:id', async (req, res) => {
      const { id } = req.params;
      const { username, password } = req.body;
      try {
        const user = await User.findByPk(id);
        if (user) {
          user.username = username;
          user.password = password;
          await user.save();
          res.json(user);
        } else {
          res.status(404).json({ error: 'User not found' });
        }
      } catch (error) {
        res.status(500).json({ error: 'Failed to update user' });
      }
    });
    ```
- **Delete (DELETE)**: Remove records from the database.
  - Example:
    ```javascript
    app.delete('/users/:id', async (req, res) => {
      const { id } = req.params;
      try {
        const user = await User.findByPk(id);
        if (user) {
          await user.destroy();
          res.json({ message: 'User deleted' });
        } else {
          res.status(404).json({ error: 'User not found' });
        }
      } catch (error) {
        res.status(500).json({ error: 'Failed to delete user' });
      }
    });
    ```

#### Middleware and Error Handling
- **Middleware**: Handle authentication, logging, or other pre-processing tasks.
  - Example:
    ```javascript
    const logger = (req, res, next) => {
      console.log(`${req.method} ${req.url}`);
      next();
    };
    app.use(logger);
    ```
- **Error Handling**: Manage and respond to errors gracefully.
  - Example:
    ```javascript
    app.use((err, req, res, next) => {
      console.error(err.stack);
      res.status(500).send('Something broke!');
    });
    ```

#### Testing
- **Unit Tests**: Test individual pieces of code.
  - Example: Use `jest` for testing.
    ```javascript
    test('should create a user', async () => {
      const user = await User.create({ username: 'testuser', password: 'password' });
      expect(user.username).toBe('testuser');
    });
    ```
- **Integration Tests**: Test interactions between components.
  - Example: Use `supertest` to test API endpoints.
    ```javascript
    const request = require('supertest');
    const app = require('../app');

    test('GET /users/:id', async () => {
      const res = await request(app).get('/users/1');
      expect(res.statusCode).toBe(200);
    });
    ```

#### Documentation
- **API Documentation**: Use Swagger or similar tools to document your API.
  - Example: Generate documentation from code annotations.
    ```javascript
    /**
     * @swagger
     * /users:
     *   post:
     *     summary: Create a new user
     *     parameters:
     *       - name: username
     *         in: body
     *         required: true
     *       - name: password
     *         in: body
     *         required: true
     *     responses:
     *       200:
     *         description: User created successfully
     */
    app.post('/users', (req, res) => { ... });
    ```
- **Setup Instructions**: Provide clear guidelines in your README.
  - Example: 
    ```markdown
    ## Setup
    1. Clone the repository: `git clone <repo-url>`
    2. Install dependencies: `npm install`
    3. Set up the database: `npm run db:migrate`
    4. Start the server: `npm start`
    ```

</details>

</details>

<details> <summary> <h2> 17. React Fundamentals (Under Development) </h2> </summary>

### Mini Project - Todo Application

</details>


<details> <summary> <h2> 18. React Mini Projects (Under Development) </h2> </summary>

  ### Mini Projects - NETFLIX & OLX Clone Mini Projects

</details>

<details> <summary> <h2>  19. React 3 - Redux Toolkit (Under Development) </h2> </summary>

### Mini Project - User Managment System

</details>


<details>
    <summary>
        <h2>20. Revision (Under Development)</h2>
    </summary>
</details>

<details>
    <summary>
        <h2>21. Learn Basic Devops (Docker & Kubernetes - k8s) & Microservice Architecture.</h2>
    </summary>
  
  <h3> Dockerise first E-Commerce Project</h3>

## Microservices Fundamentals

- **What is a Microservice?**
  - A small, independent service that performs a specific business function.
  - Communicates with other services through well-defined APIs.
  - Promotes modularity and loose coupling.

- **Monolithic vs. Microservices Architecture**
  - **Monolithic:**
    - Single codebase for the entire application.
    - Simpler development and deployment initially.
    - Scalability and maintainability challenges as the application grows.
  - **Microservices:**
    - Application broken down into smaller, independent services.
    - Increased complexity but improved scalability, maintainability, and fault tolerance.

## Principles of Microservices

- **Independent and Autonomous Services**
  - Each service should be self-contained and deployable independently.

- **Scalability**
  - Services can be scaled independently based on their needs.

- **Decentralization**
  - Promotes ownership and faster development cycles for individual services.

- **Resilient Services**
  - Failure in one service should not bring down the entire application.

- **Real-time Load Balancing**
  - Enables efficient distribution of traffic across service instances.

## Benefits of Microservices

- **Scalability**
  - Microservices can be scaled independently to meet varying demands.

- **Flexibility**
  - Easier to add new features or modify existing functionality.

- **Maintainability**
  - Smaller codebases are easier to understand and maintain.

- **Fault Tolerance**
  - Failure in one service has minimal impact on others.

- **Development Agility**
  - Independent development and deployment cycles for services.

## Challenges of Microservices

- **Increased complexity**
  - Distributed system management overhead.

- **Debugging and Testing**
  - Requires a shift in approach compared to monoliths.

- **Communication Overhead**
  - Managing communication between services can add complexity.

- **Security Considerations**
  - Requires robust security measures across services.

## Cloud Computing and Deployment

- **Public Cloud**
  - Computing resources (servers, storage, databases) delivered over the internet. (e.g., Amazon Web Services, Microsoft Azure, Google Cloud Platform)

- **Private Cloud**
  - Cloud infrastructure operated for a single organization. Offers greater control and security.

- **On-Premises**
  - Traditional approach of owning and managing physical IT infrastructure.

- **Deployment Models:**
  - Infrastructure as a Service (IaaS)
  - Platform as a Service (PaaS)
  - Software as a Service (SaaS)

- **Benefits of Deploying Microservices on the Cloud:**
  - **Scalability:** Easily scale services up or down based on demand.
  - **Agility:** Faster deployments and easier management of infrastructure.
  - **Cost-effectiveness:** Pay only for the resources you use.

<h2>Docker and Kubernetes Roadmap: A Deep Dive</h2>

## I. Docker

### What is Docker?

- A platform for developing, deploying, and running applications in containers.
- Containers are lightweight, isolated environments that share the underlying operating system kernel.
- Enables consistent and portable deployments across different environments.

### Docker Architecture

- **Client:** User interface for interacting with the Docker daemon.
- **Daemon:** Background process that builds, runs, and manages containers.
- **Registry:** Centralized repository for storing and sharing container images. (e.g., Docker Hub)

### Key Docker Concepts

- **Images:** Read-only templates for creating containers.
- **Containers:** Isolated instances of an image running on a host system.
- **Volumes:** Persistent data storage for containers. Independent of the container lifecycle.

### Docker Commands

- **Building Images:** `docker build`
- **Running Containers:** `docker run`
- **Managing Containers:** `docker ps`, `docker stop`, `docker start`, `docker rm`
- **Image Management:** `docker pull`, `docker push`
- **Networking:** Docker network commands
- **Volume Management:** Docker volume commands

### Learning Resources:

- Official Docker Documentation: [Docker Documentation](https://docs.docker.com/)
- Docker Tutorials: [Get Started with Docker](https://docs.docker.com/get-started/)
- Interactive Docker Playground: [Katacoda - Docker](https://www.katacoda.com/learn)

## II. Kubernetes

### What is Kubernetes (k8s)?

- An open-source system for automating deployment, scaling, and management of containerized applications.
- Orchestrates containerized workloads across a cluster of machines.

### Why Use Kubernetes?

- Automated Deployments
- Scalability
- Self-Healing Capabilities
- Load Balancing
- High Availability

### Kubernetes Architecture

- **Cluster**
- **Node**
- **Master Node**
- **Pod**

### Key Kubernetes Concepts

- **Deployments**
- **Services**
- **Namespaces**
- **Labels and Selectors**
- **Volumes**
- **Horizontal Pod Autoscaler (HPA)**
- **Ingress**

### Kubernetes Commands (kubectl)

- Managing Pods
- Managing Deployments
- Managing Services
- Managing Namespaces
- Viewing Logs

### Learning Resources:

- Official Kubernetes Documentation: [Kubernetes Documentation](https://kubernetes.io/docs/home/)
- Kubernetes Tutorials: [Kubernetes Tutorials](https://kubernetes.io/docs/tutorials/)
- Interactive Kubernetes Playground: [Katacoda - Kubernetes](https://www.katacoda.com/)


<h2>Beyond the Basics</h2>

- Explore advanced Docker features like Docker Swarm for multi-host container orchestration.
- Deep dive into Kubernetes concepts like service discovery, ingress controllers, and security best practices
- API Gateway: Single entry point for managing APIs of microservices.
- Service Discovery: Mechanism for services to find each other in a distributed environment.

## Learning Resources

**Articles:**
- [Microservices Roadmap](https://medium.com/@doremonlabs_70503/microservices-roadmap-45771379512f)

**Videos:**
- [Microservices explained - A gentle introduction](https://www.youtube.com/watch?v=ZoYQPxCF8xI)

</details>


<details>
    <summary>
        <h2>22. Learn Message Brokers, CICD Pipelines, gRPC + Two Mini Projects (Under Development)</h2>
    </summary>
</details>



<details>
    <summary>
        <h2>22. Project 1 (Under Development)</h2>
    </summary>
</details>

<details>
    <summary>
        <h2>23. Project 2 (Under Development)</h2>
    </summary>
</details>

<details>
    <summary>
        <h2>24. Project 3 (Under Development)</h2>
    </summary>
</details>

<details>
    <summary>
        <h2>25. Project 4: Completion (Under Development)</h2>
    </summary>
</details>

<details>
    <summary>
        <h2>26. Project 5: Hosting (Under Development)</h2>
    </summary>
</details>

<details>
    <summary>
        <h2>27. Revision 1 (Under Development)</h2>
    </summary>
</details>

<details>
    <summary>
        <h2>28. Revision 2 (Under Development)</h2>
    </summary>
</details>

<details>
    <summary>
        <h2>29. Job Interview Tips (Under Development)</h2>
    </summary>
</details>
