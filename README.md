# ca-browser-compatibility-transpilation
## ca-set-up-browser-compatitiblity-tranaspilation-npm-scripts

https://caniuse.com/?search=Template%20Literals
file:///C:/Program%20Files/nodejs/node_modules/npm/docs/public/cli-commands/npm-install/index.html
https://www.npmjs.com/?track=newUserCreated

browser compatibility and transpilation. Let’s review the key concepts:

ES5 — The old JavaScript version that is supported by all modern web browsers.
ES6 — The new(er) JavaScript version that is not supported by all modern web browsers. The syntax is more readable, similar to other programming languages, and addresses the source of common bugs in ES5.
caniuse.com — a website you can use to look up HTML, CSS, and JavaScript browser compatibility information.
Babel — A JavaScript package that transpiles JavaScript ES6+ code to ES5.
npm init — A terminal command that creates a package.json file.
package.json — A file that contains information about a JavaScript project.
npm install — A command that installs Node packages.
babel-cli — A Node package that contains command line tools for Babel.
babel-preset-env — A Node package that contains ES6+ to ES5 syntax mapping information.
.babelrc — A file that specifies the version of the JavaScript source code.
"build" script — A package.json script that you use to tranpsile ES6+ code to ES5.
npm run build — A command that runs the build script and transpiles ES6+ code to ES5.

### For future reference, here is a list of the steps needed to set up a project for transpilation:

>Initialize your project using npm init and create a directory called src
>Install babel dependencies by running
>npm install babel-cli -D
>npm install babel-preset-env -D
>Create a .babelrc file inside your project and add the following code inside it:
>{
>  "presets": ["env"]
>}
>Add the following script to your scripts object in package.json:
>"build": "babel src -d lib"
>Run npm run build whenever you want to transpile your code from your src to lib directories.

Instructions
If you want some more practice, take a moment to add JavaScript files and ES6 syntax to the src folder and try transpiling them.

Once you feel comfortable with this process, try setting up Babel on your own computer.

Concept Review
Want to quickly review some of the concepts you’ve been learning? Take a look at this material's cheatsheet!
Community Forums
Still have questions? View this exercise's thread in the Codecademy Forums.
Code Editor
12345678
var pasta = "Spaghetti"; // ES5 syntax

const meat = "Pancetta"; // ES6 syntax

let sauce = "Eggs and cheese"; // ES6 syntax

// Template literals, like the 
Terminal


