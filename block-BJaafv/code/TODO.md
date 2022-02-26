1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
```js
//The console. log() is a function in JavaScript which is used to print any kind of variables defined before in it or to just print any message that needs to be displayed to the user.
//return is how a function gives back a value. This value is often unseen by the human user, but it can be used by the computer in further functions.

```
2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.// The output shows Identifier 'a' has already been declared.
```js
// When a return statement is used in a function body, the execution of the function is stopped. If specified, a given value is returned to the function caller. 
```
3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
```js
// The output is 36 because we defined only two parameters in our function.
```
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
```js
// We can store the first 'sum' function in a variable named 'add'.Because function sum is the object and add is the variable.This type of code is called function expression.
```

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
function sayHello(name){
  return `Hello ${name}`;
}
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
```js
// The output is 'Hello, John' because variable username is defined with a value already therefore it shows the output.
```
7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1  is john because its only alerting the username.

showMessage(); // Output 2 'Hello, John' a function gives back a value. This value is often unseen by the human user, but it can be used by the computer in further functions.

alert(userName); // Output 3 is john because its only alerting the username.
```

8. What is a Anonymous Function give example of three functions.
```js
const addNumbers = function(numA,numB){
      return numA + numB;
}
const multiply = function(numA,numB){
      return numA * numB;
}
const division = function(numA,numB){
      return numA / numB;
}
```

9. Can function declaration be a Anonymous Function? Explain
```js
// No.Function Expression allows us to create an anonymous function which doesn't have any function name which is the main difference between Function Expression and Function Declaration.

```
10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
```js
// 5 Function names are : addItem()-to add multiple items, getTable()-to get multiplication table.getItemById()-for getting the item by id.isLeapYear()-to find Leap year,sayHello()-to say hello to the user.

```