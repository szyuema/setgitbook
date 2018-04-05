# 转换成pdf

1. 下载PDF
```bash
npm install ebook-convert -g
```

2. win下上述步骤会出错

`原因`

>貌似因为被墙了，下载不到phantomjs相关文件
>需要用到的工具:calibre,phantomjs;
`解决办法`

[点击这里下载phantomjs](http://pan.baidu.com/s/1dEEuTUT)
[备用原网址](http://phantomjs.org/download.html)

>压缩包解压到某个目录，如：E:\Program Files\phantomjs，并将此目录添加到系统变量path中

3.win 下载 ebook-conver

直接到 http://www.calibre-ebook.com/download_windows 下载：
或者[点击这里下载ebook-conver](http://pan.baidu.com/s/1eR4j6j4)

4.封面

>封面文件为: /cover.jpg.
尺寸为 1800x2360. 插件 autocover可以自动创建一个文件.
封面的小尺寸图形为: /cover_small.jpg.

5.命令
```bash
gitbook pdf
```


