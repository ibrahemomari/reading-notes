![](https://www.dorusomcutean.com/wp-content/uploads/2020/03/crud.jpg)
### 1. In your own words, describe what each group of status code represents:
100’s = informational status codes. [using different protocol , request failure before even sending the body]

200’s = the success codes.[request accepted, if its an async func then that mean the request met all the requirements and not necessarily successful ]

300’s = redirection codes.[resources aren't available ]

400’s = client error codes.[invalid request from the client's end]

500’s =server error codes.[overwhelmed servers or unreachable proxies.]

 

### 2. What is a status code 202?
202 Accepted is used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future.
 

### 3. What is a status code 308?
308 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore.
 

### 4. What code would you use if an update didn’t return data to a client?
204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.
 

### 5. What code would you use if a resource used to exist but no longer does?
410 Gone - This is like 404 but we know that the resource existed in the past, but it got deleted or somehow moved, and we don’t know where.
 

### 6. What is the ‘Forbidden’ status code?
403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.
 

### 7. What is the difference between PUT and PATCH?
PUT will update the whole document but PATCH will update that specific document detail.



---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com