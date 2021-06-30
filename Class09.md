## What is functional programming?

![](https://www.hexacta.com/wp-content/uploads/2015/11/Functional-programming.jpg)

It's a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data .Why is this an impure function?Simply because it uses a global object that was not passed as a parameter to the function.

## What is a pure function and how do we know if something is a pure function?

A pure function is a function which: 

- Given the same input, will always return the same output.

- Produces no side effects.

implement a program requirement using pure functions, you should use them over other options. Pure functions take some input and return some output based on that input. They are the simplest reusable building blocks of code in a program. Perhaps the most important design principle in computer science is KISS (Keep It Simple, Stupid). I prefer Keep It Stupid Simple. Pure functions are stupid simple in the best possible way.

## What are the benefits of a pure function?
Pure functions are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its dependencies, just by reading the function's declaration.

## What is immutability?

structure and properties whose values cannot be changed:
Informing the compiler about the immutability of the variable allows for optimizing the code and logic behind the implementation of the code.

## What is Referential transparency?
are properties of parts of computer programs. An expression is called referentially transparent if it can be replaced with its corresponding value (and vice-versa) without changing the program's behavior.This requires that the expression be pure, that is to say the expression value must be the same for the same inputs and its evaluation must have no side effects. An expression that is not referentially transparent is called referentially opaque.

---

## What is a module?

JS modules (also known as “ES modules” or “ECMAScript modules”) are a major new feature, or rather a collection of new features. You may have used a userland JavaScript module system in the past. Maybe you used CommonJS like in Node.js, or maybe AMD, or maybe something else. All of these module systems have one thing in common: they allow you to import and export stuff.

## What does the word ‘require’ do?

require() is used to consume modules. It allows you to include modules in your app. You can add built-in core Node.js modules, community-based modules (node_modules), and local modules too.

## How do we bring another module into the file the we are working in?
by creating a JavaScript file. Every time you create a new file with .js extension, it becomes a module.

## What do we have to do to make a module available?

We pass the name of the module we want inside the module.exports method.
Example: module.exports=module_name

Then we declare it as avariable in the file we want it to be used in, in the reqiure section



---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com