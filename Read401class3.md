# Express REST API

1. _Name 3 real world use cases where you’d want to change the request with custom middleware_ 1. security authentication (login). 2. Track user behavior and stored. 3. Handling error. 4. Hight-level payment method security
   <br>

2. _True or false: The route handler is middleware?_
   - False. A route handler can make requests and get responses without middleware. Middleware can be added to route handlers or other functions to alter/shape requests/responses.

<br>

3. _In what ways can a middleware function end the process and send data to the browser?_
   1. Use of the next()
   2. Through error handling.

<br>

4. _At what point in the request lifecycle can you “inject” middleware?_
   _ Masonite is bootstrapped via Service Providers, these providers load features, hooks, drivers and other objects into the Service Container which can then be pulled out by you, the developer, and used in your views, middleware and drivers.
   _ Middleware functions have access to the request and response objects, and the next() middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.
   <br>

5. _What can cause express to error with “Request headers sent twice, cannot start a second response”_

   - when you send more than one request to the server and make interupt beteen this requests, so kindlly he dell with this requests by send a response have an error.

   ***

# Document the following Vocabulary Term

**Middleware**
functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.

**Request Object**
is the main entry point for an application to issue a request to the Library - all operations on a URL must use a Request object. The request object is application independent in that both servers and clients use the same Request class.

**Response Object**
t is the object which communicates between the server and the output which is sent to the client. To write an ASP page, all you need to do is write a standard HTML page, putting in the Active Server Pages script where needed.

**Application Middleware**
is software that provides services beyond those provided by the operating system to enable the various components of a distributed system to communicate and manage data.

**Routing Middleware**
Routing defines the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware.

**Test Driven Development**
is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. This is as opposed to software being developed first and test cases created later.

**Behavioural Testing**
is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.

---

Preview
===

##### 1. Which 3 things had you heard about previously and now have better clarity on?
1. API Routing
2. Testing code
3. Coustom middleware

##### 2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1. More about testing 
2. Using validation from server side
3. Deal with SQL database

##### 3. What are you most excited about trying to implement or see how it works?
About tracking user data , record data on the database , also mange the API's and build custom validation function from backend.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com