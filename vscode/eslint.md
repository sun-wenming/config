> (Windows / Linux: File -> Preferences -> User Settings) open the vscode file settings.json.

```
{
  "eslint.validate": ["javascript", "javascriptreact", "html", { "language": "vue", "autoFix": true }],
  "eslint.options": {
    "plugins": ["html"]
  },
}
```

> Extension
> [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
