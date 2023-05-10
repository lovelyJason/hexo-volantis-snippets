# hexo-volantis-snippets README

这是一个vscode的代码片段提示以及代码补全插件，用于hexo博客的书写，快速书写hexo标签插件和主题volantis标签插件
## Features

![](https://raw.githubusercontent.com/lovelyJason/cdn-gallery/master/gh/Snipaste_2023-05-09_21-54-50.png)

![](https://raw.githubusercontent.com/lovelyJason/cdn-gallery/master/gh/UEL2o.png)

能快速书写标签插件，避免手写各种复杂的符号，提高写文章的效率

## Requirements

本插件是为hexo博客的volantis插件定制的，并且是拓展markdown的功能，因此你需要

hexo + volantis + vscode + markdown

## Extension Settings

使用本插件之前要配置vscode以下选项，确保markdown中有代码提示和补全的功能，默认是关闭的

settings.json
```json
"[markdown]": {
    "editor.quickSuggestions": {
        "comments": "on",
        "strings": "on",
        "other": "on"
    }
}
```

如何设置？

windows下`ctrl + shift + p`换出命令面板，输入`Open User Settings`, 会打开一个JSON文件,在文件末尾追加以上内容即可


## Usage

`htag`列出所有hexo标签以供选择， `htag [tagname]`直接插入指定标签， 如`htag iframe`向文章中插入iframe
`vtag`列出所有volantis标签以供选择， `vtag [tagname]`直接插入指定标签， 如`vtag btn`向文章中插入按钮
### 0.0.1

Initial release of ...

---


