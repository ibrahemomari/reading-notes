Redux - Additional Topics
===

Redux Toolkit
===

The Redux core library is deliberately unopinionated. It lets you decide how you want to handle everything, like store setup, what your state contains, and how you want to build your reducers.

This is good in some cases, because it gives you flexibility, but that flexibility isn't always needed. Sometimes we just want the simplest possible way to get started, with some good default behavior out of the box. Or, maybe you're writing a larger application and finding yourself writing some similar code, and you'd like to cut down on how much of that code you have to write by hand.

As described in the Quick Start page, the goal of Redux Toolkit is to help simplify common Redux use cases. It is not intended to be a complete solution for everything you might want to do with Redux, but it should make a lot of the Redux-related code you need to write a lot simpler (or in some cases, eliminate some of the hand-written code entirely).

Redux Toolkit exports several individual functions that you can use in your application, and adds dependencies on some other packages that are commonly used with Redux. This lets you decide how to use these in your own application, whether it be a brand new project or updating a large existing app.

---

##### What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
I would use the useEffect() lifecycle hook and thunk middleware to make an API call on pageload.

##### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
You would export action creators.

---

Document the following Vocabulary Terms
===

**middleware**
Software used to provide functionality between applications, tools, or databases.

**thunk**
A middleware for Redux side effects and asynchronous functions.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com