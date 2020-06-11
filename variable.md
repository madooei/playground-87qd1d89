# JavaScript Types

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