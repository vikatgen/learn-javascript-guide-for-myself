# Primitive values

_Primitive values are immutable. (Unchangeble)_

- There are two types of data in Javascript. (Data types).
- Primitive values are values that has a dedivated memory address values on the _Stack Memory_. They are values and doesn´t habe properties.
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

# Reference Values

_They are stored dynamically on the Heap Memory or 'free store'_

- Reference values are defined by properties. There properties are either default properties or added properties.
- Referene values are commonly used on large amount of data.
- Data types for reference values are:
  - Objects
  - Arrays

```javascript
// If you notice, this object holds primitive data types (string and number), this doesn´t affect the object being a reference type.

let person = {
  name: "Gen",
  age: 28
};

// Also this array holds primitive values like string, but still, this does not affect the array being reference type.

let hobbies = ["Camping", "Outdoor activites"];
```

[Back to homepage](/README.md)
