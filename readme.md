# Table of Contents !
## 1. Scope  
## 2. Hoisting

# What is Scope in Java Script ?
## -Global Scope-
![Global scope](./WhatsApp%20Image%202023-11-16%20at%2000.48.43_887e4845.jpg)
* Variables  declared in global scope and they work in everywhere.
## -Function Scope-
![function scope](./WhatsApp%20Image%202023-11-16%20at%2000.54.29_8d5331fc.jpg) 
* Variables are working only inside  function not outside of function!
* It is called "Local scope"
## -Block Scope-
![block scope](./WhatsApp%20Image%202023-11-16%20at%2000.58.16_b6e04796.jpg)
* Variable are working only inside  block (Block scoped).
* Functions are also  block scoped.

## The Scope Chain
![scope chain](./WhatsApp%20Image%202023-11-16%20at%2001.01.01_35150e74.jpg)
* Explaining about scope chain.

# what is Hoisting in JAva-Script ?
### - Hoisting isa JavaScript mechanism where variables and functiondeclarations are moved to the top of their scope before code execution.
![hoisting](./WhatsApp%20Image%202023-11-16%20at%2001.08.46_97dff649.jpg)
* Hoisting in Java-Script is atype which a function or variable  can be used before declaration.

#### Tmporal Dead Zone Js (TDZ)
* A variable declared with (let) or (const) cannot be accessed until it is declared within its scope.

# Hoisting-Variale (VAR)
* There’s a temptation to think that all of the code you see in a
JavaScript
program is interpreted line-by-line, top-down in order, as the program
execute. While that is essentially true, there’s one part of that as‐
assumption that can lead to incorrect thinking about your program.
![Var](./WhatsApp%20Image%202023-11-16%20at%2001.23.23_02fb9359.jpg)

# Hoisting – function declaration
 * Function declarations in JavaScript are hoisted to the top of the  function or global scope. You can use the function before you declared it:
 
 ![declaration](./WhatsApp%20Image%202023-11-16%20at%2001.23.46_40e957c8.jpg)

 # Temporal dead zone, letand const.
 ![let and const](./WhatsApp%20Image%202023-11-16%20at%2001.24.07_1a2ed819.jpg)
 ### - Different kinds of  error messages!
 * 1 . ReferencesError: Cannot access 'job' before initialization.
 * 2 . ReferencesError: x is not defined.

 ![Hoisting](./WhatsApp%20Image%202023-11-16%20at%2001.33.08_99548772.jpg)

 ### - Using  functions before  actual declaration;
 ### - Var hoisting is just a by product.

 ![tdz](./WhatsApp%20Image%202023-11-16%20at%2001.33.24_de262ebc.jpg) 
 ### - Make it easier to catch errors:



