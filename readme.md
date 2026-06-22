# JavaScript Variables

## What is a Variable?

Variable ek container hota hai jo data store karta hai.

```js
let name = "Tony Stark";
let age = 24;
```

---

## Common Data Types

* **String** → `"Hello"`
* **Number** → `25`, `99.9`
* **Boolean** → `true`, `false`
* **Null** → Empty value
* **Undefined** → Value assign nahi hui

---

## Variable Naming Rules

✅ Allowed:

* Letters (`name`)
* Underscore (`_name`)
* Dollar Sign (`$name`)
* Digits after first character (`name12`)

❌ Not Allowed:

* Number se start (`123name`)
* Spaces (`full name`)
* Reserved keywords (`let`, `const`, `function`)

---

## Case Sensitive

```js
let fullname = "Sudheer";
let fullName = "Kuhu";
```

Dono alag variables hain.

---

## var, let, and const

| Feature      | var | let | const |
| ------------ | --- | --- | ----- |
| Re-declare   | ✅   | ❌   | ❌     |
| Update Value | ✅   | ✅   | ❌     |
| Block Scope  | ❌   | ✅   | ✅     |

### var

* Re-declare kar sakte hain.
* Update kar sakte hain.

### let

* Re-declare nahi kar sakte.
* Update kar sakte hain.

### const

* Re-declare nahi kar sakte.
* Update nahi kar sakte.
* Declaration ke time value dena zaroori hai.

---

## Undefined

```js
let a;
console.log(a); // undefined
```

---

## Best Practices

* `const` by default use karo.
* Value change ho to `let` use karo.
* `var` avoid karo.
* camelCase naming convention follow karo.

Examples:

```js
const PI = 3.14;
let totalPrice = 999;
let userAge = 24;
```

---

## Summary

* Variables data store karte hain.
* JavaScript case-sensitive hai.
* Variable names number se start nahi ho sakte.
* `let` aur `const` modern JavaScript me preferred hain.
* `const` ko declaration ke time value dena mandatory hai.

## Arrays 
collection of  item or  multiple data
1. hum chahe to same  string digt squar braces ke andr bna skte
2. ya to similar hi data ka raays best aproaches hai
3. string imugtable
4. array immutable ar[0]=66
. for of loop yani 
  for (let city of cities) {
        console.log(city.toUpperCase());
      }///city name bade  letter me aur sab city print 

5. for of loop direct value deta hai index nhi deta hai
6. for loop with indexing value dega
# methd arrays
1.push // add end
2.pop//remove end
3.toString // convert array to string
4.concate() // join multiple arrays
5. unshift() // add start
6. shift() // deleted start 
7. slice(); //return piece of array     eg slice(startindx,endindx)
8. splice    //change original array (add,remove,replace)

splice(statindx,delcount,newE1..)

## JavaScript Data Types – Short Definitions
# Primitive Data Types
1. Number

Numbers (numeric values) ko store karta hai.

2. String

Text ya characters ko store karta hai.

3. Boolean

Sirf true ya false value ko store karta hai.

4. Undefined

Jab variable declare ho lekin usme koi value assign na ki gayi ho.

5. Null

Empty ya intentionally no value ko represent karta hai.

6. BigInt

Bahut badi integer values ko store karta hai.

7. Symbol

Unique aur immutable value create karta hai.

Non-Primitive Data Types
8. Object

Key-value pairs ke roop me data store karta hai.

9. Array

Multiple values ko ek hi variable me store karta hai.

10. Function

Reusable code block hota hai jo specific task perform karta hai.



## OPERATOR
JavaScript Operators (हिंदी में)

परिभाषा:
JavaScript में Operator एक विशेष चिन्ह (Symbol) होता है जो Variables और Values पर कोई Operation (कार्य) करता है।

1. Arithmetic Operators
   1, +, -, *, /, %, **
    2. MODULUS % REMAINDER
    3. exponentation 2**3
    4. increment  a++ ==>a=a+1
    5. decrement   a-- ==>a=a-1

परिभाषा: Arithmetic Operators का उपयोग गणितीय गणनाएँ (जोड़, घटाव, गुणा, भाग आदि) करने के लिए किया जाता है।

Operators: +, -, *, /, %, **

