# Primitive values

_Primitive values are immutable. (Unchangeble)_

- There are two types of data in Javascript. (Data types).
- The variable can be reassigned a new value, but the existing value can not be changed in the ways that objects, arrays and functions.
- Data types known as primitive values are:
  - string
  - number
  - boolean
  - undefined
  - null
  - symbol (es6).

```javascript
// Using string methods won´t change the string.

let variable = "immutable";
console.log(variable); //'immutable'

variable.toUpperCase();
console.log(variable); // 'immutable'

// Using an array method will mutate the array.

let array = [];
console.log(array); // []

array.push("mutable");
console.log(array); // ['mutable']

// Assignment gives the primitive a new value (not mutated).

variable = variable.toUpperCase(); // 'IMMUTABLE'
```

[Back to homepage](/README.md)
