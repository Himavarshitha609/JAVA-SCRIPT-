let name = "Harry";
let age = 29;
console.log(name + age); // "Harry29"
console.log(typeof name); // "string"
console.log(typeof age); // "number"
const biodata = { 
    name: "Harry",
    age: 30 
};
biodata = 29; // TypeError: Assignment to constant variable
const biodata = { 
    name: "Harry", 
    age: 30 
    };
biodata.address = "123 Main St";
console.log(biodata); // { name: "John", age: 30, address: "123 Main St" }
const months = {
  1: "January",
  2: "February",
  3: "March",
  4: "April",
  5: "May",
  6: "June",
  7: "July",
  8: "August",
  9: "September",
  10: "October",
  11: "November",
  12: "December"
};
