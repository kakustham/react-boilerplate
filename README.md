Bolierplate for React projects
==============================

An simple isomorphic boilerplate for React projects, running on Node 5.

## Features

* Transpiling ES201x and JSX via [Babel](https://babeljs.io)
* Type checking with [Flow](http://flowtype.org/)
* Linting with [ESLint](http://eslint.org/)
* Server rendering and Hot reloading for React Components with a [Koa](http://koajs.com/) server
* Inline styles support with [Radium](http://stack.formidable.com/radium/)
* Testing React Components with [Jest](https://facebook.github.io/jest/)
* [Redux](http://redux.js.org/) with [Redux Dev Tools](https://github.com/gaearon/redux-devtools)

## Usage

Set `NODE_ENV` to `production` to run the server and build files in production mode.

* `npm start` - Start the server (with hot reload in development mode)
* `npm test` - Run tests with Jest
* `npm run lint` - Lint files with ESLint
* `npm run flow` - Typecheck files with Flow
* `npm run build` - Build the JavaScript bundle
* `npm run clean` - Cleanup build directories

Check the `scripts` section in `package.json` for more details.
