# How to generate a Random Color in JavaScript

We can generate a random hex color making use of `Math.random()` and `padEnd()`

`const hexColor = () => "#" + Math.floor(Math.random() * 0xffffff) .toString(16) .padEnd(6, "0");`
