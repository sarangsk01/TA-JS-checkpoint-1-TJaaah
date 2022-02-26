1. Using loops take 10 inputs from user and find the average of all the numbers.
```js
function avg() {
  var average = 0;
  for (var i=0; i <= 10; i++) 
    average += +(prompt("enter the number " + i))/10;
  console.log(average);
```

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi'); // 0
  i++;
}
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
function getEvenSum(max=10){
     let sum=0;
for(i = 1;i<=10;i=i++){
    if(i % 2 == 0) {
        sum=sum+i;
    }
        
}
}
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
function getoddSum(max=10){
     let sum=0;
for(i = 1;i<=10;i=i++){
    if(i % 2  !== 0) {
        sum=sum+i;
    }
        
}
}

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
function getProductOfDigits(num)
6. What will be the output of the following code below in multiple conditions? Explain with reason?
// function getProductofDigits(num){
    let product = 1;
 
    while (n != 0)
    {
        product = product * (n % 10);
        n = (n / 10);
    }
    return product;
}
```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // output 'Bigger than 5'
check(1); // output 'Smaller than 5'
check(5); // output 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output 'You are arya'
getOutput('John'); // what will be the output 'You are john'
getOutput(); // what will be the output 'Who are you'
              // Reason for this code is in first statement 'Arya' is defined and in the second 'John' is defined otherwise 'Who are you' is showing.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
              // Reason for this code is in first statement 'Arya' is defined and in the second 'John' is defined otherwise 'Who are you' is showing.
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
// A function can have multiple return statements but only one of them will be executed because once a return statement is executed, the program control moves back to the caller function skipping the remaining statements of the current function.

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
// The difference between for loop and while loop is that in for loop the number of iterations to be done is already known and is used to obtain a certain result whereas in while loop the command runs until a certain condition is reached and the statement is proved to be false.
A while loop works on the following syntax–   

 While(condition){
//code
//loop body} 

for loop
During the initialization of for loop, a starting value for the variable is to be declared. This loop requires initialization only once. 