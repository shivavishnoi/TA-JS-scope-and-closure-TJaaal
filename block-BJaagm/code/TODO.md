1. What does thread of execution means in JavaScript?
the process of execution of code
2. Where the JavaScript code gets executed?
in GEC
3. What does context means in Global Execution Context?

4. When do you create a global execution context.
when the JS code is triggered
5. Execution context consists of what all things?
GEC and FEC
6. What are the different types of execution context?

7. When global and function execution context gets created?
only once whrn JS code gets triggered     
8. Function execution gets created during function execution or while declaring a function.
when function is executed and gets ddeleted as soon as it returns the value

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



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