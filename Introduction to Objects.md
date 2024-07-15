# Summary Objects in JavaScript

## Definition

- **Objects**: Collections of related data and/or functionality, stored as key-value pairs.

## Syntax

- **Creation**:
  ```javascript
  let obj = { key1: value1, key2: value2 };
  ```

## Properties

- **Accessing**:

  ```javascript
  obj.key1;
  obj["key2"];
  ```

- **Adding/Modifying:**:

  ```javascript
  obj.key3 = value3;
  obj["key4"] = value4;
  ```

## Methods

- **Function as a Property:**:

  ```javascript
  let obj = {
    method1: function () {
      /* code */
    },
    method2() {
      /* code */
    },
  };
  ```

- **Calling:**:

  ```javascript
  obj.method1();
  ```

## `this` Keyword

- **Context:** Refers to the object from which the method is called .

  ```javascript
  let obj = {
    key: value,
    method() {
      return this.key;
    },
  };
  ```

## Object Methods

- **`Object.keys`:** Returns an array of keys

  ```javascript
  Object.keys(obj);
  ```

- **`Object.values`:** Returns an array of values

  ```javascript
  Object.values(obj);
  ```

- **`Object.entries`:** Returns an array of key-value pairs.

  ```javascript
  Object.entries(obj);
  ```
