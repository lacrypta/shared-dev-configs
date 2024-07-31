# Shared ESLint, Prettier & Typescript config

This is a repository of packages that allow configuration to be shared between projects.

### Install

```bash
pnpm add -D @lacrypta/prettier-config @lacrypta/eslint-config @lacrypta/typescript-config eslint-config-prettier
```

### Prettier Settings

Add to `package.json`

```json
{
  "prettier": "@lacrypta/prettier-config",
  ...
}
```

### Typescript Settings

Add to `tsconfig.json`

```json
{
  "extends": "@lacrypta/typescript-config/base.json",
  ...
}
```

### ESLint Settings

Add to `.eslintrc.js`

```js
module.exports = {
  extends: ["@lacrypta/eslint-config/library.js"],
  ...
};
```

## What's inside?

This Turborepo includes the following packages/apps:

### Packages

- `@lacrypta/prettier`: `Prettier` configurations
- `@lacrypta/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@lacrypta/typescript-config`: `tsconfig.json`s used throughout the monorepo
