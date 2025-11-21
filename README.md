a) Arrow function isEven(n)
const isEven = (n) => n % 2 === 0;

 b) Rewrite using Ternary Operator
result = marks >= 35 ? "Pass" : "Fail";

 c) Arrow function greet(name) using ternary operator
const greet = (name) => {
  let user = name ? name : "Guest";
  console.log("Hello, " + user);
};

 Shorter version:
const greet = (name) => console.log("Hello, " + (name ? name : "Guest"));
