# Episode 5 : Shortest JS Program, window & this keyword

* The shortest JS program is empty file. Because even then, JS engine does a lot of things. As always, even in this case, it creates the GEC which has memory space and the execution context.

![image](https://github.com/R-SNGH/javascript-notes/assets/117880135/626198e2-073f-4963-b377-5240b1a9b4bb)


* JS engine creates something known as '**window**'. It is an object, which is created in the global space. It contains lots of functions and variables. These functions and variables can be accessed from anywhere in the program. JS engine also creates a **this** keyword, which points to the **window object** at the global level. So, in summary, along with GEC, a global object (window) and a this variable are created.

![image](https://github.com/R-SNGH/javascript-notes/assets/117880135/6bd43e0a-12b9-4f98-8fec-5a373a016b55)

![image](https://github.com/R-SNGH/javascript-notes/assets/117880135/a446d3cc-7218-415d-a8f4-2f33942c4c10)

![image](https://github.com/R-SNGH/javascript-notes/assets/117880135/51211f1d-e10d-450e-be82-07a242b034bb)


* In different engines, the name of global object changes. Window in browsers, but in nodeJS it is called something else. At global level, this === window

* If we create any variable in the global scope, then the variables get attached to the global object.
Eg:

![image](https://github.com/R-SNGH/javascript-notes/assets/117880135/3de4bf6f-069e-4b22-891f-22318147992a)


To access variables in the global scope, eg:
```js
var x = 10;
console.log(x); // 10
console.log(this.x); // 10
console.log(window.x); // 10
```
![image](https://github.com/R-SNGH/javascript-notes/assets/117880135/1388b105-6e5f-4be0-9a6c-a4b285e19857)

<hr>

Watch Live On Youtube below:

<a href="https://www.youtube.com/watch?v=QCRpVw2KXf8&ab_channel=AkshaySaini" target="_blank"><img src="https://img.youtube.com/vi/QCRpVw2KXf8/0.jpg" width="750"
alt="Shortest JS Program, window & this keyword Youtube Link"/></a>
