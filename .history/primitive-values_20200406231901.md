# Primitive values

_Primitive values are immutable. (Unchangeble)_

- The variable can be reassigned a new value, but the existing value can not be changed in the ways that objects, arrays and functions.

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
