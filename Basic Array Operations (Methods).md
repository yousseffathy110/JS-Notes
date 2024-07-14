# Basic Array Operations (Methods)

Arrays are a fundamental part of JavaScript, used to store multiple values in a single variable. JavaScript provides various methods to manipulate arrays. Below are some of the basic array operations with examples.

## 1. Creating Arrays

Arrays can be created using the `Array` constructor or the array literal syntax.

### Example:

```javascript
// Using array literal syntax
let fruits = ["Apple", "Banana", "Cherry"];

// Using Array constructor
let vegetables = new Array("Carrot", "Broccoli", "Asparagus");
```

## 2.Accessing Array Elements

Array elements can be accessed using their index, starting from 0.

### Example:

```javascript
let fruits = ["Apple", "Banana", "Cherry"];
console.log(fruits[0]); // Output: Apple
console.log(fruits[1]); // Output: Banana
```

## 3. Adding Elements

### push()

Adds one or more elements to the end of an array and returns the new length.

### Example:

```javascript
let fruits = ["Apple", "Banana"];
fruits.push("Cherry");
console.log(fruits); // Output: ["Apple", "Banana", "Cherry"]
```

### unshift()

Adds one or more elements to the beginning of an array and returns the new length.

### Example:

```javascript
let fruits = ["Apple", "Banana"];
fruits.unshift("Cherry");
console.log(fruits); // Output: ["Cherry", "Apple", "Banana"]
```

## 4. Removing Elements

### pop()

Removes the last element from an array and returns that element.

### Example:

```javascript
let fruits = ["Apple", "Banana", "Cherry"];
let removedFruit = fruits.pop();
console.log(removedFruit); // Output: Cherry
console.log(fruits); // Output: ["Apple", "Banana"]
```

### shift()

Removes the first element from an array and returns that element.

### Example:

```javascript
let fruits = ["Apple", "Banana", "Cherry"];
let removedFruit = fruits.shift();
console.log(removedFruit); // Output: Apple
console.log(fruits); // Output: ["Banana", "Cherry"]
```

## 5. Finding Elements

### indexOf()

Returns the first index at which a given element can be found in the array, or -1 if it is not present.

### Example:

```javascript
let fruits = ["Apple", "Banana", "Cherry"];
console.log(fruits.indexOf("Banana")); // Output: 1
console.log(fruits.indexOf("Grapes")); // Output: -1
```

### includes()

Determines whether an array includes a certain value, returning true or false.

### Example:

```javascript
let fruits = ["Apple", "Banana", "Cherry"];
console.log(fruits.includes("Banana")); // Output: true
console.log(fruits.includes("Grapes")); // Output: false
```

## 6. Removing and Adding Elements

### splice()

Adds and/or removes elements from an array.

### Example:

```javascript
let fruits = ["Apple", "Banana", "Cherry"];
// Remove 1 element at index 1 and add "Grapes"
fruits.splice(1, 1, "Grapes");
console.log(fruits); // Output: ["Apple", "Grapes", "Cherry"]
```

## 7. Slicing Arrays

### slice ()

Returns a shallow copy of a portion of an array into a new array object.

### Example:

```javascript
let fruits = ["Apple", "Banana", "Cherry", "Date"];
let slicedFruits = fruits.slice(1, 3);
console.log(slicedFruits); // Output: ["Banana", "Cherry"]
```

## 8. Concatenating Arrays

### concat ()

Merges two or more arrays.

### Example:

```javascript
let fruits = ["Apple", "Banana"];
let vegetables = ["Carrot", "Broccoli"];
let food = fruits.concat(vegetables);
console.log(food); // Output: ["Apple", "Banana", "Carrot", "Broccoli"]
```
