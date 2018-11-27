> (Windows / Linux: File -> Preferences -> User Settings) open the vscode file settings.json.

```
{
  // start golang
  "go.goroot": "D:\\Go", // 根据实际的路径
  "go.gopath": "D:\\godemo",
  "editor.formatOnSave": true,
  "go.formatTool": "gofmt",
  "go.inferGopath": true,  // 自己的包或者第三方库 出现代码提示(无法通过 lint 检查，则不会执行自动 import)
  "go.autocompleteUnimportedPackages": true, // 自动完成未导入的包。
  "go.gotoSymbol.includeImports": true,
  "go.useCodeSnippetsOnFunctionSuggest": true,
  "go.useCodeSnippetsOnFunctionSuggestWithoutType": true,
  "go.docsTool": "gogetdoc", // 如果引用的包使用了 ( . "aa.com/text") 那这个text包下的函数也无法跳转进去
  // end golang
}
```

> Extension
> [Go](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Go)
