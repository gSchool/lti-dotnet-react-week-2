# React without JSX

React can render elements to the screen with or without JSX. JSX is JavaScript XML and allows you with write HTML in JavaScript.

When rendering without JSX, the code will look something like this:

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

A component can be provided as one of three things:

* a string
* a subclass of `React.Component`
* a plain function.

## Demo without JSX

