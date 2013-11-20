# Maker.University = function() {

*Introduction to Basic Javascript*


```javascript

// Variables
var variableName;


// Casing
var camelCase;
var PascalCase;
var lowercase;
var UPPERCASE;


// Strings
var myString = "Hello, World!";
var myString = 'Hello, World!';

var escaped = "It's alright";
var escaped = "He is called 'Johnny'";
var escaped = 'He is called "Johnny"';


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
mixed[2]  // "Bill"


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

// Calling Functions
doStuff();

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
var myVal = 5+10; 		  // 15
var myVal = (2*8) + 4; 	  // 20
var myVal = (100/(10*2)); // 5
var myVal = 100 - 250; 	  // -150

// Concatenation
var myName = "Maker" + " " + "University"; // "Maker University"
var myString = "foo" + 5 + "bar"; 		   // "foo5bar"

var firstName = "John";
var lastName = "Doe";
var fullName = firstName + " " + lastName; // "John Doe"

// Returning Values and Leveraging Functions
function getName(){
	return "Bill"
}

var message = "Hello, " + getName(); // "Hello, Bill"

```


**[[⬆]](#TOC)**

# };
