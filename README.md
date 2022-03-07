# ESLint (and Prettier) config

These are settings for ESLint and Prettier used by Pocket.

## What it does

This setup lints your Typescript code based on best practices. Check the [.eslintrc.js](https://github.com/Pocket/eslint-config/blob/main/.eslintrc.js) file to see what is included. Feel free to override the rules that make sense for you.

## Installing

1. In your project folder, run:

```
npm i -D @pocket-tools/eslint-config # or yarn install --dev @pocket-tools/eslint-config 
npx install-peerdeps --dev @pocket-tools/eslint-config
```

2. You will see several dependencies were installed. Now, create (or update) a `.eslintrc` file with the following content:

```js
{
  'extends': '@pocket-tools/eslint-config'
}
```

3. Copy the [.prettierrc](https://github.com/Pocket/eslint-config/blob/main/.prettierrc) file from this repository into your project folder

---

This repository is inspired by [eslint-config-wesbos](https://github.com/wesbos/eslint-config-wesbos).
