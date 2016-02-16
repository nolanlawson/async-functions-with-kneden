async-functions-with-kneden
====

A "hello world" showing how to use `async`/`await` (async functions) with [Babel](http://babeljs.io/)
and [Kneden](https://github.com/marten-de-vries/kneden). Note in particular the
`.babelrc` file.

Usage
---

Download the code, then run

    npm install
    npm start

It should print:

    hello world

Browser version
----

To run in a browser, run:

    npm run browser

This will build `index.js` using Browserify/Babelify and then open it in a browser, so you can verify that it works.

To see the built version, run:

    npm run build

This will create a `bundle.js` you can inspect. By my measurements, the total size after uglify+gzip is 380 bytes.
