# Introduction to React Hooks and State Hook
## [Greet User](https://sspgreetuser.ccbp.tech/)

- React Hooks
  - Introduction
  - State Hook
- Function Components
  - Adding State
- State Hook
  - Code Execution Flow

### There are two ways to write React Components.
- Function Components
- Class Components
  
## React Hooks
React Hooks are special functions that are a new addition to React.<br/>
They allow us to use **state** and other **React features (lifecycle methods, context, etc)** in the Function Components

### Importance of React Hooks
Easy to reuse logic between the components
Components become simple and easy to understand
Less lines of code
No need of switching between Class & Function Components
Developers and Companies are gradually adapting to React Hooks
### Hooks for Various Purposes
React provides multiple hooks which can be used for different purposes <br/>

- **useState()**   -->	 Add State to Function Components <br/>
- **useEffect()**	 -->   Execute Logic after the Component render <br/>
- **useContext()** -->   Access the Context value <br/>

## State Hook
State Hook is a built-in Hook that allows us to add state to the Function Components.

Syntax: **const [currentState, setterFun] = useState(initialValue).**

useState accepts the ***initial value*** as an argument and returns an array with two values: ***the current state*** and a ***function*** to update it.

In the Class Components, the state is an Object. Where in the Function Components, the state can be of ***any data type*** i.e, boolean, number, string, object, etc.
