for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
for (let i = 1; i <= 29; i++) {
  console.log(i);
}
let n = prompt("Enter a number");
let sum = 0;
for (let i = 1; i <= n; i++) {
  sum = sum + i;
}
console.log("The sum of first " + n + " numbers is " + sum);
for (let property in object) {
  // code block to be executed
}
let person = {
  name: "Harry",
  age: 30,
  gender: "male"
};

for (let x in person) {
  console.log(x + ": " + person[x]);
}
for (let value of iterable) {
  // code block to be executed
}
let numbers = [1, 2, 3, 4, 5];

for (let number of numbers) {
  console.log(number);
}
