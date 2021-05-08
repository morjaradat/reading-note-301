# Functional Programming Concepts

1- What is functional programming?

- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 

2- What is a pure function and how do we know if something is a pure function?

- is The first fundamental concept we learn when we want to understand functional programming .

1. It returns the same result if given the same arguments (it is also referred as deterministic)
2. It does not cause any observable side effects
3. It returns the same result if given the same arguments

3- What are the benefits of a pure function?

- The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:

```
let list = [1, 2, 3, 4, 5];

const incrementNumbers = (list) => list.map(number => number + 1);
```

4- What is immutability?

- When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

5- What is Referential transparency?

- Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
pure functions + immutable data = referential transparency

# Node JS Tutorial for Beginners #6 - Modules and require()

1- What is a module?

- is just essentially another javascript file 

2- What does the word ‘require’ do?

- its call the funcinallty from another file

3- How do we bring another module into the file the we are working in?
cosnt functionName = require('the path')

4- What do we have to do to make a module available?
module.exports = the function name;