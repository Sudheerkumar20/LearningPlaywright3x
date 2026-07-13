# JavaScript Keywords

**Keywords** are reserved words in JavaScript that have a special meaning to the language. They **cannot** be used as variable names, function names, or identifiers.

---

## Comparison by Category

### Variable Declaration — `var` vs `let` vs `const`

| Keyword | Scope | Re-declarable? | Re-assignable? | Hoisted? | Temporal Dead Zone? |
|---------|-------|---------------|---------------|---------|--------------------|
| `var`  | Function | ✅ Yes | ✅ Yes | ✅ Yes (initialized as `undefined`) | ❌ No |
| `let`  | Block | ❌ No | ✅ Yes | ✅ Yes (not initialized) | ✅ Yes |
| `const` | Block | ❌ No | ❌ No (must assign at declaration) | ✅ Yes (not initialized) | ✅ Yes |

### Loops — `for` vs `while` vs `do...while`

| Keyword | Executes at least once? | Use case |
|---------|------------------------|----------|
| `for` | ❌ No | When you know the number of iterations |
| `while` | ❌ No | When condition is checked before each iteration |
| `do` | ✅ Yes | When the block must run at least once before condition check |
| `for...in` | ❌ No | Iterates over **enumerable property keys** of an object |
| `for...of` | ❌ No | Iterates over **iterable values** (arrays, strings, maps, etc.) |

### Conditionals — `if...else` vs `switch`

| Keyword | Evaluates | Use case |
|---------|-----------|----------|
| `if` | Boolean expressions | Simple true/false conditions, range checks |
| `else` | Paired with `if` | Fallback when `if` is false |
| `switch` | Single expression matched against cases | Multiple discrete values for the same expression |
| `case` | Specific value inside `switch` | One branch per possible value |
| `default` | Fallback inside `switch` | When no `case` matches |

### Error Handling — `try...catch...finally`

| Keyword | Purpose |
|---------|---------|
| `try` | Wraps code that might throw an error |
| `catch` | Handles the error if one occurs |
| `finally` | Always runs after `try`/`catch` (for cleanup) |
| `throw` | Manually creates/custom error |

### Functions & Classes

| Keyword | Purpose |
|---------|---------|
| `function` | Declares a regular function |
| `class` | Declares a class (syntactic sugar over prototypes) |
| `extends` | Makes one class inherit from another |
| `super` | Calls parent class constructor or methods |
| `get` | Defines a getter property |
| `set` | Defines a setter property |
| `static` | Defines a static method/property (called on class, not instances) |
| `return` | Exits a function and optionally returns a value |
| `new` | Creates an instance of a constructor/class |

### Async Programming — `async` vs `await` vs `yield`

| Keyword | Purpose | Works with |
|---------|---------|-----------|
| `async` | Declares a function that returns a Promise | `await` inside the function |
| `await` | Pauses execution until a Promise settles | Inside `async` functions only |
| `yield` | Pauses and resumes a generator function | Inside `function*` generator functions |

### Object Operations

| Keyword | What it does |
|---------|-------------|
| `this` | Reference to the current execution context (object) |
| `delete` | Removes a property from an object |
| `in` | Checks if a property exists in an object (`"key" in obj`) |
| `instanceof` | Checks if an object is an instance of a class/constructor |
| `typeof` | Returns the data type as a string |
| `void` | Evaluates an expression and returns `undefined` |

### Module System — `import` / `export`

| Keyword | Purpose |
|---------|---------|
| `import` | Brings bindings from another module into scope |
| `export` | Exposes bindings (variables, functions, classes) from a module |
| `from` | Specifies the module path in an `import` statement |
| `as` | Renames a binding during import/export |

### Special Values / Literals

| Keyword | Type | Meaning |
|---------|------|---------|
| `null` | Null | Intentional absence of an object value |
| `true` | Boolean | Logical true |
| `false` | Boolean | Logical false |

### Others

| Keyword | Purpose |
|---------|---------|
| `break` | Exits a loop or `switch` statement immediately |
| `continue` | Skips the rest of the current loop iteration and moves to the next |
| `debugger` | Invokes the debugger (breakpoint) if one is available |
| `with` | Extends the scope chain (deprecated, avoid in strict mode) |

---

## Future Reserved Keywords

These are reserved for potential future use and **cannot** be used as identifiers in strict mode:

| Keyword | Restriction |
|---------|------------|
| `enum` | Always reserved |
| `implements` | Strict mode only |
| `interface` | Strict mode only |
| `package` | Strict mode only |
| `private` | Strict mode only |
| `protected` | Strict mode only |
| `public` | Strict mode only |

---

## Quick Summary

| Feature | Keywords |
|---------|----------|
| **Variables** | `var`, `let`, `const` |
| **Functions/Classes** | `function`, `class`, `extends`, `super`, `get`, `set`, `static` |
| **Flow Control** | `if`, `else`, `switch`, `case`, `default`, `for`, `while`, `do`, `break`, `continue`, `return` |
| **Error Handling** | `try`, `catch`, `finally`, `throw` |
| **Object** | `this`, `new`, `delete`, `in`, `instanceof`, `typeof`, `void`, `with` |
| **Async** | `async`, `await`, `yield` |
| **Modules** | `import`, `export`, `from`, `as` |
| **Literals** | `null`, `true`, `false` |
| **Debug** | `debugger` |

> **Note:** `NaN`, `Infinity`, and `undefined` are **not** keywords — they are global properties. Still, avoid using them as variable names to prevent confusion.
