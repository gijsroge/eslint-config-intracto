# eslint-config-intracto

## Introduction

This repository contains sample linting configs for, .js and .ts files. Currently they are all based on recommended configs, prettier and AirBnB.

## How to use

### Installing

To install this repo, run:

```bash
yarn add @intracto/eslint-config-intracto
```

And then create a file `.eslintrc.json`. Add this config if your codebase is based on VanillaJS/ES6:

```json
{
  "extends": ["@intracto/eslint-config-intracto/js"]
}
```

And this config if you are using TypeScript:

```json
{
  "extends": ["@intracto/eslint-config-intracto/ts"]
}
```
