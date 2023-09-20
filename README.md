# Getting started

```bash
pnpm install
pnpm -F api lint
```

# Output

```bash
/Users/jgoux/Documents/code/eslint-typescript-monorepo/apps/api/eslint.config.js
  3:17  error  Unsafe spread of an `any` value in an array  @typescript-eslint/no-unsafe-assignment

/Users/jgoux/Documents/code/eslint-typescript-monorepo/apps/api/src/index.ts
  5:13  error  Unsafe spread of an `any` array type  @typescript-eslint/no-unsafe-argument

✖ 2 problems (2 errors, 0 warnings)
```

# Config files

- [ESLint recommended config](./packages/eslint-config/src/recommended.js)
- [TypeScript config](./packages/tsconfig/tsconfig.json)