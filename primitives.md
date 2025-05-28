let nullVar = null;
let numVar = 29;
let boolVar = true;
let bigIntVar = BigInt("567");
let strVar = "harry";
let symbolVar = Symbol("I'm a nice symbol");
let undefinedVar = undefined;
let nullVar = null; // value is intentionally nothing
let undefinedVar; // value is undefined or not defined
console.log(typeof numVar); // Output: number
console.log(typeof strVar); // Output: string
const bioData = {
	name: "Harry",
	age: 29,
	likesJS: true,
	secret: undefined,
};
console.log(bioData["name"]); // Output: Harry
console.log(bioData.age); // Output: 29
console.log(bioData["pet"]); // Output: undefined
const harryMarks = {
	english: 100,
	maths: 80,
	chemistry: 40,
};

const shubhMarks = {
	english: 70,
	maths: 100,
	chemistry: 60,
};
