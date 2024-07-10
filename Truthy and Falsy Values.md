# Truthy and Falsy Values

In JavaScript, every value is inherently "truthy" or "falsy". Understanding these concepts is crucial for writing effective conditional statements.

## Truthy Values

Values that are considered true when evaluated in a Boolean context:
- All non-empty strings (`"hello"`, `"0"`)
- All numbers except `0` and `NaN`
- `true`
- Objects (including arrays and functions)
- The value `Infinity`

Example:
```javascript
if ("hello") {
  console.log("This is truthy.");
}
```



## Falsey values

Values that are considered false when evaluated in a Boolean context:

- Empty strings (`""`)
- `0`
- `NaN`
- `null`
- `undefined`
- `false`

Example:

 ```javascript if ("hello") {  console.log("This is truthy."); }
 if (0) {
   console.log("This is falsy.");
 } else {
   console.log("This is truthy.");
 }
 ```