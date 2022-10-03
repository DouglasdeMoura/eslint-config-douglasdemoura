# My custom ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;
- Vitest integration.

## Setup

1. Install the dependencies

```
npm i -D eslint @douglasdemoura/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:

```
{
  "extends": "@douglasdemoura/eslint-config/react"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
