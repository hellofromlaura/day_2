
* What is scope? Your explanation should include the idea of global vs. local scope. *
JavaScript has two types of scope, one global and one local. If a variable is declared inside a function, it is local 
and it can only be accessed within that function or by functions inside that same function. On the other hand, all variables 
declared outside a function is of a global scope.

* Why are global variables avoided? *
Global variables are avoided as they can cause errors down the line through unintended side effects. Side effects are when 
Functions reach beyond their intended scope. Side effects can lead to indeterminate code, which should be avoided.

* Explain JavaScript's strict mode *
Strict mode exists in JavaScript to make sure people don't create a variable without the keyword var. The strict mode creates
an error when that occur to prevent bad syntax.

* What are side effects, and what is a pure function? *
A side effect is briefly described above, however a pure function is one without unintended side effects, that is determinate. That is, always returns the same result. 

* Explain variable hoisting in JavaScript. *
Hoisting is how the JavaScript interpreter handles variables. The interpreter looks through the entirety of the code and makes note of each variable in memory 'hoisting' them to the top of each scope. This is how functions can be called before they have been declared.