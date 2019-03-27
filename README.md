# Backoffice Base Style

## Installation and Usage

1. Just use npm install --save @bo/base-components
2. Now you can include the scripts by using following snippet:

```bash
// Load components
import '@bo/base-components';

// Load styles
import '@bo/base-components/dist/index.css';

// Run server to check the guideline
npm run dev
```

## List of components

All components are registered with the Vue global and are available for use. You do not need to re-register them.

## FAQ

### The warnings from npm install can confuse people, thinking that something has gone wrong.

1. `kleur@2.0.2` dependency warning

This issue has been fixed in [Jest 24](https://github.com/facebook/jest/issues/7430), but the `vue-cli` is still in trial [Jest 23](https://github.com/vuejs/vue-cli/blob/dev/package.json), it is estimated that this issue will be fixed in the future.

2. `CircularJSON` dependency warning

This issue has been fixed in [Eslint 5](https://github.com/eslint/eslint/issues/11052), but the `@vue/cli-plugin-eslint` is still using less than version 5, it is estimated that this issue will be fixed in the future.
