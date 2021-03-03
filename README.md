# Prettier EWM NodeJS

Installs all dependencies needed for prettier in EWM

```sh
npm i --save-dev @ewmarkets/prettier-node
```

## Edit your package.json file

```sh
# package.json
{
  ...
  "prettier": "@ewmarkets/prettier-node",
  "scripts": {
    ...
    "prettier": "prettier --write \"./**/*.{js,jsx}\""
  }
}

```
