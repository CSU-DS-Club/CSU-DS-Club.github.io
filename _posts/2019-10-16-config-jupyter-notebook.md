---
title: Jupyter Notebook配置
tags: 入门
author: Weipeng Zhang
---

在安装了Jupyter Notebook后就可以愉快地开始敲Python代码了。安装主题和插件之后可以很大地提升敲代码的体验和效率。

### 安装主题

在命令行中输入`pip install jupyter-themes `等待安装完成。

然后就可以开始自定义主题了。主题有很多种，我使用的时`grade3`。

这是我的主题配置：```jt -t grade3 -fs 11 -T -cellw 90%``` 具体含义为：设置主题为grade3, 字体大小为11，显示工具栏，单元格宽度为整个页面宽度的90%

更多的配置命令见[jupyter-themes github主页](https://github.com/dunovank/jupyter-themes)

配置后的效果如下

![1571216845608](/images/2019-10-16-config-jupyter-notebook/1571216845608.png)

### 安装插件

在命令行中输入```conda install -c conda-forge jupyter_contrib_nbextensions``` 等待安装完成。

重启jupyter notebook可以在打开的界面上发现多了一个选项：

![1571217009331](/images/2019-10-16-config-jupyter-notebook/1571217009331.png)

点进去之后是这样的。勾选自己想要使用的插件即可。

![1571217076854](/images/2019-10-16-config-jupyter-notebook/1571217076854.png)

非常推荐图中圈出来的3个插件，分别是按markdown标题折叠、代码折叠和显示目录。

#### 效果

**折叠标题：**

![1571217228682](/images/2019-10-16-config-jupyter-notebook/1571217228682.png)

**显示目录**

![1571217244574](/images/2019-10-16-config-jupyter-notebook/1571217244574.png)

**代码折叠**

![1571217303264](/images/2019-10-16-config-jupyter-notebook/1571217303264.png)