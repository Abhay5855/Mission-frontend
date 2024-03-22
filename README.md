# Frontend-hero
A curated list of Javascript, React, Machine coding problems, Pattern questions, basic backend knowledge and fundamentals questions all in one.

## Javascript 
- What is difference between async and defer, which is better.
- Problem statement : Explaing what is debouncing with an example, I just created a normal function that logs "click" after 2sec, even if multiple times button is called, followup question was If the same function that logs "clicked", is called with timeout lesser than the debounced function which should run first, if the less timeout function runs first abort it and call the debounced function first (Asked for SDE-1).
- What is interface and can we add methods in the Interface.
- SOLID Principles (Highly asked question)
- Problem statement : Create a polyfill for array.map() method and Promise.all()
- What are call, apply and bind methods.
- Explain abstraction using Javascript, how will you create private variables and methods.
- Pass by value and pass by reference output based questions.
- What is callback hell, how to prevent it.
- If Promises also forms Promise chaining how is it different from callback hell then, and what can you do to prevent both promise chaining and callback hell.
- What are falsy values in Javascript.
- Difference between undefined and null.
- Problem statement: Implement and Explain Event bubbling with an example.
- Difference between forEach and map method.
- What are the features introduced in ES6 and ES5.
- What is shadow DOM , DOM
- Type conversion - output based questions.
- Event loop - Microtask and Macrotask queue.
- What are constructors in JS.
- What methods will you use to compare two objects are equal or not.
- What is currying.
- Problem statement : Create a infinite currying function.
- Except this keyword what other things are there that arrow function does not have.
- We cannot reassign or redeclare a variable to const declaration, but in the case of array/object how is this possible?
- What is an IIFE
- Problem Statement: Write a function to create an object from a string 
```
IP - "x.y.z", "convert"
OP - {a: {b: {c: "convert"}}}
```

## Machine coding questions - (vanilla JS/ React)
- Show a button that will show start label on click it should show stop, viceversa show a counter with 0, after clicking start it should increment the counter by 1 every one second, on click of stop it should stop the counter and resume again where it was stopped previously.
- Given an API returning a list of todos, we want to fetch the list, create a separate block for each user, and display their todos in the appropriate block. Use this endpoint URL to get the todos: https://dummyjson.com/todos?limit=10&skip=80. It will return the following structure with a total of 10 todos: { “todos”: [ { “id”: 1, “todo”: “Do something nice for someone I care about”, “completed”: true, “userId”: 26 }, ], } Each block should contain the userId as the title of the block and the list of todos.

-  Create 2 mock API’s which returns a list of students and each student has a name, some marks and a unique registration ID. Data from the 2 API’s can have common students i.e. mock API 1 can have a student as — ABC / 98% / 1234 (name / marks / registration ID) and this same data can be there in mock API 2 response as well. Now after creating these 2 API’s using Promises and hard-coded data, you need to merge the data coming from both API’s and have to delete the duplicates.

- Using this API endpoint - https://dummyjson.com/products, Display the data in a list with a checkbox and button delete with each item, Before displaying the items, add a feild completed: false in the JSON, It should be able to delete the item on click of delete button, on click of checkbox it should mark the item as completed with line-through to the item marking it as complete.

- Implement pagination using this API endpoint - https://dummyjson.com/products, 
```
1.It should display 10 items on each page.
2. The page which is active should show active state.
3. It should have forward and Previous arrow on which we can change the page number.
4. Handle loading state on each page change.
5. When it's the first page the previous button should be disabled, similarly for last page.
```

- https://dummyjson.com/products using this API, display products, create a sidebar Just like Flipkart UI, show checkboxes with label - 40% and more,  50% and more,  60% and more,  70% and more, When click on particular checkboxs it should filter the products according to the discount percentage, If no products available show a display message accordingly, there should also be a button to clear the selection of selected percentage, render the UI accordingly.

- Create a multi-step form, where next and previous button are there on the last page user should be able to submit the form, on previous click the data entered should be persisted.

- Create a stopwatch display in this format - HH:MM:SS, with three buttons start, stop and reset, it should update the seconds every one second, after 60 sec update to 1 minute after 60min, update to 1hr, on stop button it should stop the watch and should be able to start again, on reset it should reset all values.

- Implement a stack structure
```
1. Create a UI that resembles stack 
2. Add Input that accepts number.
3. push button : Add an element to the top of the stack.
4. pop button : Remove the topmost element from the stack.
5. create a function isEmpty : Checks whether the stack is empty.
6. create a function top : Displays the topmost element of the stack.
```

- Impelement a previous and next functionality, create a button increment, display initial count to 0, when Increment is clicked it should show two text - 
```
1. Current : that will display the incremented count.
2. Previous : This will show the previous value that was before incrementing the count.
```

