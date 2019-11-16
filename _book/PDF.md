# markdown|gitbook创建PDF电子书

## 1. 问题描述

markdown写作效率很高，但不适合大篇幅的手册、书籍、文档编辑。要实现书籍级别的写作，必须实现有效的子文档分解和集成，类似LaTeX。gitbook软件平台实现了这一功能。

## 2. 技术背景

gitbook对大规模文档进行子文件分解，通过summary文件组织章节构架，形成总体文章。

## 3.怎样生成pdf

在项目的目录中执行

```
gitbook pdf
```

即可在项目目录下看到book.pdf的文件

这里遇到一个问题，在输入命令后报错，产生乱码，经过百度，下载了一个叫Calibre的软件，将其路径加入path，重新开启cmd，输入命令，即可。