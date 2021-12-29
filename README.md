# prettier-config

A common Prettier configuration to be shared among projects.

## How to Use

Install the library with `yarn add --dev @craigmiller160/prettier-config`. Then add a file called `.prettierrc.js` to the root of your project with this line in it:

```
module.exports = require('@craigmiller160/prettier-config');
```

## ESLint Integration

To integrate Prettier with ESLint, use the library [@craigmiller160/eslint-config-prettier](https://github.com/craigmiller160/eslint-config-prettier).
