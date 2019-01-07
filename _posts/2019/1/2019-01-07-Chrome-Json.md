---
layout:     post
title:      Chrome浏览器如何格式化查看JSON数据
subtitle:   Chrome格式化Json
date:       2019-1-07
author:     Chen
header-img: img/post-bg-rwd.jpg
keywords_post:  "Chrome安装，Web前端助手FeHelper格式化JSON"
catalog: true
tags:
    - Chrome测试返回Json格式化
---



## Chrome浏览器如何格式化查看JSON数据？

我们看到的JSON数据一般都没有经过格式化处理，没有缩进，没有换行等，给开发者阅读造成了一定困难。而JSONView扩展程序可以自动对JSON数据转码、缩进、格式化，直接显示出格式化后的数据，同时它还支持各种数据类型的语法高亮，以及节点的收缩和展开等，使得开发人员可以更好的阅读信息。JSONView是一个比较使用比较广泛的的查看格式化后JSON数据的扩展程序，但笔者使用下来，不是很好用。经笔者测试，发现WEB前端助手(FeHelper)扩展程序比JSONView更好用一些。本文说明如何安装 & 使用WEB前端助手(FeHelper)扩展程序来查看JSON数据。

![](https://github.com/DreamItPossible/DreamItPossible.github.io/blob/master/_posts/2019/1/chrome.PNG)

## 方法/步骤

1. 1

   **升级Chrome到最新版本**

   参考下面经验"**如何离线安装Chrome最新版本或某一特定版本？**"，将Chrome升级到最新版本。





   [如何离线安装Chrome最新版本或某一特定版本？](https://jingyan.baidu.com/article/8ebacdf00a711649f65cd5e5.html)

2. 2

   **下载WEB前端助手(FeHelper)扩展程序**

   最新版本：10.2

   更新日期：2017-09-15

   下载地址：http://pan.baidu.com/s/1qYc9XSS

   [![](https://github.com/DreamItPossible/DreamItPossible.github.io/blob/master/_posts/2019/1/11.PNG)]

3. 3

   **安装WEB前端助手(FeHelper)扩展程序**

   参考下面经验"**如何离线安装Chrome插件?**"，离线安装上面下载的WEB前端助手(FeHelper)扩展程序。



   [如何离线安装Chrome插件?](https://jingyan.baidu.com/article/e5c39bf5cc39cc39d76033cd.html)



   ![](https://github.com/DreamItPossible/DreamItPossible.github.io/blob/master/_posts/2019/1/22.PNG)

   ![](https://github.com/DreamItPossible/DreamItPossible.github.io/blob/master/_posts/2019/1/33.PNG)

4. 4

   **测试WEB前端助手(FeHelper)**

   浏览Json数据，WEB前端助手(FeHelper)会将JSON数据格式化显示。

   ![](https://github.com/DreamItPossible/DreamItPossible.github.io/blob/master/_posts/2019/1/44.PNG)

5. 5

   **如何格式化显示JSON数据？**

   按下F12，打开开发者工具，选择"**Network**"选项卡，找到输出JSON数据的请求，右键菜单选择"**Open in tab**"就可以在标签页中查看格式化后的JSON数据了。

   ![](https://github.com/DreamItPossible/DreamItPossible.github.io/blob/master/_posts/2019/1/55.PNG)

   ![](https://github.com/DreamItPossible/DreamItPossible.github.io/blob/master/_posts/2019/1/66.PNG)

6. 6

   **设置WEB前端助手(FeHelper)**

   右键点击WEB前端助手(FeHelper)扩展程序图标，下拉菜单中选择"**选项**"，打开WEB前端助手(FeHelper)的选项设置功能，可以开启/关闭功能。

   ![](https://github.com/DreamItPossible/DreamItPossible.github.io/blob/master/_posts/2019/1/77.PNG)

   ![](https://github.com/DreamItPossible/DreamItPossible.github.io/blob/master/_posts/2019/1/88.PNG)

   希望这些对你有帮助。如果想要学习到更多有关Chrome使用测试的知识点，请看[ShaLongBus](https://jingyan.baidu.com/user/npublic?uid=b458c311edf5000f9b2d569f)博客，这个博主有很多文章，非常有用！
   
   >参考[ShaLongBus](https://jingyan.baidu.com/user/npublic?uid=b458c311edf5000f9b2d569f)
     








