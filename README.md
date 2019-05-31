# tape-webpack-boilerplate

A project containing a sample setup of tape for unit testing and bundling with webpack.

## Install

```text
npm install
```

## Package Scripts

### Build

```text
npm run build
```

Will create a  `*.umd.js` file in the the `./dist` directory.

### Tests

Note that `@babel/register` is used on the code before it goes to `tape` in order to facilitate the use of es6 imports with node.

```text
npm run test
```

## Resources

* <https://webpack.js.org/>