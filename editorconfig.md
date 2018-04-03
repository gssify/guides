## 前言

编辑器配置统一文件，目标是提供一致的体验

## 使用方法

首先去 [EditorConfig](http://editorconfig.org/) 下载不同编辑器下的支持插件

> 推荐使用 [VS Code 插件](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

在项目根目录增加 `.editorconfig` 文件，文件内容为：

```text
# http://editorconfig.org

root = true

[*]
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
indent_style = space
indent_size = 2

[*.{diff,md}]
trim_trailing_whitespace = false
```
