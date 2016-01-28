# webpack-config-tap

Inspect your webpack config without changing it.

![build status](http://img.shields.io/travis/webpack-config/webpack-config-tap/master.svg?style=flat)
![coverage](http://img.shields.io/coveralls/webpack-config/webpack-config-tap/master.svg?style=flat)
![license](http://img.shields.io/npm/l/webpack-config-tap.svg?style=flat)
![version](http://img.shields.io/npm/v/webpack-config-tap.svg?style=flat)
![downloads](http://img.shields.io/npm/dm/webpack-config-tap.svg?style=flat)

## Usage

Install:

```sh
npm install --save webpack-config-tap
```

Add to your `webpack.config.babel.js`:

```javascript
import tap from `webpack-config-tap`;

tap(config => console.log(config))({
  /* existing webpack configuration */
})
```

[webpack]: https://webpack.github.io
