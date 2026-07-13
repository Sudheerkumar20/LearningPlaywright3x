# JavaScript Keywords

**Keywords** are reserved words in JavaScript that have a special meaning to the language. They cannot be used as variable names, function names, or any other identifiers in your code.

## Complete List of JavaScript Keywords

| Keyword | Category | Description |
|---------|----------|-------------|
| `break` | Control Flow | Terminates the current loop or switch statement |
| `case` | Control Flow | Marks a branch in a switch statement |
| `catch` | Control Flow | Catches an exception thrown in a try block |
| `continue` | Control Flow | Skips to the next iteration of a loop |
| `default` | Control Flow | Specifies the default branch in a switch statement |
| `do` | Control Flow | Creates a do...while loop (executes at least once) |
| `else` | Control Flow | Specifies an alternative block in an if statement |
| `finally` | Control Flow | Executes a block after try and catch, regardless of result |
| `for` | Control Flow | Creates a loop with an optional initialization, condition, and increment |
| `if` | Control Flow | Executes a block conditionally |
| `return` | Control Flow | Exits a function and optionally returns a value |
| `switch` | Control Flow | Evaluates an expression and matches it to case clauses |
| `throw` | Control Flow | Throws a user-defined exception |
| `try` | Control Flow | Defines a block to test for errors |
| `while` | Control Flow | Creates a loop that executes as long as a condition is true |
| `var` | Variable | Declares a function-scoped or globally-scoped variable |
| `let` | Variable | Declares a block-scoped local variable (ES6) |
| `const` | Variable | Declares a block-scoped read-only constant (ES6) |
| `function` | Function | Declares a function |
| `class` | Function | Declares a class (ES6) |
| `extends` | Function | Extends a class or creates a subclass |
| `super` | Function | Refers to the parent class (used to call parent constructor/methods) |
| `get` | Function | Binds an object property to a getter function |
| `set` | Function | Binds an object property to a setter function |
| `static` | Function | Defines a static method or property for a class |
| `new` | Object | Creates an instance of a user-defined object type |
| `this` | Object | Refers to the current execution context object |
| `delete` | Object | Deletes a property from an object |
| `in` | Object | Returns true if a property exists in an object |
| `instanceof` | Object | Checks if an object is an instance of a constructor |
| `of` | Object | Used with for...of to iterate over iterable values |
| `typeof` | Object | Returns a string describing the type of a value |
| `void` | Object | Evaluates an expression and returns undefined |
| `async` | Async | Declares an asynchronous function (ES8) |
| `await` | Async | Pauses execution until a Promise is settled (ES8) |
| `yield` | Async | Pauses and resumes a generator function |
| `import` | Module | Imports bindings from an external module (ES6) |
| `export` | Module | Exports bindings from a module (ES6) |
| `from` | Module | Specifies the module path in import statements |
| `as` | Module | Renames an imported or exported binding |
| `debugger` | Debugging | Invokes any available debugging functionality |
| `null` | Literal | Represents the intentional absence of any object value |
| `true` | Literal | Represents a boolean true value |
| `false` | Literal | Represents a boolean false value |

## Reserved for Future Use

These keywords are reserved for potential future use in JavaScript (mostly in strict mode):

| Keyword | Notes |
|---------|-------|
| `enum` | Reserved for all contexts |
| `implements` | Reserved in strict mode |
| `interface` | Reserved in strict mode |
| `package` | Reserved in strict mode |
| `private` | Reserved in strict mode |
| `protected` | Reserved in strict mode |
| `public` | Reserved in strict mode |

## Key Points

- **Keywords cannot be used as identifiers** (variable names, function names, etc.)
- Some keywords (like `let`, `static`, `yield`) have restrictions — they're only fully reserved in strict mode or certain contexts
- `NaN`, `Infinity`, and `undefined` are **not keywords** — they are global properties (but you shouldn't use them as variable names either)
- New keywords are occasionally added with newer ECMAScript versions (last major addition: `async`/`await` in ES8/2017)
