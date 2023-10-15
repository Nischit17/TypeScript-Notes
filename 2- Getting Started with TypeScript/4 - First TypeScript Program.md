# First TypeScript Program

- For our project we have to add a new file called index.ts

```
index.ts

So every typescript file should have the ts as extention
```

- So we know typescript is built on top of javascript. TypeScript is a superset of javascript which means it has everything in javascript + some additional features.

- So here we can write any javascript code and that is valid typescript code.

```
So we can write

console.log("Hello World!")

- Go to the terminal window.

- tsc index.ts using this we are compiling the typescript file.

tsc - typescript compiler
```

- If we open our project folder we have 2 files index.js and index.ts. index.js is a result of compilation we can see the exact code here.

- Let's now write a bit of typescript code

```
let age: number = 20;

we are now declaring a variable using the let keyword and we call it as age and `annotate` it with a number.

So by typing a colon(:) followed by the variable we can annotate a variable.

Later we initialized it to 20;
```

- Now we declared age as a number we cannot set it to a string or another type of object.

```
let age: number = 20;
age= "twenty"; // This will throw an error because you cant assign different types in one line like above.

Error: Type 'string' is not assignable to type 'number'.
```

- This is the beauty of typescript, here we can catch lots of our mistakes at compile time.

- Now if we remove and recompile the file, so back to out terminal

```
let age: number = 20;

tsc index.ts

var age = 20; - This is javascript code that the typescript compiler generated. So instead of the let keyword here we have var because by default the typescript compiler uses an older version of javascript which is ES5.

ES - is a standard or a specification while javascript is an implementation of that specification.
```
