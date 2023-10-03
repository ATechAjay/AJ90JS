# What is a variable?

A variable is a container for a value, like a number we might use in a sum, or a string that we might use as part of a sentence.

```html
<button id="button_A ">Press me</button>
<h3 id="heading_A "></h3>
```

```js const buttonA = document.querySelector ("#button_A");
const headingA = document.querySelector("#heading_A");
buttonA.onclick = () => {
  const name = prompt("What is your name?");
  alert(`Hello ${name} , nice to see you!`);
  headingA.textContent = `Welcome ${name}`;
};
```

One special thing about variables is that they can contain just about anything — not just strings and numbers. Variables can also contain complex data and even entire functions to do amazing things.

> We say variables contain values. This is an important distinction to make. Variables aren't the values themselves; they are containers for values. You can think of them being like little cardboard boxes that you can store things in.

# Declaring a variable

To use a variable, you've first got to create it — more accurately, we call this declaring the variable.

To do this, we type the keyword let followed by the name you want to call your variable:

```js
let myName;
let myAge;
```

Here we're creating two variables called `myName` and `myAge`.

> In JavaScript, all code instructions should end with a semicolon ( ; ) — your code may work correctly for single lines, but probably won't when you are writing multiple lines of code together. Try to get into the habit of including it.
