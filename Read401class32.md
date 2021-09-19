Context API - Behaviors
===

The React Context API is a way for a React app to effectively produce global variables that can be passed around. This is the alternative to "prop drilling" or moving props from grandparent to child to parent, and so on. Context is also touted as an easier, lighter approach to state management using Redux.

Context API is a (kind of) new feature added in version 16.3 of React that allows one to share state across the entire app (or part of it) lightly and with ease

React.createContext() is all you need. It returns a consumer and a provider. `Provider` is a component that as it's names suggests provides the state to its children. It will hold the "store" and be the parent of all the components that might need that store. `Consumer` as it so happens is a component that consumes and uses the state.

---

Review, Research, and Discussion
===



#### When you have multiple contexts, what component type should you use (class/function) and why?

The static contextType property won’t work if you need more than one, so instead you need to use a context consumer.
#### What are some good use cases for using the Context API for global state?
 when some data needs to be accessible by many components at different nesting levels.

#### How can you best test context?
The best way to test Context is to make our tests unaware of its existence and avoiding mocks. We want to test our components in the same way that developers would use them (behavioral testing) and mimic the way they would run in our applications (integration testing).

---

Document the following Vocabulary Terms
===



**context**
context is related to objects. It refers to the object to which a function belongs. When you use the JavaScript “this” keyword, it refers to the object to which function belongs.

**useContext()**

useContext” hook is used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level.
**static context**
Static context defines items that are needed to prepare executables, items such as the names and types of external variables and functions that will be available at run time as well as compilation modes like backwards compatibility, math mode, and so on.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com