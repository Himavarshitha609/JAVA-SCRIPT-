let a = 5;
let b = 3;

// Addition
let c = a + b; // c is now 8

// Subtraction
let d = a - b; // d is now 2

// Multiplication
let e = a * b; // e is now 15

// Division
let f = a / b; // f is now 1.6666666666666667

// Modulus
let g = a % b; // g is now 2

// Exponentiation
let h = a ** b; // h is now 125
let x = 5;

// Addition assignment
x += 3; // equivalent to x = x + 3
console.log(x); // Output: 8

// Subtraction assignment
x -= 2; // equivalent to x = x - 2
console.log(x); // Output: 6

// Multiplication assignment
x *= 4; // equivalent to x = x * 4
console.log(x); // Output: 24

// Division assignment
x /= 3; // equivalent to x = x / 3
console.log(x); // Output: 8

// Modulus assignment
x %= 5; // equivalent to x = x % 5
console.log(x); // Output: 3
let a = 5;

// Post-increment: returns the value of a, then increments it
console.log(a++); // output: 5
console.log(a);   // output: 6

// Pre-increment: increments the value of a, then returns it
console.log(++a); // output: 7

// Post-decrement: returns the value of a, then decrements it
console.log(a--); // output: 7
console.log(a);   // output: 6

// Pre-decrement: decrements the value of a, then returns it
console.log(--a); // output: 5
console.log(5 > 2); // true
console.log(5 == "5"); // true (type coercion is performed)
console.log(5 === "5"); // false (different types)
console.log(5 != "6"); // true
console.log(5 !== "5"); // true (different types)
const a = 10;
const b = 20;
const c = 30;
console.log(a < b && b < c); // true
console.log(a < b && b > c); // false
const x = 5;
const y = 10;
console.log(x > 3 || y < 5); // true
console.log(x < 3 || y < 5); // false
const z = 10;
console.log(!(z > 5)); // false
console.log(!(z < 5)); // true
