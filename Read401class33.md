< Login /> and < Auth />
===

**ROLE-BASED ACCESS CONTROL (RBAC)**

restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

---

**react-cookies**

`Cookies` are the data stored in the form of key-value pairs that are used to store information about the user on their computer by the websites that the users browse and use it to verify them.

To set or remove the cookies, we are going to use a third-party dependency of react-cookie.

`npm i react-cookies`
`npm install react-cookie`
```javascript
import React from "react";
import ReactDOM from "react-dom";
import { CookiesProvider } from "react-cookie";
import App from "./App";

ReactDOM.render(
   <CookiesProvider>
      <App />
   </CookiesProvider>,
   document.getElementById('root')
);

```

Cookies have six parameters that can be passed to them:

- The name of the cookie.
- The value of the cookie.
- The expiration date of the cookie – this determines how long the cookie will remain active in your browser.
- The path the cookie is valid for – this sets the URL path the cookie us valid in. Web pages outside of that path cannot use the cookie.
- The domain the cookie is valid for. This makes the cookie accessible to pages on any of the servers when a site uses multiple servers in a domain.
- The need for a secure connection – this indicates that the cookie can only be used under a secure server condition, such as a site using SSL.

---

Document the following Vocabulary Terms
===




**global state**
 is a set of local states which are all concurrent with each other.
 A global state in the time domain is also a global state in the causal domain; if two states occur simultaneously, then they cannot have any cause-effect relationship


**global context**
is about how concerned we are worldwide, how we make decisions about global issues and how we can act in a responsible way to make the world a better place.
The opportunities and tensions provided by world- interconnectedness; The impact of decision- making on humankind and the environment.


**provider**
The Provider component accepts a value prop to be passed to consuming components that are descendants of this Provider. One Provider can be connected to many consumers.


**consumer**
consumers that are descendants of a Provider will re-render whenever the Provider’s value prop changes. The propagation from Provider to its descendant consumers (including .contextType and useContext) is not subject to the shouldComponentUpdate method, so the consumer is updated even when an ancestor component skips an update.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com