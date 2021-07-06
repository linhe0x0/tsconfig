[![npm](https://img.shields.io/npm/v/@sqrtthree/tsconfig)](https://www.npmjs.com/package/@sqrtthree/tsconfig)

# tsconfig

Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html#configuration-inheritance-with-extends) for my projects.

## Install

```sh
yarn add --dev @sqrtthree/tsconfig
```

Or use npm:

```sh
npm install --save-dev @sqrtthree/tsconfig
```

## Usage

In your `tsconfig.json`:

```json
{
  "extends": "@sqrtthree/tsconfig",
  "compilerOptions": {
    "rootDir": "./src",
    "outDir": "./dist"
  },
  "include": ["src/**/*"],
  "exclude": ["node_modules"]
}
```

---

> [sqrtthree.com](http://sqrtthree.com/) &nbsp;&middot;&nbsp;
> GitHub [@sqrthree](https://github.com/sqrthree) &nbsp;&middot;&nbsp;
> Twitter [@sqrtthree](https://twitter.com/sqrtthree)
