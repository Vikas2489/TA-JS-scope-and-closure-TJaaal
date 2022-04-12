Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(useranme); // `Reference Error username is not defined`
```

In above code we are looking for the variable named `username`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = 'Arya';
}
console.log(username); // `Reference Error username is not defined`
```
In above code we are looking for the variable named `username` Which has already been defined using const.As we all know that const is block-scoped and functional scope. That's why we can't access that varaible from outside.

The above code will throw an error `Reference Error username is not defined`

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); // `Reference Error username is not defined`
```
In above code we are looking for the variable named `username`. And as let is an block scoped ,That's why we can't access that varaible.

The above code will throw an error `Reference Error username is not defined`

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = 'Arya';
}
console.log(username); // "Arya"
```
Var is only function scoped that's we can access the variable username from outside of the block scope and that's why we will see Arya in the console.

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(username); // error saying that username has already been taken
```
Because, when console will look out for the value of the variable username, 
In the console, we will see an error saying that username has already been taken. 

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(username); // error saying that username has already been defined
```
In the console, we will see an error saying that username has already been taken.

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello(); // Undefined
console.log(username); // John
```
In the console, we will see John because as the varaible username is present in the memory of global exection context.

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First'); // we will see 0 to 9 along with that first will be written.
}
console.log(i, 'Second'); //  we will see 10 "second" {when the loop will end then value of i will be 10, that's why it will show 10 in the place of i.}
```

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'First'); //  we will see 0 to 9 along with that first will be written.
}
console.log(i, 'Second'); //  10 "second"
```
