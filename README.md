```bash
$ yarn add -D eslint-react-typescript
```

### package.json

```json
...
"scripts": {
    "run:eslint": "./node_modules/eslint-react-typescript/node_modules/eslint/bin/eslint.js ./src --ext .js,.jsx",
    "run:eslint:fix": "./node_modules/eslint-react-typescript/node_modules/eslint/bin/eslint.js ./src --ext .js,.jsx --fix"
},
...
"eslintConfig": {
    "extends": "./node_modules/eslint-react-typescript/.eslintrc.js"
},
...
```