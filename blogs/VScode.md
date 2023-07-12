---
layout: page
permalink: /blogs/web/index.html
title: web

---

## 如何在MAC上使用VScode来写C++项目



```html
<center>
  <img src="/blogs/VScode/VScode.png">
</center>
```

<br>

本文记录了在Mac系统上使用VScode写C++的配置过程。

---

### 1. 下载VScode for Mac

下载地址：https://code.visualstudio.com/sha/download?build=stable&os=darwin-universal

据说无法科学上网的小伙伴说，官网下载比较慢，拷贝链接到迅雷下载速度很快。

<br>

### 2. 配置本地C++编译环境

理论上来说Mac是具备本地的C++编译环境的。在terminal中使用如下命令查看是否安装g++。

```bash
g++ --version
```

<br>

如果结果类似下图，则已安装。

```html
<center>
  <img src="/blogs/VScode/g++.png">
</center>
```

<br>

否则，在终端使用如下命令安装（其实是装了个Xcode...）：

```bash
xcode-select --install
```

<br>

### 3. 在VSCode中安装C++插件

```html
<center>
  <img src="/blogs/VScode/plugins.png">
</center>
```

在搜索框中搜索安装下面的两个插件：

* C/C++
* Code Runner

<br>

All set! 

