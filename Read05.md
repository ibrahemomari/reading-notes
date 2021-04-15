## COMPARISON OPERATORS :

|OPERATOR| DESCRIPTION |
|---|---|
|(==) equal to|compares two values to see if are the same|
|(!=) not equal|compares two values to see if are not the same|
|(===) strict equal to|compares two values to check that both the data type and value the same |
|(!==) strict not equal to|compares two values to check that both the data type and value are not the same |
|(>) greater than|check if the number in the left is greater than the number on the right|
|(<) less than|check if the number in the left is less than the number on the right|
|(>=) greater than or equal|check if the number in the left is greater than or equal the number on the right|
|(<=) less than or equal|check if the number in the left is less than or equal the number on the right|


---


## LOGICAL OPEOPERATORS 

|OPERATOR|DESCRIPTION|
|---|---|
|(&&) logical and|to test more than one condition|
|(\|\|) logical or  |test at least one condition|
|(!) logical not|takes a single boolean value and inverts it |

---

## LOOPS 


``` loops check a condition , if it returns true , a code block will run , and the condition will be checked again and if it still retuns true , it's repate until the condition returns false  ```


### 1) For loop :

  ``` for(var i=0; i<10; i++) { ``` 
  ``` document.write(i) } ```

  > `for` : keyword
  > `(var i=0; i<10; i++)`: condition (counter)
  > `{document.write(i)}` : for bblock code



  #### about condition (counter ) is contian :

  1. initialization `var i=0 ;`
  2. condition `i<10;`
  3. update `i++`



  > start loop when i=0;
  >> run the code and the i increment 
  >>> if the condition still TRUE , repate the code 





### 1) while loops :

```
var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
}
document .getEl ementByid( ' answer') . innerHTML = msg;
```

_This loop will continue to run for as long as the condition in the parentheses is true. That condition is a counter indicating that, as long as the variable i remains less than 10, the statements in the subsequent code block should run._


  

