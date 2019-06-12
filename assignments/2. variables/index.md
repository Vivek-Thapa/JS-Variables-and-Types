1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
name is the name of the variable.
```

2. Find the error if any
```js
  var product cost = 3.45;
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" right.
  'Hello World"
  wrong
  "Hello World'
    wrong
  'Hello World' right.
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
```

## Basic Operations

Mathematical Operations:

```js
var amount = 2080;
// Mathematical Operations:
// Define a new variable and store the value that is 80 less then the value of amount.
var lessAmount = amount-80

// Define a new variable and store the value that is 200 more then the value of amount.

var moreAmount = amount+200

// Define a new variable and store the value that is 4 times the value of amount.



// Define a new variable and store the reminder when the value of amount is  divided by 21.

var remAmount = amount%21
```
Logical Operation
```js
var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark
var jhonAge = 45;
var markAge = 35;
var result=(jhonAge >markAge);
alert (`${result}  jhon is older`);

// Check who is younger
var jhonAge = 45;
var markAge = 35;
var result =(jhonAge>markAge);
alert (`${result}  mark is younger`);
// Check if their age is equal
var jhonAge = 45;
var markAge = 35;
var result =(jhonAge!==markAge);
alert (`${result}  the age is not equal`);

// Create a new variable and assign the age of john to new variable.

var newAge = jhonAge;
var result =(newAge=jhonAge);
alert (`${result}  new age is the age of jhon`);
// Check if john is equal to or greater then mark.
var jhonAge = 45;
var markAge = 35;
var result =(jhonAge>=markAge);
alert (`${result}  the age of jhon is not equal but greater than that of mark`);

// Check if john is less then or equal to mark.
var jhonAge = 45;
var markAge = 35;
var result =(jhonAge>=markAge);
alert (`${result}  the age of jhon is neither less nor equal to that of mark`);

// Calculate the average age of john and mark and assign to a new variable.
var jhonAge = 45;
var markAge = 35;
var result =(jhonAge+markAge);
alert (`${result/2}  the average age`);


```