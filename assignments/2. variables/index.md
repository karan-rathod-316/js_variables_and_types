1. In code below "Mark" is a string. What is name?

```js
var name = "Mark";
```
<!-- Variable -->

2. Find the error if any

```js
  var product cost = 3.45;
```
<!-- there is a space between product and cost. product_cost or productCost are correct alternatives -->

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" //Right
  'Hello World" //Wrong
  "Hello World' //Wrong
  'Hello World' //Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man; valid
var 1girl; invalid
var woman3; valid
var -girl; invalid
var blackDog; valid
var 42; invalid
var $42; valid
var userName; valid
var x, y, z; valid
var x = 5, y = 6, z = 7; valid
var x = 5 + 10 + 2; valid
var user = "Tyrion"; "Arya"; "John"; invalid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var reducedAmount = amount - 80

// Define a new variable and store the value that is 200 more then the value of amount.
var increasedAmount = amount + 200

// Define a new variable and store the value that is 4 times the value of amount.
var multipliedAmount = amount * 4


// Define a new variable and store the reminder when the value of amount is  divided by 21.
var remainderAmount = amount % 21;

```

## var, let and const

Write down the code or if there is any error write down the error.

```js
var user = "Sameer";
// Reassign the value of user to "Sam"
user = "Sam"

// Define a variable with name user with value "Irfan"
var user = "Irfan"


let number = 21;
// Reassign the value of number to 60
number = 60;
// Define another variable called number with the value of 100

const username = "Admin";
// Reassign the value of username to "Arya"
// Define a variable called usernmae with value "John"

// a constant can't be reassigned!
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;
// Check who is older eithe John or Mark
johnAge > markAge
// Check who is younger
johnAge < markAge
// Check if their age is equal
johnAge === markAge
// Create a new variable and assign the age of john to new variable.
var newAge = johnAge
// Check if john is equal to or greater then mark.
johnAge >= markAge
// Check if john is less then or equal to mark.
johnAge <= markAge 
// Calculate the average age of john and mark and assign to a new variable.
var AverageAge = (johnAge + markAge)/2

```


Output of the following and why :

```js
let charactor = "Arya";
charactor = "John";
console.log(typeof charactor);
```

Output of the following and why :

```js
let charactor = "Arya";
console.log(typeof charactor);
charactor = 10;
// string, as typeof will only show what type of value is stored
```

valid or not (why)

```js
null = 10;
console.log(null);
// Invalid! Because Null means the intentional absence of a value.  
```
