# lzbguts ESLint config

## Setup

### Install dependencies
```
npm i -D eslint @lzbguts/eslint-config
```

### Next.js

`.eslintrc.json`
```
{
  "extends": [
    "@lzbguts/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React

`.eslintrc.json`
```
{
  "extends": [
    "@lzbguts/eslint-config/react"
  ]
}
```

### Node

`.eslintrc.json`
```
{
  "extends": [
    "@lzbguts/eslint-config/node"
  ]
}
```
