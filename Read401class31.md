Context API
===
n a typical React application, data is passed top-down (parent to child) via props, but such usage can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.

**Context** is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult.

Creates a Context object. When React renders a component that subscribes to this Context object it will read the current context value from the closest matching Provider above it in the tree.

The defaultValue argument is only used when a component does not have a matching Provider above it in the tree. This default value can be helpful for testing components in isolation without wrapping them. Note: passing undefined as a Provider value does not cause consuming components to use defaultValue.

---
Review, Research, and Discussion
===

#### Describe use cases for useMemo() and useReducer()
useMemo(): You’re noticing a component’s render is frustratingly slow, and you’re passing a calculation to an unknowable number of children, such as when rendering children using Array.map() or your app often becomes unresponsive because you’re fetching a large amount of data, and having to transform it into a usable format.

useReducer(): useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

#### Why do custom hooks need the use prefix?
React has established this as a naming convention, so it makes it obvious that it is a hook. This is a best practice that should be followed to enhance code readability.

#### What do custom hooks usually do?
React hooks are used for reusable logic, which cleans up your code base and makes it easier to apply the same functionality between components.


#### Using any list of custom hooks, research and name one that you think will be useful in your applications
I found some very useful custom hooks in the article [5 Useful and Modern Custom Hooks](https://dev.to/viclafouch/5-useful-and-modern-custom-hooks-for-your-react-app-3dl) for your React App. One that I found particularly useful was useViewport. This hooks allows you to manage the viewport of a user's device. You can retrieve the width of the screen and whether it corresponds to a mobile device, tablet or desktop.

#### Describe how a hook that fetches API data might work
You could use axios, superagent or fetch to fetch API data and it's likely that you would want to use them with the useEffect hook in order to fetch data when a page loads or re-renders.

---

Document the following Vocabulary Terms
===
**reducer**
Can be used in place of useState and is useful when dealing with complex state logic. It can be used to manage state based on defined actions.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com