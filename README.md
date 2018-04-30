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

