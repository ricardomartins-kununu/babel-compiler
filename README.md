# babel-compiler
Compile code using babel

# installation

- clone the repo
- install dependencies by running `npm install`
- add the code you need to convert into `src/indes.js`
- run `npm start` on the console
- the output should be stored into `dist/indes.js`

# Example (convert es6 -> es5):

### code to covert placed into `src/index.js`

```javascript

const testFunction = (arg)=> arg
console.log(testFunction)

```

### coverted code placed into `dist/index.js`

```javascript
"use strict";
var testFunction = function testFunction(arg) {
  return arg;
};
console.log(testFunction);

```
