## 1. Array.map()

The `map()` method calls a callback function on every element of an array and returns a new array that contains the results.

The `map()` method takes two named arguments, the first one is required whereas the second one is optional.

**examples**

```
let numbers = [16, 25, 36];
let results = numbers.map(Math.sqrt);
console.log(results);

// output:
  [4, 5, 6]
```

---

## 2. Array.reduce()

The `reduce()` method executes a reducer function for each value of an array, and returns a single value which is the function's accumulated result. and it does not execute the function for empty array elements, also does not change the original array.

**Syntax**
`array.reduce(function(total, currentValue, currentIndex, arr), initialValue)`

**Example**

```
const numbers = [15.5, 2.3, 1.1, 4.7];
document.getElementById("demo").innerHTML = numbers.reduce(getSum, 0);

function getSum(total, num) {
  return total + Math.round(num);
}
```

---

### 3. superagent()

```
const getCharacters=()=>{
  superagent.get('https://swapi.dev/api/people?format=json')
  .then( data => {
    let newData=[];
    let retunedData=data.body.results;
    newData=retunedData.map(el=>{
      let key=el.name;
      let value=el.url;
      return {[key]:value}
    });
    console.log(newData) ;

  })
  .catch(err => console.error(err));
}
getCharacters();

```

```
async function test(cityName) {
  let data = await superagent.get(`https://geocode.xyz/${cityName}?json=1`);
  console.log('latitude ',data.body.latt);
  console.log('longitude ',data.body.longt);
}

test('amman');
```

## 4. promises

A Promise is an object that represents the eventual completion (or failure) of an asynchronous operation, and its resulting value.
It allows you to associate handlers with an asynchronous action’s eventual success value or failure reason.

A Promise exists in one of these states:

1. Pending: initial state, neither fulfilled nor rejected.
1. Fulfilled: operation completed successfully.
1. Rejected: operation failed.


---

## 5. Are all callback functions considered to be Asynchronous? Why or Why Not?

No, not all time.
 a callback doesn't make a function asynchronous,
 for example `forEach` in Array, It iterates over each item and calls the function once per item.

 Calling the argument function is performed as part of normal step-by-step sequential execution of statements that make up the forEach implementation. Throwing an exception in the argument function would reveal a stack trace containing forEach and your function nested inside it.

It is very important to forEach to operate this way. If the argument function would be called asynchronously, code like in the example would not work as expected. The results would be zero each time.


So, for a function to be asynchronous it needs to perform an asynchronous operation. It needs to incorporate the argument callback in handling the results of this asynchronous operation. Only this way the function becomes asynchronous.

For example a function reading contents of a file with the correct encoding can be implemented as an asynchronous function.

```
function readFileAsUtf8(filename, callback) {
  fs.readFile(filename, "utf8", (err, data) => {
    callback(data);
  });
}

```


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com