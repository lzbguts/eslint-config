# lzbguts ESLint config

## Setup

### Install dependencies
```
npm i -D eslint @lzbguts/eslint-config
```

### Next.js

<<<<<<< HEAD
=======
Install dependencies:
```
npm i -D eslint @lzbguts/eslint-config
```
>>>>>>> 9297a5cd4d8499ad53436c64c19c7c1cac822a2e
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
