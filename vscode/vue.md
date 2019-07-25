> (Windows / Linux: File -> Preferences -> User Settings) open the vscode file settings.json.


### 插件集合：
[VSCode拓展推荐（前端开发）](https://github.com/varHarrie/varharrie.github.io/issues/10)



> Extension
> [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
```
{
  // vetur:对html的内容使用js-beautify-html
  "vetur.format.defaultFormatter.html": "js-beautify-html",
}
```

> Doc
> [vetur-Doc](https://vuejs.github.io/vetur/)



> Extension
> [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

```
"files.autoSave":"off",
"eslint.validate": [
   "javascript",
   "javascriptreact",
   "html",
   { "language": "vue", "autoFix": true }
 ],
 "eslint.options": {
    "plugins": ["html"]
 }
 ```
