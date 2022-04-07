1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = (marks, total) => {
  return (marks * 100) / total;
}

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```
<!-- function Declaration -->


```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

```
<!-- function expression -->


```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
<!-- function expression -->

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
<!-- Function expression -->

```js
let percentage = (marks, total) => (marks * 100) / total;
```
<!-- Function expression -->

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

<!-- Ans. It is because expression is an object that's why function defination is an expression. And expression can be stored in any variable in which we want. -->

```js

let checkOddOrNot = function (num){
  return num% 2 !== 0;
}

```

4. Why is a function call an expression in JavaScript?

<!-- Function call is an expression in javacript because fucntion itself is an object and we can store into any variable.   -->

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid
five = add; // valid
five = five(10, 11); // valid
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.

In Function definition, we define the each and every steps and what to do next.
```js
function add(a, b) {
  return a + b;
}

```

In function call, We call the function with parameter if required.

```js
add(2,3);

```


7. What is the similarities between function definition and function call?

They both work as same.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.

<!-- Higher Order Function is a function which return a function or accepts a function as a parameter. -->

```js

function fullName(firstName, lastName, fn){
  console.log(fn);
  return `${firstName} + ${lastName}`;
}

fullName("Arya" , "Stark", hello)

```
10. Explain what is callback function. Why you can pass a function inside a function?

A callback function is a function reference  which is passed into an another function as an parameter. We can pass a function inside a function because function is an expression and expression is an object.

