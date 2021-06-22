# What is a ‘Controlled Component?

 is one that takes its current value through `props` and notifies changes through callbacks like `onChange`. A parent component "controls" it by handling the callback and managing its own state and passing the new values as props to the controlled component. You could also call this a "dumb component".

 ```
<input type="text" value={value} onChange={handleChange} />

 ```

 We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a `“controlled component”`.

 ```
class NameForm extends React.Component {
  constructor(props) {
    super(props);
    this.state = {value: ''};

    this.handleChange = this.handleChange.bind(this);
    this.handleSubmit = this.handleSubmit.bind(this);
  }

  handleChange(event) {
    this.setState({value: event.target.value});
  }

  handleSubmit(event) {
    alert('A name was submitted: ' + this.state.value);
    event.preventDefault();
  }

  render() {
    return (
      <form onSubmit={this.handleSubmit}>
        <label>
          Name:
          <input type="text" value={this.state.value} onChange={this.handleChange} />
        </label>
        <input type="submit" value="Submit" />
      </form>
    );
  }
}

 ```

 #### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

 we set up a kind of circular data flow: state to input value, on change event to state, and back again. This loop allows us a lot of control over the input, as we can react to changes to the value on the fly. Because of this, controlled inputs don’t suffer from the limitations of uncontrolled ones

## How do we target what the user is entering if we have an event handler on an input field?

```
  eventHandler(event) {
    this.setState({value: event.target.value});
  }
```

 # Why would we use a ternary operator?


Use the ternary operator to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms. For example if we were programming a comment form and wanted to ensure that the user entered their email address then we could write something like the following.

```
//is email address specified? Notify customer if not
$email_address = (isset($_POST['email'])) ? $_POST['email'] :
                      die('Please enter your email address');

```
As you can see, the ternary operator can be written on multiple lines. It may be more likely that the email field is empty rather than not set. So instead of checking if the email field is set the following example checks if it is empty.

## Rewrite the following statement using a ternary statement:

```
  if(x===y){
 console.log(true);
  } else {
 console.log(true);
  }
```
### ternary statement:

```
x===y?console.log(true):console.log(true)

```

---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com