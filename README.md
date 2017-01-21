# babel-preset-es2015-ie-native-modules

> Babel preset for all es2015 plugins that works with IE>=9, without commonjs transform to enable tree shaking

## Install

```sh
$ npm install --save-dev babel-preset-es2015-ie-native-modules
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-ie-native-modules"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-ie-native-modules
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-ie-native-modules"]
});
```
