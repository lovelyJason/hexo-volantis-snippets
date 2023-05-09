# hexo-volantis-snippets README

这是一个vscode的代码片段提示以及代码补全插件，用于hexo博客的书写，快速书写hexo标签插件和主题volantis标签插件
## Features

![](https://raw.githubusercontent.com/lovelyJason/cdn-gallery/master/gh/Snipaste_2023-05-09_21-54-50.png)

![](https://raw.githubusercontent.com/lovelyJason/cdn-gallery/master/gh/UEL2o.png)

能快速书写标签插件，避免手写各种复杂的符号，提高写文章的效率

## Requirements

本插件时为hexo博客的volantis插件定制的，并且是拓展markdown的功能，因此你需要

hexo + volantis + vscode

settings.json:
```json
"[markdown]": {
    "editor.quickSuggestions": {
        "comments": "on",
        "strings": "on",
        "other": "on"
    }
}
```
## Extension Settings

使用本插件之前要配置vscode以下选项，确保markdown中有代码提示喝补全的功能，默认是关闭的

```json
"[markdown]": {
    "editor.quickSuggestions": {
        "comments": "on",
        "strings": "on",
        "other": "on"
    }
}
```
### 0.0.1

Initial release of ...

---


