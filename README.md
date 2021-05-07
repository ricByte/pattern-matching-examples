# PATTERN MATCHING in TS

A series of pattern matching examples in Typescript

## Background

TL;DR

story

## Project Structure

```shell

├── LICENSE.md
├── README.md
├── __tests__
│   ├── index.spec.ts
│   └── PatternMatchingClassWithAdt.spec.ts
├── huskyrc.json
├── jest.config.js
├── package-lock.json
├── package.json
├── src
│   ├── PatternMatchingClassWithAdt.ts
│   └── index.ts
├── tsconfig.json
├── tsconfig.lint.json
└── tslint.json


```

## Usage

### Build

```
yarn build
```

Outputed into `lib/`.

### Test

```
yarn test
```

### Coverage

```
yarn coverage
```

Open `coverage/lcov-report/index.html` in a browser.

## Dependencies
### TypeScript

`yarn build` transpiles the source codes from `src/` to `lib/`.

See `tsconfig.json`.

### husky & lint-staged

husky provides hooks for git, e.g. pre-commit, pre-push.

lint-staged gives the git staging files to any command.

You can format and lint the source codes with them before they are commited.

See `package.json` and `.lintstagedrc.json`.

### Jest(ts-jest)

Jest is a test runner.

ts-jest let Jest run `.ts` files.

### Contributors

Riccardo Vecchi(reackonly)

### Licence

These examples are licensed under the [MIT License](LICENSE.md).
