# tsconfig

Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html#configuration-inheritance-with-extends) for my projects.

## Install

```sh
$ yar add --dev @sqrtthree/tsconfig

# Or use npm:
$ npm install --save-dev @sqrtthree/tsconfig
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
  "exclude": ["node_modules", "**/*.spec.ts"]
}
```
