Authorization/Authentication
===

#### 1. What header(s) are used in authentication and authorization
`Authenticate`
 response headers define the authentication method that should be used to gain access to a resource. They must specify which authentication scheme is used, so that the client that wishes to authorize knows how to provide the credentials.

 ```
WWW-Authenticate: <type> realm=<realm>
 ```

`Authorization`
request headers contain the credentials to authenticate a user agent with a (proxy) server. Here, the <type> is needed again followed by the credentials, which can be encoded or encrypted depending on which authentication scheme is used.

```
Authorization: Basic YWxhZGRpbjpvcGVuc2VzYW1l
```

#### 2. What is safe to put into a JWT
A JWT needs to be stored in a safe place inside the user's browser. ... To keep them secure, you should always store JWTs inside an httpOnly cookie. This is a special kind of cookie that's only sent in HTTP requests to the server. It's never accessible (both for reading or writing) from JavaScript running in the browser.

#### 3. How are JWTs validated
When you receive a JWT from the client, you can verify that JWT with this that secret key stored on the server. Any modification to the JWT will result in verification (JWT validation) failure. A JWT is simply a string but it contains three distinct parts separated with dots (.)

Document the following Vocabulary Terms
===

**RBAC**
Role-based access control (RBAC) is a method of restricting network access based on the roles of individual users within an enterprise. RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.
**User Roles**
User Roles are permission sets that control access to areas and features within the Professional Archive Platform. Each User account requires a Role assignment.

The Professional Archive Platform contains five standard Roles. These Roles can be assigned to Users as-is, or they can be duplicated and modified to meet your organization’s specifications. Custom Roles can also be created.

```System Admin```: Admins have full access to all platform features enabled for an organization.
```Advanced User```: A Role for team leaders/managers. This Role can access Search, Cases, and Policy dashboards as well as the User-level settings.
```Basic User```: A Role granting access to the platform for periodic review, but without administrative access. This Role has limited access to search, but full access to User-level settings.
```Employee – Personal Access```: For employees who only need to access their Personal Archive and User-level settings.
```Employee – Archive Only```: A Role with no access to any part of the platform.

**JWT Token**

JSON Web Token (JWT) access tokens conform to the JWT standard and contain information about an entity in the form of claims. They are self-contained therefore it is not necessary for the recipient to call a server to validate the token.

---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com