# `@lacrypta/prettier-config`

> Official La Crypta [Prettier](https://prettier.io) config.

## Usage

**Install**:

```bash
$ pnpm add -D @lacrypta/prettier-config
```

**Edit `package.json`**:

Add prettier property

```jsonc
{
  // ...
  "prettier": "@lacrypta/prettier-config",
}
```

Add format script

```jsonc
{
  // ...
  "scripts": {
    "format": "prettier --write \"**/*.{js,ts,tsx,md}\"",
  },
}
```
