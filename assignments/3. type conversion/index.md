## What's the output of the code below
```js
typeof "Joe"; -string.
typeof 4; -Number.
typeof NaN; -"Number"
typeof false; -boolean
typeof function () {}; -function
var phone = 8983700; -Undefined
typeof phone; -Number
typeof null;-object
```

## Output of the code below
```js
// Convert num into string
var num = 45; num=string(num);
String(num);  "45"
String(321);  "321"
String(300 + 23);  "323"
String(false); "false"
String(true);  "true"
Number("3.18");  3.18
Number(" ");    0
Number("");     0
Number("22 44");   NaN
Number(false);   NaN
Number(true); 1
```