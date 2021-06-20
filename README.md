Babel Learning
=====

A quick lesson in using Babel to transpile languages back to more compatible ones, or to another one entirely.

What it does
----

The babelrc file will hold the version of the language you need to transpile back. So, ES6(+) most definitely. ["env"] instructs Babel to transpile any code from versions ES6 and later.

The Build script:
babel — The Babel command call responsible for transpiling code.
src — Instructs Babel to transpile all JavaScript code inside the src directory.
-d — Instructs Babel to write the transpiled code to a directory.
lib — Babel writes the transpiled code to a directory called lib.

The **npm run build** command will transpile all JavaScript files inside of the src folder.

Languages
---
Javascript
