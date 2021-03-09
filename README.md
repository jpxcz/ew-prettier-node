# Prettier EWM NodeJS

Adds the Prettier and ESLINT format that we use.
If `husky` is added, then it will run on every new commit

```sh
npm i --save-dev @ewmarkets/prettier-node
```

## Edit your package.json file

```sh
# package.json
{
  ...
  "prettier": "@ewmarkets/prettier-node",
  # to run it manually
  "scripts": {
    ...
    "prettier": "prettier --write \"./**/*.{js,jsx}\""
  }
  # to run on new commit
  "husky": {
    "hooks":{
      "pre-commit": "pretty-quick --staged"
    }
  }
}

```
