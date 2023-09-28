# CLASS 8

### ¿What’s the difference between using let and var in JavaScript??
The keywords **let** and **var** both declare new variables in JavaScript. The difference between **let** and **var** is in the scope of the variables they create:
- Variables declared by **let** are only available inside the block where they’re defined.
- Variables declared by **var** are available throughout the function in which they’re declared.

A **var** variable will be available thoroughout the function body in which it is defined, no matter how deeply nested its definition. A **let** variable will only be available within the same block where it is defined.
The behavior of **var** can be useful in some cases, but is quite different from other programming languages, and can cause difficult-to-resolve bugs. The more recently introduced **let** keyword allows for more precise and predictable variable scoping, and allows programmers to safely reuse names for temporary variables within the same function.
One final point to note is that when working outside of function bodies, at a global level, **let** does not create a property on the global object, whereas **var** does.
[More info](https://sentry.io/answers/difference-between-let-and-var-in-javascript/)

### Retro Flowchart

[Retro](RETRO.png)
