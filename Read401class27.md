useState() Hook
===

The useState() is a Hook that allows you to have state variables in functional components. React has two types of components, one is class components which are ES6 classes that extend from React and the other is functional components. Class components a Component and can have state and lifecycle methods: class Message extends React. The useState hook is a special function that takes the initial state as an argument and returns an array of two entries. 

Syntax: The first element is the initial state and the second one is a function that is used for updating the state.

`const [state, setState] = useState(initialstate)`
We can also pass a function as an argument if the initial state has to be computed. And the value returned by the function will be used as the initial state.

`const [sum, setsum] = useState(function generateRandomInteger(){5+7);})`

---

Review, Research, and Discussion
===

##### How does React differ from vanilla JS/HTML/CSS?

React is a Javascript library used for building user interfaces. It allows us to make complex UIs from isolated pieces of code called "components".

React has quickly become one of the most popular Javascript libraries. This is entirely because of its flexibility and the improvement it brings in the performance. React breaks down the UI into smaller and reusable components that can move around data amongst each other. This breaking down of the UI is what gives React an edge over Vanilla JS.

In Vanilla JS, the code becomes very difficult to maintain if the application is large because in such cases the UI needs to be updated regularly. Here, to change a UI element you need to first find the element in the DOM and then update it. This is fine when you have to update only a single element but imagine doing this on long-form which a user needs to fill. This could be very memory and browser intensive.

This is where React comes in with a great feature i.e its own virtual DOM. The virtual DOM is a shortcut to bypass the manual work. It is a lightweight copy of the actual DOM. It has the same properties as the real DOM but lacks the power to make changes on the screen.

The most important and fundamental reason why modern frameworks are used is that, with Vanilla JS, keeping the UI in sync with the state is hard.

##### What is the primary difference between a function component and a class component?


**Functional Components**
1. A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element.
2. There is no render method used in functional components.
3. Also known as Stateless components as they simply accept data and display them in some form, that they are mainly responsible for rendering UI.
4. React lifecycle methods (for example, componentDidMount) cannot be used in functional components.

**Class Components**
1. A class component requires you to extend from React. Component and create a render function which returns a React element.
2. It must have the render() method returning HTML
3. Also known as Stateful components because they implement logic and state
4. React lifecycle methods can be used inside class components (for example, componentDidMount).

---

Document the following Vocabulary Terms
===




**Functional Components**
are basic JavaScript functions. These are typically arrow functions but can also be created with the regular function keyword. Sometimes referred to as “dumb” or “stateless” components as they simply accept data and display them in some form; that is they are mainly responsible for rendering UI.

**Children / Child Components**
A child component is a more specific part inside a parent component.



---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com