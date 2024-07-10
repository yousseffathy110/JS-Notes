# Type Conversion and Type Coercion in JavaScript

**Type Conversion** and **Type Coercion** are methods to change a value from one data type to another. They differ in how they are implemented and when they are used.

## Type Conversion

Type Conversion, also known as explicit conversion or casting, is the process of converting a value from one data type to another by explicitly specifying the type. This is done by the programmer.

### Example

```javascript
let num = "123";
let convertedNum = Number(num); // Explicitly converts string to number
console.log(convertedNum); // 123
```



# Type Coercion in JavaScript

Type Coercion is the automatic or implicit conversion of values from one data type to another by the programming language during runtime, without explicit instructions from the programmer.

## Key Characteristics

1. **Automatic Conversion**: The language itself handles the conversion.
2. **Context-Dependent**: The conversion rules may vary depending on the operation and the context.
3. **Common in Loosely Typed Languages**: Frequently occurs in languages like JavaScript, where data types are more flexible.

## Examples of Type Coercion

### String to Number Coercion

When performing arithmetic operations, JavaScript can implicitly convert strings to numbers.

```javascript
let result = "5" - 2; // "5" is implicitly coerced to 5, result is 3
let result = "5" + 2; // "2" is implicitly coerced to "2", result is 52
console.log(result); // 3
console.log(5 == "5"); // true, because "5" is coerced to 5
console.log(false == 0); // true, because false is coerced to 0
