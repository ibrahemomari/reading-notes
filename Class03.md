# What does .map() return?

### `map()`

creates a new array with the results of calling a function for every array element,also calls the provided function once for each element in an array, in order ,and does not execute the function for array elements without values.


### Parameters: 
This method accepts two parameters as mentioned above and described below:

* **function(currentValue, index, arr):** It is required parameter and it runs on each element of array. It contains three parameters which are listed below:
- **currentValue**: It is required parameter and it holds the value of current element.
- **index**: It is optional parameter and it holds the index of current element.
- **arr**: It is optional parameter and it holds the array.
* **thisValue**: It is optional parameter and used to hold the value of passed to the function.

##### It returns a new array and elements of arrays are result of callback function.


# If I want to loop through an array and display each value in JSX, how do I do that in React?


```
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);

```
we loop through the numbers array using the JavaScript map() function. We return a < li> element for each item. Finally, we assign the resulting array of elements to listItems


# Each list item needs a unique identifies 

# What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:

```
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li key={number.toString()}>
    {number}
  </li>
);
```

---

# What is the spread operator?
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

# List 4 things that the spread operator can do.

1. Copying an array
1. Concatenating or combining arrays
1. Using Math functions
1. Using an array as arguments

# Give an example of using the spread operator to combine two arrays.

```
let fruits = ["apples", "bananas"];
let vegetables = ["corn", "carrots"];
let produce = [...fruits, ...vegetables];

//["apples","bananas","corn","carrots"]
```

# Give an example of using the spread operator to add a new item to an array.

```
const ocean = ['🐙', '🦀'];

const aquarium = [...ocean, '🐡']; // Add a single value
const sushi = [...ocean, '🐡', '🍚']; // Add multiple values

aquarium; // ['🐙', '🦀', '🐡']
sushi; //  ['🐙', '🦀', '🐡', '🍚']

```

# Give an example of using the spread operator to combine two objects into one.

```
let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
};

console.log(employee);
```
##### output 
```
{
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356',
    jobTitle: 'JavaScript Developer',
    location: 'USA'
}
```

---

# In the video, what is the first step that the developer does to pass functions between components?

create a function wherever th state is that we are going to change.

# In your own words, what does the increment function do?

is recive an object , and loop inside th array using map method , then find the matching name and update the count by one 

# How can you pass a method from a parent component into a child component?

by using constructor keyword  then spicify the methods using supr() method.

# How does the child component invoke a method that was passed to it from a parent component?

by using the state method , it can from them invoke the method and update the component methods or attreputs.

----

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com


