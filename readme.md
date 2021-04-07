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
console.log(firstname+' '+lastname) // Aman Thakur
```
### let
``` 
let name;
name = "Aman";
name="Thakur";// change value
console.log(name); // Thakur

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
myBirthday = '14.12.1999;// error can't reassign the constant!

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
```
1 let a = 123;
a =234.5;
```
There are many operations for number , e.g. multiplication * , division / , addition + , subtraction - , and so on.

#### String
 A string in javaScript must be surrounded by quotes.
  ``` 
  let str1 = " hello Aman" ; // hello Aman ;
  let str2 = ' hello Aman'  ;// hello Aman ;
  let str3= `hello Aman ,${str1}`; // hello Aman , hello Aman ;
  ```
  In JavaScript, there are three type of quotes .
  Double quotes: " Hello Aman";
  Single quotes : "Hello Aman";
  Backticks : `Hello Aman`;

  ```
  let name = "Aman" ;
  // embed a variable
   console.log (`Hello ,${name}!`); // Hello , Aman!;
   console.log ("Hello ,${name}!); // Hello ,${name}! ( Double quotes are do nothing);

   ```
   #### Boolean (logical type) 
    The boolean type has only two value :`true` and `false`.
    This type is commonly used to store value yes/no values: `true` means "yes ,correct" , `false` means "no , incorrect".

    ```
    let isGreater = 4>1; 
    console.log (isGreater) // true;
    ```



   



### Non-primitive 
1. Objects
objects such as functions and arrays are referred to as non-primitive values.
