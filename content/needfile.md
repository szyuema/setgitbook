# GitBook 想关文件配置

## 1.README.md
>典型的, 它应该是你的图书的介绍. 它可以自动的被加到最终的summary中.

## 2.SUMMARY.md
>SUMMARY.md 定义了你的图书的结构. 它应该包含章节的列表,以及它们的链接.


```bash
# Summary
* [基础环境](base.md)
  * [Node安装](node.md)
  * [GitBook安装](gitbook.md)
* [GitBook配置](gitbook-config.md)
  * [相关文件](needfile.md)
  * [制作pdf](topdf.md)
  * [总结-常用命令](topdf.md)

```

## 3.GLOSSARY.md
> GLOSSARY.md 允许你列出条目以及它们的定义. 基于这些条目 gitbook会自动创建一个索引，并在页面中加亮这些条目.

格式

```bash
# 关键字
关键字描述
```
## 4.book.json
> 文件加载默认的配置，前提是此文件存在.

格式

```json

{
    "title": "文章标题",
    "description": "描述 ",
    "language": "语言",
    "plugins": [
        //需要的配置 gitbook install 安装
        "github",
        "editlink",
    ],
    "pluginsConfig": {
    //详细配置
        "github": {
            "url": ""
        },
        "editlink": {
            "base": "",
            "label": "编辑本页"
        },
        "sharing": {
            "weibo": true,
            "twitter": false,
            "facebook": false
        },
        "fontSettings": {
            "theme": "night",
            "family": "sans",
            "size":1
        }
    },
    "links": {
        "sidebar": {
        //链接地址
            "个人博客": "https://szyuema.github.io/"
        },
        "sharing": {
            "google": null,
            "facebook": null,
            "twitter": null,
            "weibo": null,
            "all": null
        }
    },
    "pdf": {
        "toc": true,
        "pageNumbers": true,
        "fontSize": 12,
        "paperSize": "a4",
        "margin": {
            "right": 62,
            "left": 62,
            "top": 36,
            "bottom": 36
        }
    }
}


```


