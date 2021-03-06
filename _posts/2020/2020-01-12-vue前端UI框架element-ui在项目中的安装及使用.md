﻿---
layout: post
title: vue前端UI框架element-ui在项目中的安装及使用
date: 2020-01-12 00:00:00
categories: 
- Element-UI-前端UI框架
tags: 
- Vue
- Vue-cli
- Element-UI
description: element-ui是款热门的vue前端UI框架。
---



# element-ui的安装
## 普通安装
element-ui是款热门的vue前端UI框架，官方文档为：[https://element.eleme.io/#/zh-CN](https://element.eleme.io/#/zh-CN)。要安装element-ui，只需要在vue项目根目录中执行：
```
npm i element-ui -S
```

## 使用vue-cli3安装
如果自己的vue项目于是用vue-cli3创建的，则有更好的安装办法，使用对应vue-cli的element插件，官方github地址为：[https://github.com/ElementUI/vue-cli-plugin-element](https://github.com/ElementUI/vue-cli-plugin-element)，在vue项目根目录中执行：
```
vue add element
```
安装过程需要选择一些选项，选择结果参照下图：

![在这里插入图片描述](https://gitee.com/watchcat2k/pictures_base/raw/master/2020/1/12-1.png)

- 全局导入element-ui组件
- 选择覆盖element的scss变量
- 语言选择中文

# 使用
使用element-ui进行前端页面开发时，建议参考官方的组件文档：[https://element.eleme.cn/#/zh-CN/component/layout](https://element.eleme.cn/#/zh-CN/component/layout)，文档中给出了所有的组件及对应的代码，开发时只需按照需要复制相应的代码即可。


# 可视化编辑
为了更快地利用element-ui开发前端页面，可以使用在线的可视化编辑器：[MagicalCoder布局器2.2.3](http://lowcode.magicalcoder.com/magicaldrag/index-page.html)，如下图：

![在这里插入图片描述](https://gitee.com/watchcat2k/pictures_base/raw/master/2020/1/12-2.png)

该工具可以帮助我们快速实现布局和基本页面设计，还提供了调试和样式调整的功能，然后下载对应的HTML代码到自己的项目中。
