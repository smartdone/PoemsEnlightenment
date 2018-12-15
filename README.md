# 声律启蒙中的典故

《声律启蒙》和《笠翁对韵》一样，是以前学童的基础读物。《声律启蒙》是康熙年间的[车万育](https://baike.baidu.com/item/%E8%BD%A6%E4%B8%87%E8%82%B2/3612152?fr=aladdin)编写的；《笠翁对韵》是明末清初的[李渔](https://baike.baidu.com/item/%E6%9D%8E%E6%B8%94/3817?fr=aladdin)编写的。

我们知道，诗文中一般都会使用典故。《声律启蒙》中列举了很多很多的典故，我们可以通过学习声律启蒙了解到不少历史知识，也能知道哪些典故是能两两相对的。学习之后可能对我们写作乃至是写诗作词会有很大的帮助。

## 为什么要整理声律启蒙中的典故？

1. 想要维护一些GitHub项目，但是没想出来些什么技术性的项目
2. 弘扬国学
3. 打发无聊时间

## 如何构建成可视性更好的文档

> 待整理完整之后会将构建好的发布至release

### 环境准备

安装`nodejs`以及`npm`

```shell
sudo apt install nodejs
sudo apt install npm
```

安装`gitbook`

```shell
sudo npm install -g gitbook-cli
```

### 构建成html

```shell
gitbook build [书籍目录] [输出目录]
```

例如`gitbook build . ../build`

### 构建成pdf

```shell
gitbook pdf [书籍目录] [输出pdf路径]
```

例如`gitbook pdf ./ ../out.pdf`

### 构建成epub

```shell
gitbook epub [书籍目录] [输出epub路径]
```

例如`gitbook epub ./ ../out.epub`

### 构建成mobi

```shell
gitbook mobi [书籍目录] [输出mobi路径]
```

例如`gitbook mobi ./ ../out.mobi`

## 欢迎提issue

由于本人水平相当有限，仅仅是整理了一下，如果整理的过程中有什么错误，欢迎提issue，或者提pull request。