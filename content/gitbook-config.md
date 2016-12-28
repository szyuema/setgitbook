# GitBook配置

[GitBook官方地址](https://www.gitbook.com)

>1.请先建立一个文件夹，例如E:\xx\gitbook\mybook_test

>2.将README.md和SUMMARY.md放到mybook_test下，注意要用md工具编辑，否则可能后面生产的book存在中文乱码

>3.初始化。在mybook_test目录执行：gitbook init。目录下会自动生成一些目录和文件夹。

>4.启动浏览器查看。在E:\xx\gitbook目录执行：gitbook serve ./mybook_test，如下：


## GitBook 常用命令

安装gitbook需要的插件
``` bash
gitbook install 目录

```

启用gitbook 可以在 http://localhost:4000/ 访问
``` bash
gitbook serve 文件目录 生成目录

```

生成站点
``` bash
gitbook build 文件目录 生成目录

```

转换pdf
``` bash
gitbook pdf 文件目录 生成目录

```

下面介绍gitbook常用的几个文件配置