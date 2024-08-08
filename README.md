# Mission Frontend
A curated list of Javascript, React, Machine coding problems, Pattern questions, basic backend knowledge and fundamentals questions all in one.

## HTML and CSS3 
- Difference between innerText and textContent.
- What is the use of data attribute.
- Difference between loading lazy and loading eager on img tag.
- Semantic and non-semantic elements.
- Difference between rem, em and px.
- make cards responsive (display vertical in column), when screen size changes to lower resolution - without using media query.
- Difference between max-width and min-width.
- Why should you use border:transparent instead of border:none.
- How to check which HTML version are you using.
- Difference between HTML4 and HTML5.
- When to use Tailwind, CSS, SCSS and difference among them.
- What are pseudo classes.
- Difference between inline and block elements.
- Problem statement: Add a background image and a text above it, add opacity to background image -> Adding opacity to the background image should not affect the text above it.
- What is difference between display:none and display:hidden.
- Flex and Grid which layout approach should you use and when to use.
- Media Queries.

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
- Difference between preventDefault and stopPropagation.

- Write a JS func that takes an obj and a callback, execute the callback after 3 sec.
- Create a function that takes 3 arguments function, interval, and frequency. the function should execute as many times as the frequency
 we passed and there should be a delay equal to the interval
 we passed. For eg our(() => console.log("hi"), 2, 3)
 should print "hi" 3 times with a gap of 2 seconds between each execution.Add up to this, the user should have control to terminate the callback function. Suppose we are pinging the server and if we get the response we should stop executing the function.

- this, call, bind , apply and their polyfills.
- Difference between == and ===
- Exception handling 
- Difference between i++ and ++i.
- What happens when you fetch an api, and what role does dns play in this.

