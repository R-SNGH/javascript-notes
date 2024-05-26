# Episode 6 : undefined(special JS keyword: var assigned memory) vs not defined(var not defined at all) in JS

* In first phase (memory allocation) JS assigns each variable a placeholder called **undefined**.

* **undefined** is when memory is allocated for the variable, but no value is assigned yet.

* If an object/variable is not even declared/found in memory allocation phase, and tried to access it then it is **Not defined**

* Not Defined !== Undefined

![image](https://github.com/R-SNGH/javascript-notes/assets/117880135/3d2ec691-cf7f-4fcc-bdd4-1ee2148f0369)


> When variable is declared but not assigned value, its current value is **undefined**. But when the variable itself is not declared but called in code, then it is **not defined**. 

```js
console.log(x); // undefined
var x = 25;
console.log(x); // 25
console.log(a); // Uncaught ReferenceError: a is not defined
```

* JS is a **loosely typed / weakly typed** language. It doesn't attach variables to any datatype. We can say *var a = 5*, and then change the value to boolean *a = true* or string *a = 'hello'* later on. 
* **Never** assign *undefined* to a variable manually. It is not a good practice.

![image](https://github.com/R-SNGH/javascript-notes/assets/117880135/330acfe7-482e-47b8-bb9d-b46ba0b2e64f)

<hr>

Watch Live On Youtube below:

<a href="https://www.youtube.com/watch?v=B7iF6G3EyIk&ab_channel=AkshaySaini" target="_blank"><img src="https://img.youtube.com/vi/B7iF6G3EyIk/0.jpg" width="750"
alt="undefined vs not defined in JS Youtube Link"/></a>
