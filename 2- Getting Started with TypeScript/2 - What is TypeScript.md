# What is TypeScript ?

- TypeScript is a programming language created at microsoft to address shortcomings of JavaScript.

- Technically TypeScript is a programming language buit on top of javascript, so every javascript file is a valid typescript file.

- But typescript adds some cool features to javascript and help us build more robust and maintainable application in less time.

- The most important features typescript offers are :

  - Static Typing We have two types of programming languages
  - 1. Statically-Typed : Like C++, C#, Java, we know the type of variables at compile time while coding.

  ```
  int number = 10;
  Here we declared a variable of type integer and this variable can only hold integer values.

  number = "a";
  We cannot set it to a string or another type of objects
  ```

  - 2. Dynamically-Typed : Like JavaScript, Python, Ruby, the type of variables is dynamic so it is determind at runtime and it can also change

  ```
  let number = 10;
  Here we can declare a variable set it to a number

  number = "a";
  Later on we change it to a string. So the type is determind and it may change at runtime. It gives us lot of flexibility
  ```

- TypeScript is essentially javascript with Type Checking. In typescript we explicitly set the type of our variables upon declaration.

```
TYPESCRIPT Example :

let x: number = 10;
So if we declare a variable as a number.

x = "a";
We cannot set it to a string.

The typescript complier is going to stop us right there and this happens at compile time.
```

- TypeScript is built on top of JavaScript and we can use it where ever we use javascript.

- Drawbacks :

  - Complilation.

  - Discipline in coding.

- Transpilation : We have to pass the code to the typescript complier to compile and translate into javascript. This process is called Transpilation.
