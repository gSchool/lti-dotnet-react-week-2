# Mocks, Stubs, and Spies in JavaScript

## What are Mocks, Stubs, and Spies?

Together, mocks stubs, and spies are known as "test doubles". Use test doubles when a function has side effects (when the result of the function depends on more than what arguments get passed in such as the state of an object or the current time.

### Stubs

Stubs are used to replace target functions/methods. This is great to test how a function handles errors, test asynchronous code, and replace problematic/hard to test code.

### Mocks

Mocks are like stubs but used to test multiple behaviors. 

### Spies

Spies get information about a function such as how many times it's called, what arguments were passed in each call, etc. Use spies to verify that something happened.

## Demo