# reduxdemo

An App providing filter to list of texts using Redux.

[<b>Motivation and why use Redux</b>](https://github.com/fluttercommunity/redux.dart/blob/master/doc/why.md)

## Key Points

- <b>State</b> The state of your whole application is stored in an object tree within a single store.
- <b>Action</b> The only way to change the state is to emit an action, an object describing what happened. Actions are payloads of information that send data from your application to your store.
- <b>Reducers</b> Reducers are just pure functions that take the previous state and an action, and return the next state. Actions describe the fact that something happened, but don't specify how the application's state changes in response. This is the job of reducers.