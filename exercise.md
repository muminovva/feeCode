[1.Comment Your JavaScript Code](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comment-your-javascript-code)
Solution
```js
/* This is an in-line comment.*/
// This is an in-line comment.//
```
[2.Declare JavaScript Variables](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/declare-javascript-variables)
Solution
```js
var myName;
```
[3.Storing Values with the Assignment Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/storing-values-with-the-assignment-operator)
Solution
```js
var a;
a=7;
```
[4.Assigning the Value of One Variable to Another](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/assigning-the-value-of-one-variable-to-another)
Solution
```js
var a;
a = 7;
var  b;
a=b;
```
[5.Initializing Variables with the Assignment Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/initializing-variables-with-the-assignment-operator)
Solution
```js
var a=9;
```
[6.Declare String Variables](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/declare-string-variables)
Solution
```js
const myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line
```
[7.Understanding Uninitialized Variables](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/understanding-uninitialized-variables)
Solution
```js
var a=1;
var b=5;
var c="I am ";
// Only change code above this line

a = b + 1;
b = b + 5 + b;
c = c + "a String!";
```
[8.Understanding Case Sensitivity in Variables](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/understanding-case-sensitivity-in-variables)
Solution
```js
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Variable assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```
[9.Explore Differences Between the var and let Keywords](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/explore-differences-between-the-var-and-let-keywords)
Solution
```js
let catName = "Oliver";
let catSound = "Meow!";
```
[10.Declare a Read-Only Variable with the const Keyword](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/declare-a-read-only-variable-with-the-const-keyword)
Solution
```js
const FCC = "freeCodeCamp"; // Change this line
let fact = "is cool!"; // Change this line
fact = "is awesome!";
console.log(FCC, fact); // Change this line
```
[11.Add Two Numbers with JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/add-two-numbers-with-javascript)
Solution
```js
const sum = 10 + 10;
```
[12.Subtract One Number from Another with JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/subtract-one-number-from-another-with-javascript)
Solution
```js
const difference = 45 - 33;
```
[13.Multiply Two Numbers with JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/multiply-two-numbers-with-javascript)
Solution
```js
const product = 8 * 10;
```
[14.Divide One Number by Another with JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/divide-one-number-by-another-with-javascript)
Solution
```js
const quotient = 66 / 33;
```

[15.Increment a Number with JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/increment-a-number-with-javascript)
Solution
```js
let myVar = 87;
myVar = ++myVar;
```

[16.Decrement a Number with JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/decrement-a-number-with-javascript)
Solution
```js
let myVar = 11;

myVar = --myVar ;
```

[17.Create Decimal Numbers with JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/create-decimal-numbers-with-javascript)
Solution
```js
const myDecimal = 5.7;
```

[18.Multiply Two Decimals with JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/multiply-two-decimals-with-javascript)
Solution
```js
const product = 2.5 * 2;
```

