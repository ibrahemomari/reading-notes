Redux - Asynchronous Actions
===

In Part 5: UI and React, we saw how to use the React-Redux library to let our React components interact with a Redux store, including calling useSelector to read Redux state, calling useDispatch to give us access to the dispatch function, and wrapping our app in a < Provider> component to give those hooks access to the store.

So far, all the data we've worked with has been directly inside of our React+Redux client application. However, most real applications need to work with data from a server, by making HTTP API calls to fetch and save items.

In this section, we'll update our todo app to fetch the todos from an API, and add new todos by saving them to the API.

---

Review, Research, and Discussion
===



##### How granular should your reducers be?
They should be as granular as possible in order to enhance UI performance. You should make as few components render on state change as possible.

##### Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
I think this could be a pro or a con. Ideally, you want the fewest possible components to render on state change; however, there are definitely situations where this could be very helpful.
##### Name a strategy for preventing the above
You could use redux-ignore or reduxr-scoped-reduce to ensure only specified reducers listen to an action. You should use very specific names for your actions.


---

Document the following Vocabulary Terms
===

**store**
A store is an object that holds the global state of your application.

**combined reducers**
The combineReducers helper function combines multiple reducers into one function, which can be passed to createStore and allows you to easily access them throughout your application.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com