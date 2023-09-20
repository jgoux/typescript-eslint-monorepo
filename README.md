# Getting started

```bash
pnpm install
pnpm -F api lint
```

# Output

```bash
/Users/jgoux/Documents/code/eslint-typescript-monorepo/apps/api/eslint.config.js
  3:17  error  Unsafe spread of an `any` value in an array  @typescript-eslint/no-unsafe-assignment

✖ 1 problem (1 error, 0 warnings)
```

# Config files

- [ESLint recommended config](./packages/eslint-config/src/recommended.js)
- [TypeScript config](./packages/tsconfig/tsconfig.json)