2. Assignment Operators

परिभाषा: Assignment Operators का उपयोग Variables को Value Assign (मान देने) के लिए किया जाता है।

Operators: =, +=, -=, *=, /=, %=


a+=1 =>a=a+1,   a+=4==>a=a+4

3. Comparison Operators

परिभाषा: Comparison Operators दो Values की तुलना करते हैं और परिणाम true या false के रूप में देते हैं।

Operators: ==, ===, !=, !==, >, <, >=, <=

4. Logical Operators

परिभाषा: Logical Operators एक या अधिक Conditions को जोड़ने तथा उनका Logical Result प्राप्त करने के लिए उपयोग किए जाते हैं।

Operators: && (AND), || (OR), ! (NOT)



Operator: --

7. Conditional (Ternary) Operator

परिभाषा: Ternary Operator if-else का संक्षिप्त रूप है, जिसका उपयोग Condition के आधार पर निर्णय लेने के लिए किया जाता है।

Operator: ?:

8. String Operator

परिभाषा: String Operator दो या अधिक Strings को जोड़ने (Concatenate) के लिए उपयोग किया जाता है।

Operator: +

9. Type Operator

परिभाषा: Type Operator किसी Variable या Value के Data Type की जानकारी प्राप्त करने के लिए उपयोग किया जाता है।

Operator: typeof

# JavaScript Conditional Statements (Notes with Examples & Output)

## 1. if Statement

### Definition
Agar condition true hai to code execute hoga.



### Example
javascript

. let age = 20;

if (age >= 18) {
    console.log("Adult");
}

### Output

```text
Adult
```

---

## 2. if...else Statement

### Definition
Agar condition true hai to if block chalega, warna else block chalega.

### Syntax

```javascript
if (condition) {
    // code
} else {
    // code
}
```

### Example

```javascript
let age = 16;

if (age >= 18) {
    console.log("Adult");
} else {
    console.log("Minor");
}
```

### Output

```text
Minor
```

---

## 3. else if Statement

### Definition
Multiple conditions check karne ke liye use hota hai.

### Syntax

```javascript
if (condition1) {
    // code
}
else if (condition2) {
    // code
}
else {
    // code
}
```

### Example

```javascript
let marks = 85;

if (marks >= 90) {
    console.log("Grade A");
}
else if (marks >= 75) {
    console.log("Grade B");
}
else if (marks >= 50) {
    console.log("Grade C");
}
else {
    console.log("Fail");
}
```

### Output

```text
Grade B
```

---

## 4. Nested if Statement

### Definition
Jab ek if ke andar doosra if ho.

### Example

```javascript
let age = 20;
let citizen = true;

if (age >= 18) {
    if (citizen == true) {
        console.log("Eligible for Voting");
    }
}
```

### Output

```text
Eligible for Voting
```

---

## 5. Ternary Operator

### Definition
if...else ka short form.

### Syntax

```javascript
condition ? trueValue : falseValue;
```

### Example

```javascript
let age = 18;

let result = age >= 18 ? "Adult" : "Minor";

console.log(result);
```

### Output

```text
Adult
```

---

## 6. switch Statement

### Definition
Multiple fixed values check karne ke liye use hota hai.

### Syntax

```javascript
switch(expression) {
    case value1:
        // code
        break;

    case value2:
        // code
        break;

    default:
        // code
}
```

### Example

```javascript
let day = 2;

switch(day) {
    case 1:
        console.log("Monday");
        break;

    case 2:
        console.log("Tuesday");
        break;

    case 3:
        console.log("Wednesday");
        break;

    default:
        console.log("Invalid Day");
}
```

### Output

```text
Tuesday
```

---

# Quick Revision

| Statement | Use |
|-----------|-----|
| if | Ek condition check karne ke liye |
| if...else | True aur False dono cases handle karne ke liye |
| else if | Multiple conditions check karne ke liye |
| Nested if | if ke andar if |
| Ternary Operator | Short form of if...else |
| switch | Multiple fixed values check karne ke liye |

## Trick

- One Condition → if
- Two Choices → if...else
- Many Conditions → else if
- if ke andar if → Nested if
- Short Form → Ternary Operator
- Fixed Values → switch
## 