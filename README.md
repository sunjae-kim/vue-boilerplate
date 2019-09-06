# Vue Boilerplate Using Webpack

Used Node.js version 12.4.0.

## Get started

### Installation

```bash
$ npm install
```

### Set Envitonment Variables

```python
# .env
NODE_ENV="test"
```

```javascript
// *.js
const nodeEnv = process.env.NODE_ENV
```

### Start

```bash
$ npm start
```

### Build

```bash
$ npm build
```

---

## Core libraries

#### `vue`
Vue core library.

#### `vue-loader`
Complies Vue components to normal Javacscript files in webpack.

#### `vue-template-compiler`
Compliles Vue 2.0 templates.

#### `webpack & webpack-cli`
To use webpack to bundle modules for the project.

#### `webpack-dev-server`
Runs development server.

#### `dotenv-webpack`
Supports `dotenv` to webpack project.

#### `@babel/core`, `@babel/preset-env`, `babel-loader`
Enables ES6 features.

Ref: https://babeljs.io/docs/en/babel-preset-env

#### `css-loader`, `style-loader`
To use CSS files for the project.

#### `html-loader`
Ref: https://zzu.li/html-loader

#### `html-webpack-plugin`
Simplifies creation of HTML files to serve webpack bundles.
