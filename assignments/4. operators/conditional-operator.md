## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    let x = 1;
    let y = 2;
    alert (x+y);

    * [ ] Sub
    let number1 = 20;
    let number2 =10;
    alert (number1-number2);

    * [ ] Mul
    let a = 55;
    let b = 60;
    alert (a*b);

    * [ ] Div
    let div1 = 2500;
    let div2 = 5;
    alert (div1/div2);

2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
var firstName = 'John';
var status = 'single';
// Your code goes here
var firstName = 'jhon';
var status = 'single';
let query = prompt(`jhon is single or married ?`)
if (firstName==status) {
  alert('jhon is single');
}
else if (firstName!=status){
  alert(`jhon is married`);
}

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here

var firstNum = prompt('enter first number');
var secondNum = prompt('enter second number');
if (firstNum>secondNum) {
  alert(`${firstNum} first number is larger`)
} else {
  alert(`${secondNum} second number is larger`)
}
```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here

let firstNum=prompt('enter your first number');
var secNum=prompt('enter your second number');
var thirdNum=prompt('enter your third number');
prod=firstNum*secNum*thirdNum;
if(prod<0){
  alert(`${prod}`);
}else {
  alert(`${prod}`);
}
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
let number=prompt('enter your number');
switch(number)
{
  case"1":
  alert("one");
  break;
  case"2":
  alert("two");
  break;
  case"3":
  alert("three");
  break;
  case"4":
  alert("four");
  break;
  case"5":
  alert("five");
  break;
  case"6":
  alert("six");
  break;
  case"7":
  alert("seven");
  break;
  case"8":
  alert("eight");
  break;
  case"9":
  alert("nine");
  break;
  default:
  alert("PLEASE TRY AGAIN");
  break;
}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here
let marks=Number(prompt("enter your mark?"));
switch(true){
  case(marks>90):
  alert("AA")
  break;
  case(marks>=80):
  alert("AB");
  break;
  case(marks>=70):
  alert("BB")
  break;
  case(marks>=60):
  alert("BC");
  break;
  case(marks>=50):
  alert("CC");
  break;
  case(marks>=40):
  alert("CD");
  break;
  case(marks>=30):
  alert("DD");
  break;
  case(marks<=30):
  alert("FF");
  break;
}
```
