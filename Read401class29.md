# Advanced State with Reducers

**Reducers** are functions that take the current state and an action as arguments, and return a new state result. In other words, `(state, action) => newState.`

Using a State Reducer with Hooks

1. End user does an action
1. Dev calls dispatch
1. Hook determines the necessary changes
1. Hook calls dev's code for further changes 👈 this is the inversion of control part
1. Hook makes the state changes

---

# Review, Research, and Discussion

#### How can we ensure that an effect hook runs only once?

given to useEffect after the initial render, you can give it an empty array as second argument.

```javascript
 useEffect(() => {
    loadDataOnlyOnce();
  }, []);
```

#### Can useState() update more than one state variable at the same time?
- To update multiple states on top of the previous state, use setState with the `spread operator ...` . 
- To update multiple states that will override all values in the state, use setState without the spread operator.
#### Is useState() synchronous?
No ,useState is asynchronous

---

Document the following Vocabulary Terms
===



**State Hook**

A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We'll learn other Hooks later.
**Component Lifecycle**
Every React Component has a lifecycle of its own, lifecycle of a component can be defined as the series of methods that are invoked in different stages of the component's existence. ... A React Component can go through four stages of its life as follows.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com