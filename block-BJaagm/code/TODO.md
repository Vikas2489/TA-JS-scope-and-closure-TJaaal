1. What does thread of execution means in JavaScript?

<!-- Ans. Thread of execution means executing the piece of code line by line in Javascript. -->

2. Where the JavaScript code gets executed?

<!-- Ans. Javascript code gets executed in execution context. -->

3. What does context means in Global Execution Context?

<!-- Ans. context in Global Execution Context means the required environment to run all the javascript codes line by line. -->

4. When do you create a global execution context.

<!-- Ans. Global execution context is created whenever we run a piece of code and whenever we create a variable and that variable gets stored in the memory. -->

5. Execution context consists of what all things?

<!-- Ans. Execution context consits of all the codes which is running at that time and everything that help in the execution. -->

6. What are the different types of execution context?

<!-- Ans. Execution context are of two types which are given below:-
  1. Global execution context (Default one)
  2. Function execution context (Whenever we call a function) -->

7. When global and function execution context gets created?

  <!-- 1. Global execution context (Default one)
  2. Function execution context (Whenever we executes a function, it gets created in the global execution context.) -->

8. Function execution gets created during function execution or while declaring a function.

 <!-- Ans. Function execution context (Whenever we executes a function, it gets created in the global execution context.) -->

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);

```

<!-- Put your image here -->


```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)