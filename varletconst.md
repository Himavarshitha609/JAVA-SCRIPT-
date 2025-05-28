//var name = "Harry";
console.log(name); //output: Harry
var name = "Harry";
name = "Ron";
console.log(name); //output: Ron
var name = "Harry";
{
    var name = "Ron";
    console.log(name); //output: Ron
}
console.log(name); //output: Ron
let a = 29

let b = " Harry";
{
let b = "this";
console.log(b); //output: this
}
console.log(b); //output: Harry
const name = " Harry";
name = "this";
console.log(name); //output: Uncaught TypeError: Assignment to constant variable.
const a = "Harry"; //bad
const name = "Harry"; //good
const myName = "Harry"; //good
const myname = "Harry"; //bad
const name = "Harry"; //good
let temporary = 29; //good
var name = "Harry"; //bad
//good:
{
    const name = "Harry";
    const hobby = "programming";

    console.log("My name is " + name + " and I love " + hobby); // output: My name is Harry and I love programming
}
//bad
{
    console.log("My name is " + name + " and I love " + hobby); // output: My name is undefined and I love undefined
    const name = "Harry";
    const hobby = "programming";
}
const name = "Harry"; //good
let name = "Harry"; //fine but const is better because we know that the value of name will not change
var name = "Harry"; //bad
