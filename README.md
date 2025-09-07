1) What is the difference between var, let, and const?

  var, let , const holo variable type

var
var holo purono system.
Eta function scoped. Ekoi nam er variable abar declare kora jai.

let
let holo block scoped. Ekbar declare korle abar declare kora jai na. 

const
const o block scoped. Reassign kora jai na. Kintu object ba array er vitorer value change kora jai.

2) What is the difference between map(), forEach(), and filter()?

map
Prottek element er upor function apply kore. Ekta notun array return kore. Original array change hoy na.

forEach()
Prottek element er upor function chalai. Kono value return kore na. Mainly side effect er jonno use hoy (jemon console.log).

filter()
Condition onujayi element gulo filter kore. Ekta notun array return kore. Original array change hoy na.

3) ES6 e arrow function ki?


Arrow function holo ekta short syntax function likhar jonno. function keyword chara function define kora jai. Arrow function this keyword inherit kore parent scope theke.

const sum = (a, b) => a + b;


4) How does destructuring assignment work in ES6?


Destructuring diye array ba object theke value alada kore variable e rakha jai easily.

Array destructuring
const numbers = [1, 2, 3];
const [a, b] = numbers; // a = 1, b = 2

Object destructuring

const person = { name: "Rahim", age: 25 };
const { name, age } = person; // name = "Rahim", age = 25


5) Explain template literals in ES6. How are they different from string concatenation?

Example
const name = "Rahim";
const greeting = `Hello, ${name}!`; // "Hello, Rahim!"

String concatenation diye korle
const greeting = "Hello, " + name + "!";

Template literals diye code beshi readable hoi.
Multi-line string easily likha jai.
Dynamic string create kora easy hoi.

Read Me By Zarif Hasab