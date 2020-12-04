Hello Everyone and Welcome to My Profile

## my goals
- [x] make a github account
- [x] learn `React`
- [x] make Projects

# how a basic react app code looks like in the `App.js` file
## react 17 is current version (will update on later versions)

```js
 import './App.css';
 import logo from './logo.svg';
 
 function App() {
  return (
   <div className="App">
     <img src={logo} />
     
     <h1>React App</h1>
     
     <p>some text</p>
   </div>
  )
 }
 
 export default App;
```

to create a React App run

```js
 npx create-react-app .
 // or
 npm install -g create-react-app
 create-react-app .
```
