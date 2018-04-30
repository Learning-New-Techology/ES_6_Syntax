# ES_6_Syntax
## JavaScript ES6 Tutorial

### Hello World program 

```javascript
console.log('Hello World!'); 

```
### Variables 
```javascript
var name='George'; 
console.log(name); 
```

### ***Let*** and ***const***
```javascript
let name='George'; 
console.log(name); 
```

let limits the variable within the block scope. 

For example, 

```javascript
let name='George';
if (true) {
	let name='Johh'; 
}
console.log(name); 
```

```javascript
const age=27; 
age=28; // This will give an error. 
console.log(age); 
```

Const will not affect the arrays though as arrays are based on pointers. 

```javascript
const AGES=[10,20,30]; 
console.log(AGES); 
AGES.push(25); 
console.log(AGES); // Prints [10,20,30,25]
``` 

It is same with object as well. 

```javascript 
const OBJ= {
  age: 27
}; 

console.log(OBJ); 
OBJ.age=30; 

console.log(OBJ); 
```
