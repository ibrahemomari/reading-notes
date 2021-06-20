# lifecycle of react?
our React components follow this cycle as well: they’re created (mounted on the DOM), they experience growth (by updating) and they die (unmounted from the DOM). This is the component lifecycle! Within the lifecycle of a component, there are different phases. These phases each have their own lifecycle methods. Lets now take a look at these methods. The Lifecycle Methods A component’s lifecycle can be broken down into four parts:

* Initialization
* Mounting
* Updating
* Unmounting

![ html and css](https://www.tutomena.com/static/738b3cb912d2783835719b09be62552c/861bd/reactjs-lifecycle-methods-diagram.png)


### Put the following things in the order that they happen:
 `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`:
 
The order for the previous methods is:
`constructor`
`render`
`componentDidMount`
`React Updates`
`componentWillUnmount`

---

```
componentDidMount() is a hook that gets 
invoked right after a React component has 
been mounted aka after the first render() lifecycle.
```

---

##  we re-render our application 
only be triggered if a component's state has changed. The state can change from a props change, or from a direct setState change. The component gets the updated  state and React decides if it should re-render the component.

# prop VS state ?

![ html and css](https://i.ytimg.com/vi/aLmwln09Tbs/maxresdefault.jpg)

- In a React component, props are variables passed to it by its parent component. State on the other hand is still variables, but directly initialized and managed by the component. The state can be initialized by props
----
![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com