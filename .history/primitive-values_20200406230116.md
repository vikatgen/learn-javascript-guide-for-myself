# Primitive values

_Primitive values are immutable. (Unchangeble)_

- The variable can be reassigned a new value, but the existing value can not be changed in the ways that objects, arrays and functions.

  ```javascript
  let variable = "immutable";
  console.log(variable); //'immutable'

  variable.toUpperCase();
  console.log(variable); // 'immutable'
  ```
