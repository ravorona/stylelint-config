# Stylelint configuration
Stylesheet style guide using [Stylelint](https://stylelint.io)

## Install
Yarn:
```bash
yarn add -D \
    @ravorona/stylelint-config
    stylelint
```
NPM:
```bash
npm i --save-dev \
    @ravorona/stylelint-config
    stylelint
```

## Usage
Set extends property inside your [Stylelint configuration](https://stylelint.io/user-guide/configure)
```json
{
    "extends": "@ravorona/stylelint",
    "rules": {}
}
```