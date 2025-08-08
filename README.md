# TypeScript Config ![NPM Version](https://img.shields.io/npm/v/%40cuiqg%2Ftypescript-config?registry_uri=https%3A%2F%2Fregistry.npmmirror.com&style=social&logo=npm&logoColor=%23CB3837&link=https%3A%2F%2Fnpmmirror.com%2Fpackage%2F%40cuiqg%2Ftypescript-config)

## Installation

1. Install package:

```sh
pnpm add --save-dev typescript @cuiqg/typescript-config
```

2. Create TypeScript configuration file `tsconfig.json` in the root of your project:

```diff json
{
+ "extends": "@cuiqg/typescript-config"
}
```

3. Add Script for `package.json`:

```diff json
{
  "scripts": {
+   "test:types": "tsc --noEmit --pretty"
  }
}
```
