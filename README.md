# JavaScript-Sheet

## Arithmetic Operations

```javascript
// Division
let result = 14.5 / 3;
console.log(result); // Output: 4.833333

// Floor Division
result = Math.floor(14.5 / 3);
console.log(result); // Output: 4 rounds down to the nearest whole number

// Modulo
result = 14.5 % 3;
console.log(result); // Output: 2.5

// Exponentiation
result = Math.pow(2, 3);
console.log(result); // Output: 8

// Addition
result = 10 + 5;
console.log(result); // Output: 15

// Subtraction
result = 10 - 5;
console.log(result); // Output: 5

// Multiplication
result = 10 * 5;
console.log(result); // Output: 50

// Increment
let number = 5;
number++;
console.log(number); // Output: 6

// Decrement
number = 5;
number--;
console.log(number); // Output: 4
```

## Type Conversion

```javascript
// Integer to Float
let intToFloat = parseFloat(10);
console.log(intToFloat); // Output: 10.0

// Float to Integer
let floatToInt = parseInt(10.5);
console.log(floatToInt); // Output: 10

// Integer to String
let intToStr = String(123);
console.log(intToStr); // Output: '123'

// Float to String
let floatToStr = String(3.14);
console.log(floatToStr); // Output: '3.14'

// String to Integer
let strToInt = parseInt("42");
console.log(strToInt); // Output: 42

// String to Float
let strToFloat = parseFloat("3.14");
console.log(strToFloat); // Output: 3.14

// Array to String
let arrayToStr = JSON.stringify([1, 2, 3]);
console.log(arrayToStr); // Output: '[1,2,3]'

// String to Array
let strToArray = JSON.parse("[1, 2, 3]");
console.log(strToArray); // Output: [1, 2, 3]

// Set to Array
let setToArray = Array.from(new Set([1, 2, 3]));
console.log(setToArray); // Output: [1, 2, 3]

// Array to Set
let arrayToSet = new Set([1, 2, 3]);
console.log(arrayToSet); // Output: Set {1, 2, 3}
```

## String Formatting

```javascript
let thingToDo = "Take it";
let wayToDoIt = "easy";
let pronoun = "dude";

let formattedString = `${thingToDo} ${wayToDoIt} ${pronoun}. But ${thingToDo}!`;
console.log(formattedString);
```

## For Loops

```javascript
let animals = ["tiger", "lion", "bar"];
for (let animal of animals) {
  console.log(animal);
}

for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

## While Loop

```javascript
let count = 0;
while (count < 9) {
  count++;
  console.log(count);
}
```

## Array (List) Operations

```javascript
let newArray = [1, 3, 4, 4, 4, 4, 4, 4, 4, 4, 4, 5, 5, 5];
newArray.push("peanutbutter");
console.log(newArray);

newList.pop();
console.log(newArray);

newList.splice(newList.indexOf(4), 1);
console.log(newArray);
```

## Objects (Dictionaries in python)

```javascript
let myObject = {
  name: "John",
  age: 25,
  isStudent: false,
  tupleKey: "a tuple key",
  floatKey: "a float key",
};

for (let [key, value] of Object.entries(myObject)) {
  console.log(`${key}: ${value}`);
}

console.log(myObject.name);
```

## Conditionals

```javascript
number = 34;
if (number >= 34) {
  print("yes");
} else if (number < 33) {
  print("no");
} else {
  print("not a number!!");
}
```

## Functions

```javascript
//Function Declaration
function add(a, b) {
  return a + b;
}
//Function Expression
const subtract = function (a, b) {
  return a - b;
};
// Arrow function
const multiply = (a, b) => a * b;
```

## Exercises

```javascript
let whereAreMyThings = {
  games: "closet",
  food: "fridge",
  stickynotes: "drawer",
};

for (let key in whereAreMyThings) {
  console.log(`My ${key} is in the ${whereAreMyThings[key]}`);
}

function fizzBuzz() {
  let number = 0;
  while (number < 99) {
    number++;
    if (number % 3 === 0) {
      console.log("fizz");
    } else if (number % 5 === 0) {
      console.log("buzz");
    } else {
      console.log(number);
    }
  }
}

fizzBuzz();
```
