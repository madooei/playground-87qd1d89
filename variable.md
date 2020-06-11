# Declaring Variables

In JS, unlike in Java, you don't declare a variable by specifying its data type. 
Instead, you use the keywords `let` or `const` to declare a variable. 

```javascript runnable
let name = "Jim";
console.log(name);
```

## `const` vs. `let`



## what about `var`?

You can declare variables with `var` keyword too. 

# JavaScript Types

JavaScript has the following types. 

* Numbers
* Boolean
* String
* Object

> Except for _Object_s, all other types are considered **primitive**
> _Symbol_s are new primitive type introduced in ES6 (but not covered in here).

You can use `tyepof` operator to get the type of a variable. 
The special values `null` and `undefined` are used to indicate absence of type.

```javascript runnable
let variable;
console.log(typeof variable);

variable = 6;
console.log(typeof variable);

variable = 'six';
console.log(typeof variable);

variable = false;
console.log(typeof variable);

variable = null;
console.log(typeof variable);

variable = {value: "13", type:"prime"};
console.log(typeof variable);
```