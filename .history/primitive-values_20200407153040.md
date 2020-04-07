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

# What is the difference, what is the point?

_It is related to memory management._

- Behind the scene Javascript has to store the values you assign to properties or variables in memory.
- Javascript knows two types of memory. The Stack (Primitive values) and The Heap (reference values).

#### To make a short summary

- _The Stack_ is an easy-to-access memory that simply manages its items as a well stack. This means only items witch size is known in advanced can go onto the stack. This is the case for primitive types. (String, number, boolean...).
- _The Heap_ is simply a memory for items of which you can´t pre-determine the exact size and structure. Since arrays and objects can be mutable (changeable), they have to go to _The Heap_ memory therefore.

[Back to homepage](/README.md)
