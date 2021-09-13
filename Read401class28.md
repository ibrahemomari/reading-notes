Component Lifecycle / useEffect()
===

One of the most important features that React introduced to us was the virtual DOM, the way we can easily replace a specific element in the DOM by using a virtual DOM to compare with the actual one is very useful. Updating our components is an essential part of our applications. Showing our updated content to our user is essential, we should always know what will be shown to the user after an interaction.

In React, we have something called the React component’s lifecycle. Each React component has its own stages, these stages are known as the React component’s lifecycle.

`useEffect`
It receives a callback function as the first parameter, this callback function is going to be our “effect” and be called. The useEffect Hook is going to be called after every render of our component, that’s why we have a second argument.

---

Review, Research, and Discussion
===


##### Why do we not need more .html pages in a multi-page React app?

React Router to the Rescue

React Router is a great way to build single-page applications because you prevent a page refresh every time a link is clicked. With client-side rendering, the page doesn't refresh as you navigate through the different links. React Router is easy to understand, and simple to implement!

##### If we wanted a component to show up on every page, where would we put it and why?
1. Outside the < BrowserRouter/>
1. Inside the < BrowserRouter />, outside a < Route />
1. Inside a < Route />

> Inside a < Route /> to render it in every page

##### What does routing do with the components that were rendered when a new route is requested
allow to move from component to anthor.
##### What does props.children contain?
can have one element, multiple elements, or none at all, its value is respectively a single child node, an array of child nodes or undefined. Sometimes, we want to transform our children before rendering them — for example, to add additional props to every child. If we wanted to do that, we'd have to take the possible types of this.props.children into account. For example, if there is only one child, we can't map it.
##### How do useState() and this.setState() differ?

`setState` is merging the previous state with the new one, it means that you dont have to pass the full state object every time you want to change some part of the state. React will update given properties and won't touch the rest. 

The `useState's` updater rewrites a previous state with a new one and it does not perform any merging. Its just replacement instead of merging.

---

Document the following Vocabulary Terms
===



**State Hook**

A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We'll learn other Hooks later.
**Mounting and Un-Mounting**

React has a top-level API called unmountComponentAtNode() that removes a component from a specific container. The function unmountComponentAtNode() takes an argument as a container from which the specific component should be removed


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com