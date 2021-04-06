# Variables

A variable is a "named storage" for data.
We used three keyword to declares variables.
1. var 
2. let 
3. const

### var 
```
var firstname = 'Aman'
var lastname ='Thakur'
alert(firstname+' '+lastname)
```
### let
``` 
let name;
name = "Aman";
name="Thakur";// change value
alert(name);

```
We can put any value in the veriable 
We can also change it as many times as we want.

```
let name = 'Aman';
let name = 'thakur'//repeated 'let'leads to an error

```
A variable should be declared only once.
A repeated declaration of the same variable is an error.
so , we should declare a variable once and then refer to it without let.

```
let message ="Hello Aman"
let hello;
 hello = message; // copy "Hello Aman" from message into hello 

alert(message); // Hello Aman
alert (hello); // Hello Aman
```
we can also declare two variables and copy data one into other.

Example of  incorrect variable name :
```
let 1a;//cannot start with a digit 
 let my-name ;// hyphens '-' aren't allowed in the name
 ```

### const
To declare a constant (Unchanging) variable , use const instead of let.
 `const pi = 3.14;`

variable declared using const are called "constant". 
They cannot be reassigned.
```
const myBirthday = '15.5.1999';
myBirthday = '14.12.1999;// error can't reassing the constant!

```


# Datatypes

In javascript there are two types of data types
1. Primitive values
2. Non- primitive values

### Primitive
1. Number
2. String
3. Booleans
4. null
5. undefined

#### Number
The number type represent both integer and floating point numbers.

### Non-primitive 
1. Objects
objects such as functions and arrays are referred to as non-primitive values.
