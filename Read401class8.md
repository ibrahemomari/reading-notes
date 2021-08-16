Access Control (ACL)
===

##### 1. When is Basic Authorization used vs. Bearer Authorization?

|Basic Authorization|Bearer Authorization|
|--|--|
|The basis Auth allow you to access the API directly with your credential : user/password.|To access the API with a bearer token you will need to make 2 call :one to get the bearer tokenone to get the data|
|The use case for this are integration with reporting tools like PowerBI, Tableau, QLik, BoldBI...|Once you have the bearer token you can reuse it and keep it for up to 60 minutes. You can refresh (to extend the validity) or revoke the bearer (to remove the validity) if needed.|
| calling the API choose "Basic Auth" and fill-in the user password. The information will be encoded with Base64 to avoid to be readable when sent. |It is the recommended Authentication methods whenever possible. It is ideal when scripting, when developing external app or when doing integration with external tools.|
||Make a first call to the UAS endpoint to get a bearer. How to get a bearer Token  Make a call to the API with the retrieve bearer. For instance, in Postman when calling the API choose "Bearer Token" and fill-in the bearer value. |

##### 2. What does the JSON Web Token package do?
is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

##### 3. What considerations should we make when creating and storing a SECRET?
1. choose strong plain-text.
2. encode the SECREAT contant.
3. do not share it.

---

Document the following Vocabulary Terms
===


###Term:
* ###### encryption
 is the process of taking plain text, like a text message or email, and scrambling it into an unreadable format — called “cipher text.” This helps protect the confidentiality of digital data either stored on computer systems or transmitted through a network like the internet.

* ###### token
a process where the client application first sends a request to Authentication server with a valid credentials. The Authentication server sends an Access token to the client as a response. This token contains enough data to identify a particular user and it has an expiry time.

* ###### bearer
is an opaque string, not intended to have any meaning to clients using it. Some servers will issue tokens that are a short string of hexadecimal characters, while others may use structured tokens such as JSON Web Tokens.

* ###### secret
Secret Env Vars are special type of Env Vars as they hide information in an encrypted format so that your private input is not exposed in the build logs/bitrise.yml. Secret Env Vars can be set by adding the Env Var key and the variable in the Secrets tab of the Workflow Editor.

* ###### JSON Web Token
JSON Web Tokens (JWT) are an RFC 7519 open industry standard for representing claims between two parties.



---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com