const : 
Variables declared with const cannot be reassigned. However, the value they hold can still be mutated if it's an object or an array.
let: 
Variables declared with let can be reassigned, but they have block scope, meaning they are only accessible within the block they are defined in.
var: 
Variables declared with var have function scope, meaning they are accessible throughout the function they are defined in. They can also be reassigned, and they have some quirks related to hoisting that let and const do not have.