## Guess the Output!
```
console.log(undefined  || 5 && 9 || 2 );
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

- Build an input box and a button to store items in an array, and have another button to find the second largest element from the stored array. Also, the array of items should be displayed along with the second-largest number.

- Create a reusable input component that will accept type as a prop
 and will do different types of input validation(if the type is text it should contain max x no. of characters if a type is a number it should be between x and y etc.) depending upon the type we passed. As soon as something invalid is entered, an error should dynamically show on screen and as soon as we change it to something valid, the error should also disappear.

- Implement four quadrants  (just like the Microsoft logo) using react with reusability.
And after that, whenever I click on a  box, it should show clicked on that particular box, and when I click on another box  it should show clicked in that box and disappear in another box. ( without any code redundancy)

- Make three radio buttons with labels red, blue, and yellow and add a div below it . When I click on any radio
button the color of the div should change ,for example , if I click on red the colour should be red.
Add feature that if I click on two radio buttons the colour of div should be mixture of those colours.

- On check/uncheck of top checkbox, all checkboxes should be checked/unchecked and vice-versa.
We should be able to individualy check/uncheck checkbox from the list. 
If any of the checkbox is unchecked, the top checkbox should show an intermediate symbol.
A button below the checkbox, which when clicked should console log only the Id of the checked checkbox.

- create a toast message using Javascript/ React , it should disappear automatically after 5sec.

-  Create a Reusable react card, header and type is passed as props, style of that card should be determined by type of card it is through prop : like type="facebook" some style, for "twitter" some other style, some nested components inside the body of card, they should also have styles.

- Create a component which converts the input to ascii, add 10 to it and convert the same from char code.

- Validate form 
name (must not be empty and less than 100 characters allow);
age (between 18-99)
email(valid email)
password(at least 8 characters)
re-password(password and re-password same)
show error message in the alert box!
- optimize the performance of a React app that displayed a large list of data, and the interviewer wanted me to explain the most efficient approach to rendering the lists.

## DSA 
- Sum of digits at even places of a number.
- Recursive solution to find factorial.
- check if strings are rotational of each other.
- recursion solution to multiply without using multiply operator
- Find the maximum Occurring string from an array.
- Given an array conver it to linked list and find the head from the converted linked list.
- Flatten an array without using inbuilt js methods.
-  implement recursion function to print every character of string , after that its should print "its vowel" for every vowel from string.
- let arr = [ " ( ", " } ", " ] " , " { ", " ) ", " [ " ];  to   ["(", ")", "{", "}", "[", "]"]
      sort the array with pairs
     catch:  a left brace has a high priority over right brace 
      so in case of left brace "(" so we have to find it first pair ")" .
- Write a function which takes an array and returns sub arrays. for eg if we pass [1, 1, 2, 2, 4, 4, 5, 5, 5] as input we should get [[1,1,2,2], [4,4,5,5,5]] as output. Basically sub array can only contain one pair of consecutive elements but those elements should repeat as many times as they repeated in original array. 
- Given input : 
{
    "harsh" : ["cricket", "vollyball"],
    "aasim" : ["cricket", "football", "ludo", "COD", "rugb", "vollyball", "Racing"],
    "jignesh" : ["cycling", "cricket"],
    "jimish" : ["cycling"],
    "prince" : ["vollyball","football"],
    "raj" : ["ludo","cricket","cycling"]
}
 
output : 
{
    "harsh, aasim":["cricket","vollyball"],
    "harsh, jignesh":["cricket"],
    "harsh, jimish":[],
    "harsh, prince":["vollyball"],
    "harsh, raj":["cricket"],
    "aasim, jignesh": ["cricket"],
    "aasim, jimish": ["],
    "aasim, prince": ["vollyball","football],
    "aasim, raj": ["ludo","cricket"],
    "jignesh, jimish" : ["cycling"],
    "jignesh, prince" : [],
    "jignesh, raj" :["cycling"],
    "prince, raj" : []
 }

- Sort the array without inbuilt method.
- Binary search implementation (Find index of number present in a sorted array).
- Find the 3rd largest element in an array.
- Sort the array 1's , 2's and 3's -> [0, 1, 1, 2, ,1 , 2, 0] -> [0, 0, 1, 1,1, 2, 2]
- Given a string "{}()[}[)]" , find the valid parenthesis, if yes return true else false.
- Count the number of each character occured in string  "madam".
- Remove duplicates from an array.
- Check is the string is a palimdrome.
- Reverse the string
- Capitalize first letter of each word -> "abhay is cool" => "Abhay Is Cool"
- Array methods -> Filter, map, reduce, slice, splice, sort.
- Check if the number is a palimdrome or not.
- Impement stack and it's operations.
- Write a function that converts an object into an array, where each element represents a key-value pair in the form of an array
.toArray({ shrimp: 15, tots: 12 }) ➞ [["shrimp", 15], ["tots", 12]]
- Create a function which takes an array arr of integers as an argument. This function must return another function, which takes a single integer as an argument and returns a new array.
The returned array should consist of each of the elements from the first array multiplied by the integer. 
multiply([1, 2, 3])(2) ➞ [2, 4, 6]


## React 
- Dependency Injection.
- What are high order components, explain with an example.
- Design patterns.
- What solid principles are followed in React.
- Presentational Components - What are pros and cons.
- Virtual Dom.
- Lazy loading and Suspense.
- what are protected routes, how will you implement that.
- Lifting the state up.
- What components will you use lazy loading.
- Controllled vs Uncontrolled components.
- Class based vs Functional based components pros and cons.
- Why does component re-render.
- useMemo and useCallback Hook differences.
- Memoisation.
- CSR VS SSR.
- how to handle image uploading -> asset optimization techniques.
- Why the key should be unique.
- Why should you use redux instead of context.
- Can redux have multiple stores, and can context have multiple context.
- Life cycle hooks.
- Difference between state and props.
- What is batching.
- what is prop drilling how can you avoid prop drilling.
- How will you structure your folder architecture - redux, helpers, utils, constants, components.
- What are reusable component - create a reusable Input component that will handle email, password, number, text at same time.
- If props are passed from parent to child and if I made some changes in props value in child will the value be affected in the Parent component.
- Why does state use previous values to update or set state.
- What are the things that can be passed in dependency array of useEffect.
- Can functions be passed in the dependency array.
- Diffrence between useLayoutEffect and useEffect which is synchronous and which is asynchronous.
- Can you use this keyword in functional component.
- Create a h2 tag with classname attached to it and display it on the screen without using JSX.
- What is babel.
- Why is React so fast.
- React VS VueJs VS Angular JS which is better and why.
- What problems does Next JS solve, that React does not.
- React is declarative or imperative library.
- What are children props.
- What is useReducer hook how is it useful instead of using useState.
- What value does useCallback hook return function or value?.
- Why is Switch used in react-router-dom.
- Create a custom useAsync hook, that will take API URL as parameter, and return loading, error, response and use this useAsync hook to fetch data.
- Why setState is asynchronous.
- What is cleanup function in useEffect where is it used.
- What are pure components.
- If child re-renders will the parent also re-render and viceversa.
- Component lifecycle.
- Does useRef hook cause re-render on change of something.
- When to use useRef and useState hook.
- Can you pass a function in the useState initial value.
- How will you handle images that takes time to load on the UI.
- How would you explain re-renders in React
- What are synthetic events.
- What are the optimization techniques to make react fast.
- What is strict mode in react.
- What is react element.
- How will you explain components.
- What are fragments in react.
- Difference between element and component in React.
- What are Error Boundaries.
- What are render props pattern.

## Basic Backend 
- Rest API.
- types of Status code and what they refer to.
- Middlewares.
- Types of storage.
- Accesss token and Refresh token.
- How Authentication works.
- Difference between Sql and noSql database.
- How will you validate API.
- ContentType
- What are headers.
- What type of content can you pass in the Rest API.
- Basic Schema idea - how will you design schema.
- What is ORM and ORD.
- API Polling.
- web tokens.
- API versoning.

## Performance and Optimization
- Given list of images how would you render it effectively.
- If network is low how will you manage the video calling effectively, if there is some error in it how will you display it to the user.
- What is lazy loading and its tradeoffs.
- How code splitting actually helps to reduce the bundle size.
- Why react is faster?
- If large unused css files are there will it effect the bundle size.
- What if the font is not loading - how can you optimize it.
- Fallback image and fallback font how to use them to optimize and improve performance.

## System Design 
- video call feature, how to check network connection, which protocol to use, multiple joinee, backend connection, as I had done this feature using  aws chime sdk, so this was asked to me if not aws chime how will you implement it with performance optimisation.
- TCP.
- RTMP
- Video optimization techniques.

