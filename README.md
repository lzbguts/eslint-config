# lzbguts ESLint config

## Setup

### Next.js

Install dependencies:
```
npm i -D eslint @lzbguts/eslint-config
```
`.eslintrc.json`
```
{
  "extends": [
    "@lzbguts/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```
