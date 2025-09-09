1) What is the difference between var, let, and const?
 var: Function-scoped (or globally scoped if declared outside a function). Hoisted to the top of the function/scope but initialized as undefined.

 let: Block-scoped ({ ... }), meaning it only exists inside the block it’s defined in .Hoisted but not initialized (exists in the “Temporal Dead Zone” until declared).
 const: Block-scoped (like let). Same behavior as let (hoisted but in Temporal Dead Zone).


 2) What is the difference between map(), forEach(), and filter()?

 map(): Creates a new array by transforming each element using the callback.
 forEach(): this method happend loop of any array and return nothing
 filter(): this methid return a new array based on condition we set and the new element of new array is thosw whose true

 3) What are arrow functions in ES6?
 Arrow functions are a shorter syntax for writing functions in JavaScript.

 4) How does destructuring assignment work in ES6?
 can extract values from arrays based on their position (index).

 5) Explain template literals in ES6. How are they different from string concatenation?
 Template literals are a new way to create strings in ES6 using backticks ( ` ) instead of quotes (' or ").
 They make it much easier to:

 *Interpolate variables and expressions

 *Write multi-line strings

 *Use tagged templates