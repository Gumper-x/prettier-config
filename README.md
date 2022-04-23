# @gumper-x/prettier-config

That basic prettier config for all JS/TS projects 

### [NPM](https://www.npmjs.com/package/@gumper-x/prettier-config)

```bash
npm i @gumper-x/prettier-config
```
Use in `package.json`
```json
"prettier": "@gumper-x/prettier-config",
```
### OR
Use in `.prettierrc.js`
```json
module.exports = {
  ...require("@gumper-x/prettier-config"),
  // Your rules https://prettier.io/docs/en/options.html
};
```