Combined Reducers
===

As your app grows more complex, you'll want to split your reducing function into separate functions, each managing independent parts of the state.

The `combineReducers` helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

The resulting reducer calls every child reducer, and gathers their results into a single state object. The state produced by combineReducers() namespaces the states of each reducer under their keys as passed to combineReducers()

```javascript

rootReducer = combineReducers({potato: potatoReducer, tomato: tomatoReducer})
// This would produce the following state object
{
  potato: {
    // ... potatoes, and other state managed by the potatoReducer ...
  },
  tomato: {
    // ... tomatoes, and other state managed by the tomatoReducer, maybe some nice sauce? ...
  }
}

```


---



##### Why choose Redux instead of the Context API for global state?
Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity.

##### What is the purpose of a reducer?
A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.

##### What does an action contain?
The actions and reducers are the command (write) part of CQRS and is event sourcing, redux is sometimes referred to as an event store. This enables you to add or remove handlers (reducers or middle ware) for your events (actions) that can update the store, dispatch other events (=actions), do asynchronous stuff, write to local storage.
##### Why do we need to copy the state in a reducer?

If the new state is different, the reducer must create new object, and making a copy is a way to describe the unchanged part, so that the application doesn't lose its current state. We're returning a brand new object rather than trying to change state.

---

Document the following Vocabulary Terms
===




**immutable state**
an object whose state cannot be modified after it is created.


**time travel in redux**

Time travel is the ability to move back and forth among the previous states of an application and view the results in real time.

**action creator**
merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store's dispatch() function.


**reducer**
are pure functions in that they produce the same output for a given input. 


**dispatch**
 is a function of the Redux store. You call store. dispatch to dispatch an action. This is the only way to trigger a state change. With React Redux, your components never access the store directly - connect does it for you.


 
---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com