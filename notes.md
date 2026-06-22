## JavaScript
Javascript is developed by Sir brendon Eich in 1995 .
Javascript firstname => mocha
second name => livescript 
Third Name => JavaScript
JavaScript is a object based scripting  language .
1.BOM (Browser Object Model)
    BOM handle the browser related functionalities .
2.DOM (Document Object Model)
    DOM handle the document related functionalities .
But Now JavaScript is a complete programming language .

Netscape navigator was first browser for javascript
first engine of js was Spider Monkey
# Everything in javascript is object .
In 1997 javaScript was standardize .
## ECMA (Europian Computer Manifacturing Association)
It is Organization that decide the standard for computers- .
## ECMA script .

# JavaScript is a interpreted Language .

## Variables
Variables is a value container which is store value in the memory .

1. var (redeclare , reassign , hoisted , global scope) 
2. let (reassign , block scope ) =>  everywhere 
3. const (block scope) => () ,[],{}
4. Automatically

# Rules
1. Variables must have alphnumeric
2. Variables can start with the _ or $
3. variables are case sensitive .
4. variables can not be any predefined keywords .
## Operators -----
Operators are used for performing operation between two operands .
# Types of Operators 
1. Arithematical Operators (+,-,*,/,%,**)
2. Assignment Operators (=,+=,-=,*=,/=,%=)
3. Conditional Operators (<,>,<=,>=,!=,!==,==,===)
4. Logical Operators (&&,||,!)
5. Bitwise Operators .(left shift , right shift ,|,&)
6. Ternary Operators .
7. Increment / Decrement Operators .(++i,i++/--i,i--)
8. Special Operators . (...,?,#,$) etc .

## Datatypes 
    Datatypes tell us what data stored in the memory or variable.
# Types of Datatypes -----------
    1. Primitive Datatypes
        1. Number 
        2. String
        3 BigInt.
        4. undefined
        5. null
        6. Boolean
        7. Symbol
        8. NaN (count nahi karta  hun)
    2.Non-Primitive Datatypes / Referenced Datatype .
        1. Object
            |__
               1. Array
               2. object
        2. function
    
## Conditional Statements  =>
Conditional statements are used for perform the task based on the condition .
1. if
2. else if (ladder if)
3. switch 
    1. break
    2. continue .

# falsy
null , undefined , NaN , infinite,0


 ## Array
array is a collection of multiple data .
array are indexed . 
0 
length -1 

let ar = [1,2,34,45]
# types
1. Using Constructor n=> new Array()
2. Using Literals . => []


## Predefined Methods of Array .
# push
    if you want to add value in the last of an array .

# Traversing Methods .
    map() 

Spread / Rest Operators 
(...)

## 
1. wap to sum of all elements of an array
2. copy all elements of an array to another
<!-- 3. find the duplicate elements in array
4. remove the duplicate elements in array -->
5. perform the sorting on array 
6. find the second smallest and second largest element in array .
7. find the smallest and largest element in array  
<!-- 8. find the missing elements in array  -->
9. add an element on the perticular place of an array .
10. remove the element of an array from particular place .
<!-- 11. find the frequency of each elements in array . -->




## String 
    String is a sequence of charecters .
    1. using ""
    2. using ''
    3. using `` (template literals )
## Functions
function is the block of code which is used to perform a particular task 
## types of functions
 1. Named Function
 2.Anonymous Function
 3.Arrow Function

## Rules
1. Variables must have alphnumeric
2. Variables can start with the _ 
3. variables are case sensitive .
4. variables can not be any predefined keywords or functions .

## Syntax
 function name(){
    // statements
 }

 name()//callig
 ## string methods
 String Method            Description                          Example
--------------------------------------------------------------------------------
length                   Returns string length               "Hello".length → 5

toUpperCase()            Converts to uppercase               "hello".toUpperCase() → "HELLO"

toLowerCase()            Converts to lowercase               "HELLO".toLowerCase() → "hello"

trim()                   Removes spaces from both ends       " hello ".trim() → "hello"

slice(start, end)        Extracts part of a string           "Hello".slice(1, 4) → "ell"

substring(start, end)    Extracts characters                 "Hello".substring(1, 4) → "ell"

replace()                Replaces first match                "Hello".replace("H", "J") → "Jello"

replaceAll()             Replaces all matches                "a-a-a".replaceAll("a", "b") → "b-b-b"

split()                  Splits into an array               "a,b,c".split(",") → ["a", "b", "c"]

concat()                 Joins strings                       "Hello".concat(" World") → "Hello World"

includes()               Checks if text exists               "Hello".includes("ell") → true

startsWith()             Checks beginning                    "Hello".startsWith("He") → true

endsWith()               Checks ending                       "Hello".endsWith("lo") → true

indexOf()                First occurrence position           "Hello".indexOf("l") → 2

lastIndexOf()            Last occurrence position            "Hello".lastIndexOf("l") → 3

charAt(index)            Character at position               "Hello".charAt(1) → "e"

charCodeAt(index)        Unicode value                       "A".charCodeAt(0) → 65

repeat(n)                Repeats string                      "Hi".repeat(3) → "HiHiHi"
## Example
let str = "  Hello JavaScript  ";

console.log(
  str.length,                    // 20
  str.trim(),                    // Hello JavaScript
  str.toUpperCase(),             //   HELLO JAVASCRIPT
  str.toLowerCase(),             //   hello javascript
  str.slice(2, 7),               // Hello
  str.replace("JavaScript", "JS"), //   Hello JS
  str.includes("Hello"),         // true
  str.split(" ")                 // ["", "", "Hello", "JavaScript", "", ""]
);
## function
function is the block of code which is used to perform particular task
# types of function
Function Declaration  → Named function, hoisted.
Function Expression   → Function stored in a variable.
Arrow Function        → Short ES6 function syntax.
Anonymous Function    → Function without a name.
IIFE                  → Runs immediately after creation.
Callback Function     → Passed as an argument to another function.
Higher-Order Function → Accepts or returns functions.
Constructor Function  → Creates objects using new.
Generator Function    → Uses yield to pause/resume execution.
Async Function        → Handles asynchronous code with async/await.
##    pattern
 *
 * *
 * * *
 * * * *

## object
object in javascript are the collection of methods and properties in js.
## types of object 
1.BOM(Browser object Model)
2.DOM(Document object Model)
## Way to crteate and object 
1. using constructor 
ex-
const a=nerw