Data Modeling
====

##### 1. Name 3 advantages to Test Driven Development?


1. Better program design and higher code quality
2. Detailed project documentation
3. TDD reduces the time required for project development

##### 2. In what case would you need to use beforeEach() or afterEach() in a test suite?

`beforeEach` and `afterEach` can handle asynchronous code in the same ways that tests can handle asynchronous code - they can either take a done parameter or return a promise. For example, if initializeCityDatabase() returned a promise that resolved when the database was initialized.

 use `beforeEach` to do some setup before each test runs in order to avoid repetition. In this case

 `afterEach` runs a function after each one of the tests in this file completes. If the function returns a promise or is a generator, Jest waits for that promise to resolve before continuing.3

 ##### 3. What is one downside of Test Driven Development

 When feature changes, implementation will change as well, and many test cases will fail. ... This problem exists as long as unit test exists, but more severe especially when the test cases are written during TDD. Since during TDD process people tend to focus on implementation, the test cases are more prone to change.

##### 4. What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
* As discussed above ES6 class constructors creates objects by adding function to their prototypes (Blueprint).
* It ensures that this keyword used by the developer is referring to the object being created by the developer. 
* Its syntax is similar to object creation in other object-oriented programming languages.
* This can be said to be a syntax base for constructor functions and instantiate objects using a new operator.


##### 5. Why REST?
1. Easy to Learn and Implement
1. Scalability
1. Cacheable
1. Flexibility and Portability

----
Document the following Vocabulary Terms
====


###### functional programming
functional programming is a programming paradigm where programs are constructed by applying and composing functions.


###### object-oriented programming (OOP)
s a programming paradigm based on the concept of "objects", which can contain data and code: data in the form of fields (often known as attributes or properties), and code, in the form of procedures (often known as methods).


###### class
 the building block, that leads to Object-Oriented programming. It is a user-defined data type, which holds its own data members and member functions, which can be accessed and used by creating an instance of that class. 

###### super
the parent class of the derived one.

###### this 
pointer to the current object you are using.

###### Test Driven Development (TDD)
 is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. This is as opposed to software being developed first and test cases created later.

###### Jest
is a delightful JavaScript Testing Framework with a focus on simplicity.



###### Continuous Integration (CI)
is the practice of merging all developers' working copies to a shared mainline several times a day.Grady Booch first proposed the term CI in his 1991 method, although he did not advocate integrating several times a day. Extreme programming (XP) adopted the concept of CI and did advocate integrating more than once per day – perhaps as many as tens of times per day.


###### REST
a software architectural style which uses a subset of HTTP. It is commonly used to create interactive applications that use Web services. Data Model: is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities

###### Data Model
is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities. ... So the "data model" of a banking application may be defined using the entity-relationship "data model".


----


Preview
===
1. Which 3 things had you heard about previously and now have better clarity on?
abput REST app
1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
testing the routes
1. What are you most excited about trying to implement or see how it works?
a continous api data.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com