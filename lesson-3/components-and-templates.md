### What exactly are components

Components are basically the bulding blocks for any react application. They represent a section of user Interface for example:- header,sideNav,main-content,footer and much more.

### Types of components

There are two types of react components this are:
**Stateless Functional Component** - This are javaScript functions whicch maily describe the user interface of the website. An example is shown from the below snippet.

```javascript
function welcome(props) {
  return <h1>Hello Fabulous!</h1>;
}
```

**Stateful class component** - class extending component class
Render method returning `JSX`. For example

```javascript
class Welcome extends React Component{
    render(){
        return <h1>Hello, {this.props.name}</h1>
    }
}
```

Just for the record the more you complicate your application the more you will work with components
A more suitable example is in the following files: - index.js - App.js

### Conclusion

- Components describe a part of the user Interface
- They are re-usable and can be nested inside other componets
- There are two types of components :- Stateful class component and Stateless Functional Component

Happy Coding!
