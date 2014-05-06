# function MakerUniversity() {

*Introduction to Basic Javascript*

### Running our server-side JS code
```javascript
cd path/to/code/
node myFile.js
```

### Experimenting with Client Side JS on JS Fiddle
* Visit http://jsfiddle.net/
* Open your Chrome Console
* Fill out JS Box
* Click "Run" or "Save" and view console

* * *

## 1. Variables &amp; Functions
```javascript

// Variables
var variableName;
var someVariable = variableName;


// Casing
var camelCase;
var PascalCase;
var lowercase;
var UPPERCASE;


// Strings
var myString = "Hello, World!";
var myString = 'Hello, World!';

var myString = "It's alright";
var myString = "He is called 'Johnny'";
var myString = 'He is called "Johnny"';
var escaped = "He said \"Javascript\" out loud.";
var escaped = 'Why, It\'s a wonderful day!';

// Numbers
var myNum = 34.00;
var myNum = 34;
var myNum = 8e3; // Scientific exponential notation: 8000


// Booleans
var foo = false;
var bar = true;


// Arrays
var sample = [10, 11, 12];
var mixed = [false, "Bill", 75, someVariable];


// Accessing Arrays
sample[0] // 10
sample[2] // 12
mixed[1]  // "Bill"


// Object Literals
var sample = {
  foo: "bar",
  hello: "world",
  name: "Bill",
  age: 100,
  isQA: true
};


// Accessing Object Literals via dot notation
sample.foo  // "bar"
sample.name // "Bill",
sample.age  // 100


// Accessing Object Literals via bracket notation
sample['hello'] // "world"
sample['isQA']  // true


/*
 * Functions are ways to group blocks of code
 */

// Declaring Functions
function doStuff(){
  // your code
}

var doMoreStuff = function(){
  // do more code
}

// Calling Functions
doStuff();
doMoreStuff();


/*
 * console.log() is a function for writing output to a console.
 * It's parameters are the data structures you wish to log
 */
function sayHello(){
  console.log( "Hello, World!" );
}
sayHello(); // Call our function, outputs "Hello, World!"


// Anonymous Functions (functions with no name, or functions as values):
var myFunction = function(){
  // your code
};
myFunction(); // Call like any other function


/*
 * Operators
 * Add: +
 * Subtract: -
 * Multiply: *
 * Divide: /
 * Modulus: % (division remainder)
 */
var myVal = 5+10;       // 15
var myVal = (2*8) + 4;     // 20
var myVal = (100/(10*2)); // 5
var myVal = 100 - 250;     // -150


// Concatenation
var myName = "Maker" + " " + "University"; // "Maker University"
var myString = "foo" + 5 + "bar";        // "foo5bar"

var firstName = "John";
var lastName = "Doe";
var fullName = firstName + " " + lastName; // "John Doe"


// Returning Values and Leveraging Functions
function getName(){
  return "Bill"
}
var message = "Hello, " + getName(); // "Hello, Bill"


// Calling functions with Parameters
function addFive(num){
  return num+5;
}
var myNum = addFive( 12 ); // 17


/*
 * Complete this JSFiddle: http://jsfiddle.net/jakie8/ELk2y/
 */

```

# };
