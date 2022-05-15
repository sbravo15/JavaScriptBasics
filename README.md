# JavaScriptBasics
JS Basics

Data Types
Variables
Functions
Printing logging 

Making Decisions:  Boolean Logic
If 
If Else

# Arrays & Loops

## Arrays
Syntax to declare an array is a pair of square brackets.
```
let myArray = [];
```
This is an empty array, but arrays can be declared already populated with data. Multiple values in an array are separated by a comma.

```
let iceCreamFlavors = ["Chocolate", "Strawberry", "Vanilla", "Pistachio", "Rocky Road"];
```
The array values are assigned a unique value called the index, a whole number that is assigned based on its distance from the beginning of the array. In the example above, the string value "Chocolate" has an index of 0, and the index of "Rocky Road" is 4. Use the index with square brackets to retrieve, change, or insert array values.

✅ Does it surprise you that arrays start at the zero index? In some programming languages, indexes start at 1. There's an interesting history around this, which you can read on Wikipedia.

```
let iceCreamFlavors = ["Chocolate", "Strawberry", "Vanilla", "Pistachio", "Rocky Road"];
iceCreamFlavors[2]; //"Vanilla"
```
You can leverage the index to change a value, like this:
```
iceCreamFlavors[4] = "Butter Pecan"; //Changed "Rocky Road" to "Butter Pecan"
```
And you can insert a new value at a given index like this:
```
iceCreamFlavors[5] = "Cookie Dough"; //Added "Cookie Dough"
```
✅ A more common way to push values to an array is by using array operators such as `array.push()`

To find out how many items are in an array, use the length property.
```
let iceCreamFlavors = ["Chocolate", "Strawberry", "Vanilla", "Pistachio", "Rocky Road"];
iceCreamFlavors.length; //5
```
✅Try it yourself! Use your browser's console to create and manipulate an array of your own creation.


## Loops
Loops allow for repetitive or iterative tasks, and can save a lot of time and code. Each iteration can vary in their variables, values, and conditions. There are different types of loops in JavaScript, and they have small differences, but essentially do the same thing: loop over data.


### For Loop
The for loop requires 3 parts to iterate:

- `counter` A variable that is typically initialized with a number that counts the number of iterations

- `condition` Expression that uses comparison operators to cause the loop to stop when `true`

- `iteration-expression` Runs at the end of each iteration, typically used to change the counter value

```
// Counting up to 10
for (let i = 0; i < 10; i++) {
  console.log(i);
}
```
✅ Run this code in a browser console. What happens when you make small changes to the counter, condition, or iteration expression? Can you make it run backwards, creating a countdown?

### While loop
Unlike the syntax for the for loop, while loops only require a condition that will stop the loop when true. Conditions in loops usually rely on other values like counters, and must be managed during the loop. Starting values for counters must be created outside the loop, and any expressions to meet a condition, including changing the counter must be maintained inside the loop.

```
//Counting up to 10
let i = 0;
while (i < 10) {
 console.log(i);
 i++;
}
```




Methods
