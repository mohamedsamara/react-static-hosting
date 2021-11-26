# React Static Hosting

## CRA Setup

```
npx create-react-app my-app --template typescript
```

## Husky Setup

```
yarn prepare
```

```
npx husky add .husky/pre-commit 'yarn lint && yarn test --watchAll=false'
```

```
npx husky add .husky/commit-msg 'npx --no-install commitlint --edit $1'
```

## ESlint Setup

```
npx eslint --init
```

```
"lint": "eslint \"**/*.{ts,tsx,js,jsx}\"",
```
