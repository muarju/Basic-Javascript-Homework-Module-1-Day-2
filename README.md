# Programming foundations - Basic Javascript Homework Module 1 Day 2

### EXERCISE 1
Enumerate and describe the main datatypes in JavaScript. Try to explain the concepts as you were speaking to a 12 years old. <br>
Answer: 
```
console.log("In JavaScript, there are 6 primitive data types: string, number, boolean, null, undefined, symbol")
```

### EXERCISE 2
Try to describe what a variable is, in your own words. <br>
Answer: 
```
console.log("A variable is a named unit of data that is assigned a value. If the value is modified, the name does not change.")
```

### EXERCISE 3
Write the code to execute an addition (a sum) of the numbers 12 and 20. <br>
Answer: 
```
let sum=12+20
console.log(sum)
```

### EXERCISE 4
Create a variable named x containing the number 12. <br>
Answer: 
```
let x = 12
```

### EXERCISE 5
Create a variable called name containing the string John Doe. <br>
Answer: 
```
let name="John Doe"
```

### EXERCISE 6
Execute a subtraction between the number 12 and the variable x, which is storing the value 12. <br>
Answer: 
```
let ex6result = 12 - x
console.log(ex6result)
```

### EXERCISE 7
Create two variables: name1 and name2. name1 is equal to john, name2 is equal to John.
Verify that name1 is different from name2. 
Verify then, that name1 and name2 are equals if both lowercase (without changing the value of name2).<br>
Answer: 
```
let name1="john"
let name2="John"
if(name1 == name2){
    console.log("The name1 and name 2 are equals")
 }
 else{
    console.log("The name1 and name 2 are not equals")
 }

 if(name1.toLowerCase() == name2.toLowerCase()){
    console.log("The name1 and name 2 are equals in lowerCase")
 }
 else{
    console.log("The name1 and name 2 are not equals in lowerCase")
 }
```

### EXERCISE 8
Create a variable named x (its value must be less than 10). Write the code to print the literal value of x (ex.: if x is 1 print "one", if 5 print "five" etc.).<br>
Answer:
```
let x=5
switch(x){
    case 1:
        console.log("One")
    break;
    case 2:
        console.log("Two")
    break;
    case 3:
        console.log("Three")
    break;
    case 4: 
        console.log("Four")
    break;
    case 5:
        console.log("five")
    break;
    case 6:
        console.log("six")
    break;
    case 7:
        console.log("seven")
    break;
    case 8:
        console.log("eight")
    break;
    case 9: 
        console.log("nine")
    break;
    case 10: 
        console.log("ten")
    default:
        console.log("The number is not between 1 to 10")
}
```

### EXERCISE 9
[Extra] Insert a value in a variable based on the resut of a ternary if (topic not covered during lesson, try to search it by yourself, tomorrow morning we'll discuss it together ;) )<br>
Answer:
```
let ternaryExample = x > 10 ? true : false
```
