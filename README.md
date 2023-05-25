# Interview Cheat Sheet
Ok, not a chear sheet per se.. more of a reminder of definitions.

## Javascript

### 7 primitive data types: 

string, number, bigint, boolean, undefined, symbol, and null

### Map vs Reduce:

Map - Using map you iterate the elements, and for each element you return an element you want.

Reduce - Using an array as an input, you can get one single element

### The difference between `==` and `===` :

- `==` converts the variable values to the same type before performing comparison. This is called type coercion.
- `===` does not do any type conversion (coercion) and returns true only if both values and types are identical for the two variables being compared.

### Asynchronous JavaScript:

Asynchronous code allows the program to be executed immediately where the synchronous code will block further execution of the remaining code until it finishes the current one

### Reference Types

- objects
- arrays
- functions

Mutable can be changed or added to where immutable means something that cannot be changed or added. Primitive values in JavaScript cannot have anything added upon to them, they can only be re-assigned, and hence all primitive values in JavaScript are immutable.

Hooks are functions that let you “hook into” React state and lifecycle features from function components.

### Closure:

The combination of a function bundled together (enclosed) with references to its surrounding state

### Promises

A promise in JavaScript is an object that represents the eventual completion (or failure) of an asynchronous operation, and its resulting value. Asynchronous operations are operations that take some time to complete, such as making a network request or reading from a file.

Promises are used to handle asynchronous operations in a way that is both predictable and easy to understand. When an asynchronous operation is started, it returns a promise. The promise then represents the state of the operation: it can be pending, fulfilled, or rejected.

When the asynchronous operation completes successfully, the promise is fulfilled with the result of the operation. When the asynchronous operation fails, the promise is rejected with the error that occurred.

Promises can be chained together to create complex asynchronous workflows. For example, you could use promises to make a network request, parse the response, and then display the results on the screen.

## Typescript
### Enum

In JavaScript, an enum is a data type that represents a set of named constants. Enums are useful for representing values that are known at compile time, such as the days of the week or the months of the year.

### Inferred Types
In JavaScript, inferred types are types that are automatically assigned to variables and expressions based on their values. For example, if you assign a string to a variable, the variable will be inferred to be of type `string`.

Inferred types can be useful for making code more readable and maintainable. They can also help to prevent errors by ensuring that variables are only used with values of the correct type.

### Pros of TypeScript

- Static typing: Static typing helps to prevent errors at compile time, which can save time and frustration during development.
- Better code organization: TypeScript's type system can help to improve the organization of code by making it easier to understand the relationships between different parts of the codebase.
- Enhanced IntelliSense: TypeScript's type system can also be used to provide enhanced IntelliSense in IDEs, which can make it easier to write code and avoid errors.
- Interoperability with JavaScript: TypeScript is a superset of JavaScript, which means that any JavaScript code can also be used in TypeScript. This makes it easy to migrate existing JavaScript code to TypeScript.

### Cons of TypeScript

- Learning curve: TypeScript adds a layer of complexity to JavaScript, which can make it more difficult to learn.
- Bloated code: TypeScript code can be larger than JavaScript code due to the additional type annotations.
- Not widely adopted: TypeScript is not as widely adopted as JavaScript, which can make it more difficult to find developers who are familiar with the language.


## GraphQL
### Pros of GraphQL

- Flexibility: GraphQL allows clients to request exactly the data they need, which can improve performance and reduce bandwidth usage.
- Scalability: GraphQL can be used to scale APIs to meet the needs of large and complex applications.
- Efficiency: GraphQL can be used to reduce the number of API calls, which can improve performance and reduce latency.
- Reusability: GraphQL queries can be reused, which can save time and effort.
- Developer productivity: GraphQL can make it easier for developers to build applications, as they do not need to worry about overfetching or underfetching data.

### Cons of GraphQL

- Complexity: GraphQL can be more complex to learn and implement than traditional REST APIs.
- Not widely adopted: GraphQL is not as widely adopted as REST APIs, which can make it more difficult to find developers who are familiar with the language.
- Security: GraphQL can be less secure than traditional REST APIs if not implemented properly.
