---
title: Python数据分析环境搭建
tags: 入门
author: Weipeng Zhang
---

Anaconda是一个适用于Python数据分析的开发包，其中封装了Python和数据分析、机器学习常用库以及JupyterNotebook和Spyder等开发环境，十分方便。

**注：这里以Win10安装为例**

---

### 1. 下载Anaconda

在[Anaconda官网]([https://www.anaconda.com](https://www.anaconda.com/))下载适用于自己系统的开发包。

![1570934740001](/images/2019-10-13-build-Python-DS-env/1570934740001.png)

点击**Download**后选择自己的操作系统并选择Python3.7安装包(默认大家都是64位的系统了)

![1570934851613](/images/2019-10-13-build-Python-DS-env/1570934851613.png)

然后等待下载完成（这里推荐右键复制下载链接后到迅雷中下载，比直接在浏览器里下快不少）



### 2. 安装Anaconda

![1570935004767](/images/2019-10-13-build-Python-DS-env/1570935004767.png)

点击**Next**.

![1570935025675](/images/2019-10-13-build-Python-DS-env/1570935025675.png)

点击**I Agree**

![1570935051298](/images/2019-10-13-build-Python-DS-env/1570935051298.png)

这里自行选择，一般情况下直接默认就可以了。点击**Next**

![1570935091306](/images/2019-10-13-build-Python-DS-env/1570935091306.png)

选择安装位置，可以自行设置。点击**Next**

![1570935139389](/images/2019-10-13-build-Python-DS-env/1570935139389.png)

选中**“将Anaconda添加到系统环境变量”**，这样安装完成后就不用手动配置了。点击**Install**,等待安装完成。



### 3. 完成安装

打开命令提示符

![1570935530474](/images/2019-10-13-build-Python-DS-env/1570935530474.png)

输入```conda --version```

![1570935555448](/images/2019-10-13-build-Python-DS-env/1570935555448.png)

如果显示出anaconda的版本，则说明安装成功。

输入```python```

![1570935602300](/images/2019-10-13-build-Python-DS-env/1570935602300.png)

显示如图则说明Python3.7环境也配置好了，按`Ctrl+D`退出

输入```jupyter notebook```

![1570935719402](/images/2019-10-13-build-Python-DS-env/1570935719402.png)

在默认的浏览器中弹出如图的网页则说明JupyterNotebook配置完成。