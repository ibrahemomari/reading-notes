> # Read: 04a - Dynamic web pages with JavaScript


### What is JavaScript ? 

`is a scripting or programming language that allows you to implement complex features on web pages`

`This is where we can change how the page behaves, adding interact ivity. We will aim to keep as much of our JavaScript as possible in separate files.`

---

![JavaScript](https://res.cloudinary.com/practicaldev/image/fetch/s--ohpJlve1--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://res.cloudinary.com/drquzbncy/image/upload/v1586605549/javascript_banner_sxve2l.jpg)

* The extinction of JavaScript fils is **.JS**
* The JavaScript is added last and enhances the usability of the page or the experience of interacting with the site.

### Example :

```
var today= new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
greeting= 'Good evening!';
else if (hourNow > 12) {
greeting = ' Good afternoon!';
else if (hourNow > 0) {
greeting = 'Good morni ng!';
else {
greeting = 'Welcome! ' ;
document .write( ' <h3>' +greeting + ' </ h3>');
 ```


 ### How to creat JavaScript file ?

 1. creat new folder 📂 
 2. creat the JavaScript file, with extinction ( .js ) .
 3. linking to a JavaScript file from an HTML page , like this :
    * 
    ```
    <!DOCTYPE html>
    <html>
    <head>
    <title>Constructive &amp; Co.</ title>
    <link rel ="stylesheet" href="css/ cOl.css" />
    </ head>
    <body>
    <hl>Constructive &amp; Co. </ hl>
    <script src="js/ add-content.js"></ script>
    <p>For all orders and i nquiries please cal l
    <em>SSS-3344</ em></ p>
    </ body>
    </html>

     ```

  4. Start writing your code ☺ .

  ---

  **Note:** ` the script tag must be in th body tag  `


  ---

  ## Placing The Script In The HTML File :

  `to do that :`

  1. open the <script> tag in the <body> tag .
  2. start write your JavaScript code , for Example :
      ```
      <!DOCTYPE html>
      <html >
      <head>
      <title>Constructive &amp; Co.</title>
      <li nk rel ="stylesheet" href="css/ cOl .css" />
      </ head>
      <body>
      <hl>Constructive &amp; Co.</hl>
      <script>document.write(' <h3>Welcome !</h3>');
      </script>
      <p>For all orders and inquiries please call
      <em>555-3344</ em></ p>
      </ body>
      </ html >
      ```
  3. open the HTML file in your web browser .

  ---


   ## How to use object & methods : 

   ## `document.write('good afternoon');`

   * #### `document` : object 
   * #### `.` : member operator 
   * #### `write('good afternoon');` : prameter


   **JavaScript runs where it is found in the html , when browser comes across a <script< element , it stops to load the script and then checks to see if it needs to do anything**


---

# BASIC JAVASCRIPT INSTRUCTIONS :

### STATEMENTS:

- Statements should end with a semicolon.

```
var today= new Date());
var hourNow = today.getHours()) ;
var greeting;
if (hourNow > 18) {
greeting= 'Good evening';
else if (hourNow > 12) {
greeting= 'Good afternoon';
else if (hourNow > O) {
greeting 'Good morning';
else {
greeting 'Welcome';
document.write(greeting) ; 
```

### ` NOTE: JAVASCRIPT IS CASE SENSITIVE`

* STATEMENTS ARE INSTRUCTIONS AN EACH ONE STARTS ON A NEW LINE
* STATEMENTS CAN BE ORGANIZED INTO CODE BLOCKS



### COMMENTS :

You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.

```
/* Th i s script displays a greeting to the user based upon the current time.
It is an example from JavaScript & jQuery book */

var today= new Date();  // Create a new dat e object
var hour Now = today.getHours(); // Find the current hour
var greeting;


// Display the appropriate greeti ng based on the current time

if (hourNow > 18) {
greet ing = 'Good evening ' ;
else if (hourNow > 12) {
greeting = 'Good afternoon';
else if (hourNow > 0) {
greeting= ' Good morning';
else {
greeting = 'Welcome';
}
document.write(greeting) ;
 ```


 **Two type of comments :**

 1. SINGLE-LINE COMMENTS `// your comment `
 2.MULTI-LINE COMMENTS `/* your comment */`

 ---
 

 ## VARIBLES: HOW TO DECLEARE THEM :

 ## `var quantity;`

 * `var` : variable keyword.
 * `quantity`: variable name .

 ---


 ## VARIBLES: HOW TO ASSIGN THEM A VALUE :

 ## ` quantity = 3;`
* `quantity`: variable name .
* `=`: assugnment operator .
* `3`: variable value .



## DATA TYPE:

* NUMERIC DATA TYPE `1 ,55 , 2.5 , 66.445`
* STRING DATA TYPE `Hi , abcd..`
* BOOLEAN DATA TYPE `true , false`


---


## RULES FOR NAMING VARIABLES :

1. The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.
2. The name can contain letters, numbers, dollar sign ($), or an  underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name.
3. You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.
4. All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases.
5. Use a name that describes the kind of information that the variable stores. For example, fi rstName might be used to store a person's first name,l astNarne for their last name, and age for their age.
6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, f i rstName rather than fi rstnarne (this is referred to as camel case). You can also use an underscore between each word (you cannot use a dash).


