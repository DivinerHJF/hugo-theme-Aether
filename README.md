Aether Hugo Theme
========================

- [Example Site](https://Aether.netlify.app)

该主题为 [LeaveIt](https://github.com/liuzc/leaveit) 的魔改版，仅作私人使用。 

## 功能

- **黑暗模式**
1. 根據 PC 或手機的系統設置自動切換；
2. 點擊網站左上角“❤”手動切換。

- **評論系統**

内置 Valine、Disqus、chanyan、gittalk 等評論系統，具體在 `config.toml` 文件中需要添加的參數可以參考 `theme/layouts/partials/comments.html`。

- **代码块设置**

代码块无高亮设置，不推荐在文章中写太多代码，个人习惯于在 RMarkdown、Jupyter Notebook 等专业工具中敲代码，让博客文章回归文字！
## 使用本主题

- **安装**

    ``` bash
    $ git submodule add https://github.com/DivinerHJF/hugo-theme-divine.git themes/divine
    ```

- **开启**

将 `theme = "divine"` 加入到 `config.toml` 中。

- **更新**

    ``` bash
    git submodule update --recursive --remote
    ```
