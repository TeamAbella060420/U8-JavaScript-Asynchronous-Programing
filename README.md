# U8-JavaScript-Asynchronous-Programing
 
1. Introduction to Asynchronous JavaScript - Any time you have code that needs to execute after some period of time, in response to an event (like a mouse click), or upon receiving the data it needs, you're introducing asynchronous behavior into your program. JavaScript and its runtime environment provide efficient ways to handle async operations.
2. Understanding Synchronous and Asynchronous Code - To better understand what asynchronous code is and why it's necessary, you should also understand what synchronous code is.
3. Async Programming and Callback Functions - Fetching data is one of the most common ways you will write asynchronous programs in JavaScript.
4. Implement a Callback - Now that we're successfully getting data asynchronously from the Open Notify API, let's use it to make another AJAX call, this time to the Wikipedia API.
5. Stepping Through Async Code - Use the Chrome DevTools debugger to step through the code you've written and highlight the flow of code execution.
6. Managing Nested Callbacks - Each callback adds a level of nesting, and when you have lots of callbacks, the code could get complicated quickly.
7. What is a Promise? - A Promise represents the eventual completion of an asynchronous operation. Promises provide a straightforward alternative for composing and managing asynchronous code, without having to write too many callbacks, or spend extra time figuring out what the program should do.
8. Reject a Promise and Handle Errors - If an error occurs, the promise status changes from "pending" to a "rejected" (or failed) state. Promises give you the opportunity to handle the error with a method called catch().
9. From Callbacks to Promises - convert parts of the project from callbacks to promises.
10. Handle Multiple Promises with Promise.all - JavaScript promises provide an efficient way to fire off and keep track of multiple asynchronous operations with the Promise.all method. Promise.all is useful when your program needs to wait for more than one promise to resolve.
11. Perform Cleanup With finally() - The `finally()` method is a new addition to promises. It gets called once a promise is fully settled, regardless of whether it's fulfilled or rejected. Finally is useful when you need to do some clean up after the promise sequence finished.
12. Using Fetch - easier way to make network requests with the Fetch API.
13. Convert Promise Handling to Async/Await - convert many of the project's promise chains to async/await.
14. Error Handling with try...catch - Since you're working with what looks like synchronous code, async functions can use try...catch to handle any errors. try...catch is the most common way to handle exceptions when using async/await.