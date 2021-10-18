# Strict configurations for typescript projects

Usage:

1. Install package `npm install strict-configs`
2. Extend your configs:

```
{
  "extends": "strict-configs/ts/tsconfig.base.json",
  "compilerOptions": {
    "allowJs": false   // disable default extended rule
  }
}
```
