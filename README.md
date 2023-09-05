# Setup

## Visual Studio Code

### Install ESLint extension (there's no need to install Prettier as it's already included in ESLint)

Edit VS Code `settings.json`
```
{
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.addMissingImports": true
  },
}
```

### Install dependencies
```
npm i -D eslint @lzbguts/eslint-config
```

## Next.js

`.eslintrc.json`
```
{
  "extends": [
    "@lzbguts/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

## React

`.eslintrc.json`
```
{
  "extends": [
    "@lzbguts/eslint-config/react"
  ]
}
```

## Node

`.eslintrc.json`
```
{
  "extends": [
    "@lzbguts/eslint-config/node"
  ]
}
```
