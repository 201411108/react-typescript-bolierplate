# react-typescript-bolierplate

> React with typescript bolierplate based on `create-react-app`<br>
> `Eslint` and `Prettier` are set by [201411108](https://github.com/201411108)

## Installation
1. folk or clone this repository
2. ```npm install``` or ```yarn```
3. download packages you needed
   1. You can see installed packages in `package.json`
   2. If you want to change or delete the rules, please change `.eslintrc.json` and `.prettierrc`

## Eslint
### extends
```json
"extends": [
    "airbnb",
    "plugin:react/recommended",
    "plugin:jsx-a11y/recommended",
    "plugin:import/errors",
    "plugin:import/warnings",
    "plugin:@typescript-eslint/recommended",
    "plugin:prettier/recommended"
]
```

### Rules
```json
"rules": {
    "import/prefer-default-export": 0,
    "prettier/prettier": 0,
    "import/extensions": 0,
    "no-use-before-define" : 0,
    "guard-for-in": 0,
    "no-restricted-syntax": 0,
    "import/no-unresolved": 0,
    // "import/no-extraneous-dependencies": 0,
    "react/prop-types" : 0,
    "react/jsx-filename-extension": [
        2,
        { "extensions": [".js", ".jsx", ".ts", "tsx"] }
    ],
    "react/require-default-props": 0,
    "jsx-a11y/no-static-element-interactions": 0,
    "jsx-a11y/click-events-have-key-events": 0,
    "jsx-a11y/no-noninteractive-element-interactions": 0,
    "@typescript-eslint/explicit-module-boundary-types": 0
    // "@typescript-eslint/no-explicit-any": 0,
    // "@typescript-eslint/no-unused-vars": 0
}
```
* This is settings that I used. You can freely change this.

## Prettier
```json
{
    "singleQuote": true,
    "jsxSingleQuote": true,
    "bracketSpacing": true
}

```