[19.Divide One Decimal by Another with JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/divide-one-decimal-by-another-with-javascript)
Solution
```js
const quotient = 4.4 / 2; 
```
[20.JavaScript Algorithms and Data Structures
Basic JavaScript
Finding a Remainder in JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/finding-a-remainder-in-javascript)
Solution
```js
const remainder = 11%3;
```
[21.Compound Assignment With Augmented Addition](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/compound-assignment-with-augmented-addition)
Solution
```js
let a = 3;
let b = 17;
let c = 12;

a += 12;
b += 9;
c += 7;
```
[22.Compound Assignment With Augmented Subtraction](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/compound-assignment-with-augmented-subtraction)
Solution
```js
let a = 11;
let b = 9;
let c = 3;

a -= 6;
b -= 15;
c -= 1;
```
[23.Compound Assignment With Augmented Multiplication
](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/compound-assignment-with-augmented-multiplication)
Solution
```js
let a = 5;
let b = 12;
let c = 4.6;

a *= 5;
b *= 3;
c *=10;
```
[24.Compound Assignment With Augmented Division](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/compound-assignment-with-augmented-division)
Solution
```js
let a = 48;
let b = 108;
let c = 33;

a /=12;
b /=4;
c /=11;
```
[25.]()
Solution
```js
```
[26.Quoting Strings with Single Quotes](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/quoting-strings-with-single-quotes)
Solution
```js
const myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```
[27.]()
Solution
```js
```
[28.Concatenating Strings with Plus Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/concatenating-strings-with-plus-operator)
Solution
```js
const myStr = 'This is the start.' + ' This is the end.'; // Change this line
```
[29.Concatenating Strings with the Plus Equals Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/concatenating-strings-with-the-plus-equals-operator)
Solution
```js
let myStr = "This is the first sentence. ";
myStr+= "This is the second sentence."
```
[30.Constructing Strings with Variables](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/constructing-strings-with-variables)
Solution
```js
const myName = "My name is";
const myStr = "Hello "+myName +"and I am well!"

```
[31.Appending Variables to Strings](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/appending-variables-to-strings)
Solution
```js
const someAdjective = " awesome!";
let myStr = "Learning to code is ";
 myStr+= someAdjective
```
[32.Appending Variables to Strings](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/appending-variables-to-strings)
Solution
```js
```
[33.Find the Length of a String](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/find-the-length-of-a-string)
Solution
```js
let lastNameLength = 0;
const lastName = "Lovelace";

// Only change code below this line
lastNameLength = lastName.length;
```
[34.Use Bracket Notation to Find the First Character in a String](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/use-bracket-notation-to-find-the-first-character-in-a-string)
Solution
```js
let firstLetterOfLastName = "";
const lastName = "Lovelace";

// Only change code below this line
firstLetterOfLastName = lastName[0]; // Change this line
```
[35.Understand String Immutability](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/understand-string-immutability)
Solution
```js
let myStr = "Jello World";

// Only change code below this line
myStr = "Hello World"; // Change this line
// Only change code above this line

```
[36.Use Bracket Notation to Find the Nth Character in a String](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/use-bracket-notation-to-find-the-nth-character-in-a-string)
Solution
```js
const lastName = "Lovelace";

// Only change code below this line
const thirdLetterOfLastName = lastName[2]; // Change this line
```
[37.Use Bracket Notation to Find the Last Character in a String](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/use-bracket-notation-to-find-the-last-character-in-a-string)
Solution
```js
const lastName = "Lovelace";

// Only change code below this line
var lastLetterOfLastName = lastName[lastName.length - 1];
```
[38.Use Bracket Notation to Find the Nth-to-Last Character in a String](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/use-bracket-notation-to-find-the-nth-to-last-character-in-a-string)
Solution
```js
const lastName = "Lovelace";

// Only change code below this line
const secondToLastLetterOfLastName = lastName[lastName.length-2]; // Change this line
```
[39.Word Blanks](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/word-blanks)
Solution
```js
const myNoun = "dog";
const myAdjective = "big";
const myVerb = "ran";
const myAdverb = "quickly";

// Only change code below this line
var wordBlanks = "The " + myAdjective + " " + myNoun + " " + myVerb + " " + myAdverb + "." // Change this line
// Only change code above this line

```
[40.Store Multiple Values in one Variable using JavaScript Arrays](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/store-multiple-values-in-one-variable-using-javascript-arrays)
Solution
```js
const myArray = ["",3];
```
[41.Nest one Array within Another Array](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/nest-one-array-within-another-array)
Solution
```js
const myArray = [["Bulls", 23], ["White Sox", 45]];
```
[42.Access Array Data with Indexes](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/access-array-data-with-indexes)
Solution
```js

```
[43.Modify Array Data With Indexes](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/modify-array-data-with-indexes)
Solution
```js
const myArray = [18, 64, 99];
myArray[0]=45;
```
[44.Access Multi-Dimensional Arrays With Indexes](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/access-multi-dimensional-arrays-with-indexes)
Solution
```js
const myArray = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14],
];

const myData = myArray[2][1];
```
[45.Manipulate Arrays With push Method](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/manipulate-arrays-with-push)
Solution
```js
const myArray = [["John", 23], ["cat", 2]];
myArray.push(["dog",3])
```
[46.Manipulate Arrays With pop Method](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/manipulate-arrays-with-pop)
Solution
```js
const myArray = [["John", 23], ["cat", 2]];
var removedFromMyArray = myArray.pop();
```
[47.Manipulate Arrays With shift Method](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/manipulate-arrays-with-shift)
Solution
```js
const myArray = [["John", 23], ["dog", 3]];
var removedFromMyArray = myArray.shift();
```
[48.Manipulate Arrays With unshift Method](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/manipulate-arrays-with-unshift)
Solution
```js
const myArray = [["John", 23], ["dog", 3]];
myArray.shift();
myArray.unshift(["Paul",35]);
```
[49.Shopping List](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/shopping-list)
Solution
```js
const myList = [
  ["Chocolate Bar", 15],
["Umida",20],
["Iroda",18],
["Vohid",18],
["Ozoda",19]
]
```
[50.Write Reusable JavaScript with Functions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/write-reusable-javascript-with-functions)
Solution
```js
function reusableFunction(){
  console.log("Hi World");
}
reusableFunction()
```
[51.Passing Values to Functions with Arguments](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/passing-values-to-functions-with-arguments)
Solution
```js
function functionWithArgs(param1,param2){
  console.log(param1+param2)
}
functionWithArgs(1,2)
```
[52.]()
Solution
```js
```
[53.Global Scope and Functions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/global-scope-and-functions)
Solution
```js
let myGlobal = 10;

function fun1() {
  oopsGlobal = 5;
}

// Only change code above this line
function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
```
[54.Local Scope and Functions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/local-scope-and-functions)
Solution
```js
function myLocalScope() {

  // Only change code below this line
  var myVar;
  console.log('inside myLocalScope', myVar);
}
myLocalScope();

// Run and check the console
// myVar is not defined outside of myLocalScope
console.log('outside myLocalScope', myVar);

```
[55.Global vs. Local Scope in Functions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/global-vs--local-scope-in-functions)
Solution
```js
const outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
const outerWear="sweater"
  // Only change code above this line
  return outerWear;
}

myOutfit();
```
[56.Understanding Undefined Value returned from a Function](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/understanding-undefined-value-returned-from-a-function)
Solution
```js
let sum = 3;

function addFive(num) {
  sum = sum + 5;
}

// Only change code below this line


// Only change code above this line

addFive(5);
```
[57.Assignment with a Returned Value](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/assignment-with-a-returned-value)
Solution
```js
let processed = 2;

function processArg(num) {
  return (num + 3) / 5;
}
processed = processArg(7);
```
[58.Stand in Line](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/stand-in-line)
Solution
```js
function nextInLine(arr, item) {
  // Only change code below this line
   arr.push(item);
  const removed = arr.shift();
  return removed;
  // Only change code above this line
}

// Setup
let testArr = [1, 2, 3, 4, 5];

// Display code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 6));
console.log("After: " + JSON.stringify(testArr));
```
[59.Understanding Boolean Values](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/understanding-boolean-values)
Solution
```js
function welcomeToBooleans() {
  // Only change code below this line

  return true; // Change this line

  // Only change code above this line
}
```
[60.Use Conditional Logic with If Statements](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/use-conditional-logic-with-if-statements)
Solution
```js
function trueOrFalse(wasThatTrue) {
  // Only change code below this line
if(wasThatTrue){
  return "Yes, that was true";
}else{
  return "No, that was false";
}


  // Only change code above this line

}
trueOrFalse(true);
trueOrFalse(false);
```
[61.Comparison with the Equality Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-equality-operator)
Solution
```js
function testEqual(val) {
  if (val==12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testEqual(10);
```
[62.Comparison with the Strict Equality Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-strict-equality-operator)
Solution
```js
function testStrict(val) {
  if (val===7) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testStrict(10);
```
[63.Practice comparing different values](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/practice-comparing-different-values)
Solution
```js
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

compareEquality(10, "10");
```
[64.Comparison with the Inequality Operator]{https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-inequality-operator}
Solution
```js
function testNotEqual(val) {
  if (val!=99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

testNotEqual(10);
```
[65.Comparison with the Strict Inequality Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-strict-inequality-operator)
Solution
```js
function testStrictNotEqual(val) {
  if (val!==17) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

testStrictNotEqual(10);
```
[66.Comparison with the Greater Than Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-greater-than-operator)
Solution
```js
function testGreaterThan(val) {
  if (val>100) {  // Change this line
    return "Over 100";
  }

  if (val>10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

testGreaterThan(10);
```
[67.Comparison with the Greater Than Or Equal To Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-greater-than-or-equal-to-operator)
Solution
```js
function testGreaterOrEqual(val) {
  if (val>=20) {  // Change this line
    return "20 or Over";
  }

  if (val>=10) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

testGreaterOrEqual(10);
```
[68.Comparison with the Less Than Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-less-than-operator)
Solution
```js
function testLessThan(val) {
  if (val<25) {  // Change this line
    return "Under 25";
  }

  if (val<55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

testLessThan(10);
```
[69.Comparison with the Less Than Or Equal To Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-less-than-or-equal-to-operator)
Solution
```js
function testLessOrEqual(val) {
  if (val<=12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }

  if (val<=24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

testLessOrEqual(10);
```
[70.Comparisons with the Logical And Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparisons-with-the-logical-and-operator)
Solution
```js
function testLogicalAnd(val) {
  // Only change code below this line

  if (val <= 50 && val >= 25) {
    return "Yes";
  }

  // Only change code above this line
  return "No";
}

testLogicalAnd(10);
```
[71.Comparisons with the Logical Or Operator](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/comparisons-with-the-logical-or-operator)
Solution
```js
function testLogicalOr(val) {
  // Only change code below this line

  

  if (val > 20 || val < 10) {
    return "Outside";
  }

  // Only change code above this line
  return "Inside";
}

testLogicalOr(15);
```
[72.Introducing Else Statements](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/introducing-else-statements)
Solution
```js
function testElse(val) {
  let result = "";
  // Only change code below this line

  if (val > 5) {
    result = "Bigger than 5";
  }

  else {
    result = "5 or Smaller";
  }

  // Only change code above this line
  return result;
}

testElse(4);
```
[73.Introducing Else If Statements](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/introducing-else-if-statements)
Solution
```js
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }

 else if (val < 5) {
    return "Smaller than 5";
  }
  else{
    return "Between 5 and 10";
  }

  
}

testElseIf(7);
```
[74.Logical Order in If Else Statements](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/logical-order-in-if-else-statements)
Solution
```js
function orderMyLogic(val) {
  if (val < 5) {
    return "Less than 5";
  } else if (val < 10) {
    return "Less than 10";
  } else {
    return "Greater than or equal to 10";
  }
}
```
[75.Chaining If Else Statements](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/chaining-if-else-statements)
Solution
```js
function testSize(num) {
  // Only change code below this line
if(num<5){
  return "Tiny"
}else if (num<10){
  return "Small"
}else if (num<15){
  return "Medium"
}else if (num<20){
  return "Large"
}else if(num>=20){
  return "Huge"
}

  return "Change Me";
  // Only change code above this line
}

testSize(7);
```
[76.Golf Code](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/golf-code)
Solution
```js
const names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];

function golfScore(par, strokes) {
  // Only change code below this line
if(strokes==1){
  return "Hole-in-one!"
}else if(strokes<=par-2){
  return "Eagle"
}else if(strokes==par-1){
  return "Birdie"
}else if (strokes==par){
  return "Par"
}else if (strokes==par+1){
  return "Bogey"
}else if (strokes==par+2){
  return "Double Bogey"
}
else if (strokes>=par+3){
  return "Go Home!"
}
  return "Change Me";
  // Only change code above this line
}

golfScore(5, 4);
```
[77.Selecting from Many Options with Switch Statements](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/selecting-from-many-options-with-switch-statements)
Solution
```js
function caseInSwitch(val) {
  let answer = "";
  // Only change code below this line
switch(val){
  case 1:
  answer="alpha"
  break;
}
switch(val){
  case 2:
  answer="beta"
  break;
}
switch(val){
  case 3:
  answer="gamma"
  break;
}
switch(val){
  case 4:
  answer="delta"
  break;
}



  // Only change code above this line
  return answer;
}

caseInSwitch(1);
```
[78.Adding a Default Option in Switch Statements](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/adding-a-default-option-in-switch-statements)
Solution
```js
function switchOfStuff(val) {
  let answer = "";
  // Only change code below this line
 switch(val){
   case"a":
   answer= "apple";
   break;
   case"b":
   answer= "bird";
   break;
   case"c":
   answer= "cat";
   break;
   default:
   answer="stuff";
 }
 ```
 [79.Multiple Identical Options in Switch Statements](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/multiple-identical-options-in-switch-statements)
 Solution
 ```js
 function sequentialSizes(val) {
  let answer = "";
  // Only change code below this line
switch(val){
  case 1:
  case 2:
  case 3:
    return "Low";
    break;
  case 4:
  case 5:
  case 6:
    return "Mid";
    break;
  case 7:
  case 8:
  case 9:
    return "High";
    break;
}


  // Only change code above this line
  return answer;
}

sequentialSizes(1);
```
[80.Replacing If Else Chains with Switch](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/replacing-if-else-chains-with-switch)
Solution
```js
function abTest(a, b) {
  if (a < 0 || b < 0) {
    return undefined;
  }
  else {
    return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
  }
}
abTest(2, 2);
```