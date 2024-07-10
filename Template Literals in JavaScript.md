# Template Literals in JavaScript

Template literals are a feature in JavaScript introduced in ES6 that provide an easier and more readable way to work with strings. They are enclosed by backticks (`` ` ``) instead of single or double quotes.

## Features of Template Literals

1. **String Interpolation**:
   - Embed expressions inside a string using `${expression}`.
   ```javascript
   const name = 'Yousef';
   const greeting = `Hello, ${name}!`;
   console.log(greeting); // Output: Hello, Yousef!
   
   const multiLine = `This is a
   multi-line string.`;
   console.log(multiLine);
   
   const a = 10;
   const b = 20;
   const result = `The sum of a and b is ${a + b}.`;
   console.log(result); // Output: The sum of a and b is 30.
   
   const user = {
       name: 'Yousef',
       points: 150,
       level: 'Expert'
   };
   
   const message = `Hello, ${user.name}!
   You have ${user.points} points.
   Your current level is ${user.level}.`;
   
   console.log(message);
   
   // Output:
   // Hello, Yousef!
   // You have 150 points.
   // Your current level is Expert.
   



