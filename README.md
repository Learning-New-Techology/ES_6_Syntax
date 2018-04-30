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

A weird syntax: 

```javascript 
function doSomething()
{
  age=27; 
}
let age=10; 
doSomething();
console.log(age)
```

### A simple class / object 

```javascript
let name='Shiva'; 
let age=25; 

let obj= {
  name:'Hari',  
  age:10,
  printName(){
  console.log(this.name); 
}
}; 

console.log(obj); 
obj.printName()
```

### Loops and arrays
```javascript
let numbers=[1,2,3,4,5]; 

function sumUp(toAdd){
  let result=0; 
  for(let i=0; i<toAdd.length;i++) {
    result=result+toAdd[i]; 
  }
  return result; 
}

console.log(sumUp(numbers))
```

### Get maximum number from a list 

```javascript 
let numbers=[1,2,3,5,10,0,6]; 

function getMaximum(numbers){
  let max=0; 
  for (let i=0;i<numbers.length;i++)
    {
      if (numbers[i]>max){
        max=numbers[i]; 
      }
    }
  return max; 
}
```

###