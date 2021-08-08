# Readings: Express
![](https://res.cloudinary.com/practicaldev/image/fetch/s--KkScstnJ--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zojuy79lo3fn3qdt7g6p.png)
1. What’s the difference between PUT and PATCH?
- The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

2. Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
- [Postman](https://www.postman.com/)
- [Mocky.io](https://designer.mocky.io/)
- [Moockoon](https://mockoon.com/).

3. Compare and contrast Swagger and APIDoc.js Which HTTP status codes should be sent with each type of (un)successful API call?

### Status codes for HTTP response
* Information answers (100-199)
* Responses to success (200-299)
* Retransfers (300-399)
* Errors in the client (400-499)
* Errors with the server (500-599)


### SOAP and REST
* `SOAP` (Simple Object Access Protocol) is a standards-based web services access protocol that has been around for a long time. Originally developed by Microsoft.

* `REST` (Representational State Transfer) is another standard, made in response to SOAP’s shortcomings. It seeks to fix the problems with SOAP and provide a simpler method of accessing web services.

* `The Similarities` While SOAP and REST share similarities over the HTTP protocol, SOAP is a more rigid set of messaging patterns than REST. The rules in SOAP are important because we can’t achieve any level of standardization without them. REST as an architecture style does not require processing and is naturally more flexible. Both SOAP and REST rely on well-established rules that everyone has agreed to abide by in the interest of exchanging information.



#### Differences:
* for `SOAP` :Language, platform, and transport independent (REST requires use of HTTP). for SOAP :Works well in distributed enterprise environments (REST assumes direct point-to-point communication).

* `REST` is more efficient (SOAP uses XML for all messages, REST can use smaller message formats). REST is faster (no extensive processing required). REST is closer to other web technologies in design philosophy.


#### Why we Use TDD:
* “code coverage” is a common approach to evidencing the use of TDD; while high coverage does not guarantee appropriate use of TDD, coverage below 80% is likely to indicate deficiencies in a team’s mastery of TDD.

* version control logs should show that test code is checked in each time product code is checked in, in roughly comparable amounts.



#### CD and CI
ontinuous integration(CI) is a coding philosophy and set of practices that drive development teams to implement small changes and check in code to version control repositories frequently. Because most modern applications require developing code in different platforms and tools, the team needs a mechanism to integrate and validate its changes.



---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com