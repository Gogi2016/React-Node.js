## Intro to Node JS
Node.js, introduced in 2009 by Ryan Dahl, revolutionized JavaScript by extending its use beyond front-end development to server-side programming. It is built on Chrome's V8 JavaScript engine, providing a runtime environment that allows JavaScript to execute on servers. Node.js gained significant traction with the release of npm (Node Package Manager) 1.0 in 2011, facilitating easy sharing and management of open-source libraries.
node instalation use "npm" (Node Package Manager)
The Node.js Foundation, established in 2015, helped resolve community disputes and foster collaboration among major companies like IBM, Microsoft, and PayPal. This collaborative effort ensured the continued growth and evolution of Node.js as a prominent technology in the software development ecosystem.
Node.js enables developers to leverage their JavaScript skills for a wide range of tasks, including building command-line tools, servers, and interacting with the file system. Its asynchronous, non-blocking I/O model makes it particularly efficient for handling tasks like networking and file system access in web applications.
One of Node.js's key advantages is its ability to unify front-end and back-end development, allowing developers to share code seamlessly between client and server. This reduces cognitive overhead and promotes maintainability and efficiency in software development.
Version of JavaScript does Node.js support is Both ES5 and ES6

## Pros of JS
Same Language for Frontend and Backend: JavaScript can be used for both the front end (what users see in their browsers) and the back end (the server-side of web applications). This means developers can use the same language for both parts, making it easier to share and reuse code between them.

Dynamic Nature: In JavaScript, the type of a variable is determined by the value it holds, not by the type declared when creating the variable. This means JavaScript has loose typing, unlike languages with strong typing where you have to declare the type of a variable when you create it.
Integration with JSON: JSON is a popular data format used for exchanging data between a web server and a web application. JavaScript works really well with JSON, making it easy to send and receive data between the front end and back end of a web application without needing complicated conversions.
Drawbacks Consideration: While JavaScript has many advantages, it's not always the best choice for every situation. Some people might see its flexibility as a drawback, especially in certain scenarios. However, the ability to use the same language for both the front end and back end of web applications is a big plus for many developers.
In simple terms, JavaScript is great because you can use it for both the visible parts of a website and the behind-the-scenes stuff. It's flexible with how it handles data and works well with a format called JSON for exchanging information between different parts of a web app. But just like anything else, it has its pros and cons, and it might not be the best choice for every situation.

Callbacks and Asynchronous Tasks
Synchronous Tasks: When tasks are done synchronously, we have to wait for each task to finish before moving on to the next one. This waiting can cause blocking, which means everything else has to stop until that task is done. For example, think of filling out a form on a website and waiting for it to submit before you can do anything else.

Asynchronous Tasks: With asynchronous tasks, we can move on to the next task without waiting for the previous one to finish. This is really helpful for tasks that might take a long time, like loading data from a network or accessing files. Node.js is great at handling these kinds of tasks efficiently, which is why it's popular for web applications.

Callbacks: In asynchronous programming, we often use something called callbacks. Think of it like leaving your phone number for a tech support call-back. You tell Node.js what to do when a task is done, and it will call that "callback" function when it's finished. So, in the example of loading and reading directories, even though we have a line saying "this comes after" later in the code, it might actually execute first because of the way callbacks work. It's like saying, "Hey, call me back when you're done with this task," and then Node.js will let you know when it's finished.

Node.js primarily used for Server-side JavaScript
Node.js uses a single-threaded, event-driven architecture.
Node.js well-suited for building scalable network applications because It has a non-blocking, event-driven architecture.
version of JavaScript that Node.js support is Both ES5 and ES6

Node Global
global object in Node.js represents the current module is Module
the purpose of the ‘__filename’ variable in Node.js contains the absolute path of the current module file.
to exit a Node.js process explicitly use 'process.exit()'
the role of the '__dirname' variable in Node.js It stores the absolute path of the current module's directory.
function is used to include external modules in Node.js is 'require()'

Node Modules
the purpose of the ‘module.exports’ object in Node.js modules It exports the content of the current module for use in other modules.
They are automatically included in every Node.js application.
the purpose of the ‘require.resolve()’ function in Node.js It resolves the path of a given module.
the ‘__filename’ variable represent inside a module The path to the current module file.
to import an entire module into a variable in Node.js 'const myModule = require('./myModule')'

Node Frameworks
In web development, frameworks are like blueprints or templates that help developers build websites or web applications more efficiently. They provide a structure and tools to handle common tasks, like serving web pages or managing data.
Web APIs are interfaces that allow different software systems to communicate over the internet, typically used for retrieving or storing data on a server.
Node.js is a popular technology for building web applications, and there are several frameworks available to work with it.
Express is a widely-used framework known for its simplicity and reliability, making it a good choice for many projects.
Sails is another framework that offers more features, including tools for working with databases, making it a comprehensive option for larger projects.
Koa is a more modern framework with innovative features, appealing to developers looking for the latest tools and techniques.
Each of these frameworks has its own strengths and is suitable for different types of projects.

Express
Express.js is a web framework for Node.js, designed to support both web applications and web APIs. This means it can handle tasks for both the front end and back end of a web application.
Sometimes, the term "web application" can be confusing because it may seem to refer only to the front-end part of an application that runs in a browser or on a mobile device. However, many web applications also require a back end to handle tasks like user authentication and data retrieval.
Express.js specifically focuses on the back-end aspect of web applications, providing tools and features to facilitate communication between the front end and the server. For example, it allows applications to fetch data from a database or perform other server-side operations.
Express.js has a strong community of developers and extensive online documentation, making it a popular choice for building web applications and APIs. Its longstanding presence in the development community contributes to its robustness and reliability.

Socket.io
Socket.io is a powerful tool for enabling real-time, bidirectional communication between a client (such as a web browser) and a server (typically powered by Node.js). This addresses a limitation in Express, which primarily allows the client to initiate requests to the server.
With Socket.io, both the client and server can send messages to each other at any time, allowing for dynamic updates and notifications without the need for the client to continuously poll the server for updates.
Socket.io consists of two main components: a client-side library for browsers and a server-side library for Node.js. These libraries have similar APIs and operate in an event-driven manner, similar to Node.js itself.
In our upcoming demonstration application, we'll explore how Socket.io enables real-time communication between a web client and a Node.js server. This will showcase the power of Socket.io in creating dynamic and interactive web applications. Let's proceed to create our demo application using Express and Socket.io.
