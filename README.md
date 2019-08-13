# @vbelolapotkov/js-config

Shareable set of configs for JavaScript tools.

## Installation

```bash
npm i -D @vbelolapotkov/js-config
```

## Usage

Feel free to use all or only required configs.

### ESLint

Create `.eslintrc.js` in your project root:

```js
module.exports = {
  extends: '@vbelolapotkov/js-config/eslint',
}
```

### Prettier

Create `prettier.config.js` in your project root:

```js
module.exports = require('@vbelolapotkov/js-config/prettier')
```
