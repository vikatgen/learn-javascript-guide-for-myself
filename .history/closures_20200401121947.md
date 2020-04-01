# Closures **(Need to learn more)**

_Closures control what is and isnt in scope in a particular function_

- Ability for inner functions to access outer function scope.
- Ability to 'remember' the variables that wew present in function outer scope when they were defined.
- Keep in mind that every time there is a function defined inside another function - the inner one has the access to variables defined in outer function. This applies also to arguments (parameters) of the outer function.
- Closure applies to arrow functions as well as the standard function notation.
- The inner function will have access to the variables in the outer function scrope, even after the outer function has returned.
- Works when you return the inner function.
- Now you have access to 'private' variables.
- Using closure can help us write more readable code.
- A closure in Javascript is like keeping a copy of all the local (inside the function - scoping) variables, just as they were when a function exits.

[Back to homepage](/README.md)
