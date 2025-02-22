# diegods-ferreira ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Import Helpers plugin;
- Unused Imports plugin;
- TailwindCSS plugin;
- Prettier;

## Installation

### Install the dependencies

```
npm i -D eslint @diegods-ferreira/eslint-config
```

### Create .eslintignore file

```
# .eslintignore

node_modules
```

## Usage

### React (with Next.js)

Inside `.eslintrc.json`
```
{
  "extends": [
    "@diegods-ferreira/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Inside `.eslintrc.json`
```
{
  "extends": "@diegods-ferreira/eslint-config/react"
}
```

### Node.js

Inside `.eslintrc.json`
```
{
  "extends": "@diegods-ferreira/eslint-config/node"
}
```

### NestJS

Inside `.eslintrc.json`
```
{
  "extends": "@diegods-ferreira/eslint-config/nest"
}
```
