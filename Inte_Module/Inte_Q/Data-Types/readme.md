# Javascrpit Data Types

 - Javascript Data Types are divided into 2 parts : 

```
.
├── Data Types
    ├── Primitive Data type  
    ├── Non-Primitive Data type  

```

### Primitive Data Type 

<p>
 In JavaScript, a primitive (primitive value, primitive data type) is data that is not an object and has no methods. 
All primitives are immutable, i.e., they cannot be altered. It is important not to confuse a primitive itself with a variable assigned a primitive value.

</p>


```
This primitive data types can further be classified into - 

    ├── Primitive Data Types
      ├── String
      ├── BigInt
      ├── Undefined
      ├── Null
      ├── Symbol
      ├── Boolean
      └── Number

```

#### String : 
```
It represents a series of characters and is written with quotes. A string can be represented using a single or a double quote.

Example :
 var str = "Vivek Singh Bisht"; //using double quotes
 var str2 = 'John Doe'; //using single quotes
```

#### BigInt : 
```
This data type is used to store numbers which are above the limitation of the Number data type. 
It can store large integers and is represented by adding “n” to an integer literal.

Example :
var bigInteger =  781034890123410789987345674101234567890;
```

#### Undefined : 
```
When a variable is declared but not assigned, it has the value of undefined and it’s type is also undefined.

Example :
var x; // value of x is undefined
var y = undefined; // we can also set the value of a variable as undefined
```

#### Null : 
```
It represents a non-existent or a invalid value.

Example :
var z = null;
```

#### Symbol :
```
It is a new data type introduced in the ES6 version of javascript. It is used to store an anonymous and unique value.

Example :
var symbol1 = Symbol('symbol');
```

#### Boolean :
```
It represents truth and false value.

Example:
var x = true;
var y = false;
```

#### Number : 
```
It represents a number and can be written with or without decimals.

Example :
var x = 3; //without decimal
var y = 3.6; //with decimal
```


