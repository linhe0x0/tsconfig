[![npm](https://img.shields.io/npm/v/@sqrtthree/tsconfig)](https://www.npmjs.com/package/@sqrtthree/tsconfig)

# tsconfig

Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html#configuration-inheritance-with-extends) for my projects. The configuration is now distributed to be compatible with [TypeScript 5.0](https://devblogs.microsoft.com/typescript/announcing-typescript-5-0/) or newer.

## Install

```sh
yarn add --dev @sqrtthree/tsconfig
```

Or use npm:

```sh
npm install --save-dev @sqrtthree/tsconfig
```

## Usage

For example in your `tsconfig.json`:

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
