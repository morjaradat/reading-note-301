# React Docs - lists and keys

1- What does .map() return?

- A new array where each element is the result of calling the function on the corresponding element from the original array.

2- If I want to loop through an array and display each value in JSX, how do I do that in React?

- by use map()

3- Each list item needs a unique __key__.

4- What is the purpose of a key?

- Keys help React identify which items have changed, are added, or are removed.

# The Spread Operator

1- What is the spread operator?

- in JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

2- List 4 things that the spread operator can do.

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments

3- Give an example of using the spread operator to combine two arrays.

```
const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
```

4- Give an example of using the spread operator to add a new item to an array.

```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```

5- Give an example of using the spread operator to combine two objects into one.

```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```

# How to Pass Functions Between Components

1- In the video, what is the first step that the developer does to pass functions between components?

- we can pass it like any other props in the child component  like :

```
fun={this.functionNmae}
```

2- In your own words, what does the increment function do?

- when any event oucrrs in the child the event call function in child component and in that funtion we call the parent function.

3- How can you pass a method from a parent component into a child component?

- in child tag we add :

```
fun={this.functionNmae}
```

4- How does the child component invoke a method that was passed to it from a parent component?

- from the props like when any event oucrrs the event call function in child component and in that funtion we call the parent function.
