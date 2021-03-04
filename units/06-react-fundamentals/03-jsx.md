# React JSX, props, and state



React can render elements to the screen with or without JSX. JSX is JavaScript XML and allows you with write HTML in JavaScript.

## JSX

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

### Resources 

[JSX documentation](https://reactjs.org/docs/jsx-in-depth.html)

## Props

Props are arguments that are passed into React components via HTML attributes.

### Resources

[Props documentation](https://reactjs.org/docs/render-props.html)

## State and Lifecycle Components

### State

A `state` object is a built-in object where property values that belong tot he component are store. When `state` changes, the component re-renders.

### Lifecycle

A component in React has three phases where you can monitor and manipule the component. The phases are:

1. Mounting
2. Updating
3. Unmounting

### Resources

[State and Lifecycle documentation](https://reactjs.org/docs/react-component.html)