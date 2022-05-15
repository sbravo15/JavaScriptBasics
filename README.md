# JavaScriptBasics
JS Basics

Data Types
Variables
Functions
Printing logging 

Making Decisions:  Boolean Logic
If 
If Else

Arrays & Loops



# Loops
Loops allow for repetitive or iterative tasks, and can save a lot of time and code. Each iteration can vary in their variables, values, and conditions. There are different types of loops in JavaScript, and they have small differences, but essentially do the same thing: loop over data.


## For Loop
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

## While loop
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
