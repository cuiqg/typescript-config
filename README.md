# TypeScript Config

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
