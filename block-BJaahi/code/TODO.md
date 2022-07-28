For the given code below:

- re-write the code in ways that system will understand

For Example:

1.

```js
var username = 'Arya';
let brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Declaration Phase
var username = undefined;
let brothers;

function sayHello(name) {
  return `Hello ${name}`;
}

let message;
var nextMessage = undefined;

// Execution Phase

username = 'Arya';
brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

message = sayHello(username);
nextMessage = sayHello('Test');
```

2.

```js
console.log(username, numbers);

var username = 'Arya';
let number = 21;

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Your code goes here
//DP
var username = undefined
let number;
function sayHello(name) {
  return `Hello ${name}`;
}
let message;
var nextMessage = undefined
//EP
console.log(username, numbers);
 username = 'Arya';
 number = 21; 
message = hello arya
nextMessage = hello test
```

3.

```js
console.log(username, numbers);
let username = 'Arya';
let number = 21;

let sayHello = function (name) {
  return `Hello ${name}`;
};

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Your code goes here
//DP
let username;
let number;
let sayHello;
let message;
var nextMessage = undefined;
//EP
console.log(username, number); //error
username = 'Arya';
number = 21;
message = hello arya
var nextMessage = hello test;

```

4.

```js
let username = 'Arya';
console.log(username, numbers);

let number = 21;
let message = sayHello(username);

let sayHello = function (name) {
  return `Hello ${name}`;
};

var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Your code goes here
let username;
let number;
let message;
let ssayhello;
var nextMessage = undefined;
// EP
username = 'Arya';
console.log(username, numbers);
 number = 21;
 sayHello =  function (name) {
  return `Hello ${name}`;
};
nextMessage = hello text
```

5.

```js
console.log(name);
console.log(age);
var name = 'Lydia';
let age = 21;
```

<!-- Answer -->
<!-- undefined

ReferenceError: age is not defined -->
```js
// Your code goes here
```

6.

```js
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}

sayHi();
```

<!-- Answer -->
<!-- undefined

ReferenceError: age is not defined -->
```js
// Your code goes here
```

7.

```js
sayHi();
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}
```

<!-- Answer -->
// undefined age not defined
```js
// Your code goes here
```

8.

```js
sayHi();
let sayHi = function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
};
```

<!-- Answer -->
// sayHi is not defined
```js
// Your code goes here
```

9.

```js
let num1 = 21;
console.log(sum); // undefined
var sum = num1 + num2; // num2 is not defined
let num2 = 30;
```

<!-- Answer -->

```js
// Your code goes here
```

10.

```js
var num1 = 21;
let sum2 = addAgain(num1, num2, 4, 5, 6);
let addAgain = (a, b, c, d, e) => {
  return a + b + c + d + e;
};
function add(a, b) {
  return a + b;
}
let num2 = 200;
let sum = add(num1, num2, 4, 5, 6);
```
<!-- Answer -->
```js
// Your code goes here
var num1 = undefined
let sum2;
let add;
function addAgian(a, b) {
  return a + b;
}
let num2;
let sum;
//EP
num1 = 21;
```

11.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

let add = (a, b) => {
  return a + b;
};
```

<!-- Answer -->  add is not defined

```js
// Your code goes here
```

12.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

function add(a, b) {
  return a + b;
}
```

<!-- Answer --> 121

```js
// Your code goes here
```
