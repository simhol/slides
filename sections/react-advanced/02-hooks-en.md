# Hooks

## Hooks

Hooks = extension of function components

A _basic_ function component can render contents based on props and it can trigger events.

Hooks allow for advanced functionality, e.g. having internal component state or listening for lifecycle events.

## Hooks

Hooks are special functions that can be called at the start of a component definition.

Examples:

- `useState(...)`
- `useEffect(...)`
- `useContext(...)`
- ...

## Hooks

> "In the longer term, we expect Hooks to be the primary way people write React components."

\- [React FAQ](https://reactjs.org/docs/hooks-faq.html#should-i-use-hooks-classes-or-a-mix-of-both)

## Hooks: current state

- Documentation for beginners is still very focused on classes
- Not supported by the test library _enzyme_ (https://github.com/airbnb/enzyme/issues/2011)

## Important hooks

- state hook
- effect hook
- context hook
- reducer hook