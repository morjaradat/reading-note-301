# Passing Functions as Props

- There should be a single “source of truth” for any data that changes in a React application. 

Basic List Component


We can refactor the previous example into a component that accepts an array of numbers and outputs a list of elements.

```
const numbers = [1, 2, 3, 4, 5];
ReactDOM.render(
  <NumberList numbers={numbers} />,
  document.getElementById('root')
);
```
 
- Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:

- The best way to pick a key is to use a string that uniquely identifies a list item among its siblings. Most often you would use IDs from your data as keys:

```
  <li key={todo.id}>
    {todo.text}
  </li>
);
```

- When you don’t have stable IDs for rendered items, you may use the item index as a key as a last resort:

```
  // Only do this if items have no stable IDs
  <li key={index}>
    {todo.text}
  </li>
);
```

- Keys used within arrays should be unique among their siblings.


- JSX allows embedding any expression in curly braces so we could inline the map().

## How to Use the Spread Operator:

- The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

## What is the spread operator?

- The spread operator was added to JavaScript in ES6 (ES2015), just like the rest parameters, which have the same syntax: three magic dots …

## What spread operator used for?

- Spread operator to the rescue! It looks similar to rest parameters, also using ..., but does quite the opposite.

- the spread syntax expands an iterable object, usually an array, though it can be used on any interable, including a string.