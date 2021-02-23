# React JSX

React can render elements to the screen with or without JSX. JSX is JavaScript XML and allows you with write HTML in JavaScript.

Without JSX, Hello, World Looks like this.
```js
class Hello extends React.Component {
  render() {
    return React.createElement('div', null, `Hello ${this.props.toWhat}`);
  }
}

ReactDOM.render(
  React.createElement(Hello, {toWhat: 'World'}, null),
  document.getElementById('root')
);

```

This would be the equivalent of this:

```js
class Hello extends React.Component {
  render() {
    return <div>Hello {this.props.toWhat}</div>;
  }
}

ReactDOM.render(
  <Hello toWhat="World" />,
  document.getElementById('root')
);
```

## Demo JSX

## Resources 

(JSX documentation) [https://reactjs.org/docs/jsx-in-depth.html]

