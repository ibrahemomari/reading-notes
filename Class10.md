Understanding the JavaScript Call Stack
===

## What is a ‘call’?
s primarily used for function invocation (call). Since the call stack is single, function(s) execution.

## How many ‘calls’ can happen at once?
 is done, one at a time, from top to bottom. It means the call stack is synchronous.

## What does LIFO mean?
 Last In, First Out (LIFO).
is a method of processing data in which the last items entered are the first to be removed.

![](https://media.geeksforgeeks.org/wp-content/uploads/LIFO.jpg)


## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

```
function greeting() {
   // [1] Some code here
   sayHi();
   // [2] Some code here
}
function sayHi() {
   return "Hi!";
}

// Invoke the `greeting` function
greeting();

// [3] Some code here
```

![](https://cdn-media-1.freecodecamp.org/images/QgR2uIk7tW0YNz0Xm8g0jAPeRFI0e4sCejsv)

## What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

```
function callMyself(){
  callMyself();
}

callMyself();
```

The `callMyself() `will run until the browser throws a “Maximum call size exceeded”. And that is a stack overflow.

---

JavaScript error messages
===

1. Reference errors
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

```
console.log(foo) // Uncaught ReferenceError: foo is not defined
```

2. What is a ‘syntax error’?
I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

```
JSON.parse( {'foo': 'bar'} ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1
```
Some syntax errors like sending a trailing comma when calling a function are handled without error by most recent browsers, but older ones you have to be careful.

3. What is a ‘range error’?
Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

```
var foo= []
foo.length = foo.length -1 // Uncaught RangeError: Invalid array length
```
An array for instance cannot have a negative length, why would you mess with the array length? Some people use it to set an array to empty, something of the likes of:

```
var foo = [0, 0]
foo.length = foo.length - 2 // (or foo.length - foo.length)
foo // would log [] instead of [0, 0]
```

4. What is a ‘tyep error’?
Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

```
var foo = {}
foo.bar // undefined
foo.bar.baz // Uncaught TypeError: Cannot read property 'baz' of undefined
```

5. What is a breakpoint?
 achieved by putting a debugger statement in your code in the line you want to break.
 You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. 

6. What does the word ‘debugger’ do in your code? 
help the software development process by identifying coding errors at various stages of the operating system or application development. Some debuggers will analyze a test run to see what lines of code were not executed.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com