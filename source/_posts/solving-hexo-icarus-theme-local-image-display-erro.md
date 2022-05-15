---
title: solving  hexo icarus theme local image display erro
date: 2022-05-15 05:43:27
tags:
---
# 解决hexo 本地图片无法显示问题
**1.问题定义**: 利用hexo 搭建静态博客，页面无法显示本地图片（如果图片网络地址来自网络可以正确显示）

**2.问题解决**: 本地图片相对地址编译过程不能正确匹配网络端地址

**3.解决过程演示**
hexo + icarus theme 搭建静态博客 *source/gallery/test/tt.jpeg*

```bash
<div class="justified-gallery">

![hah](https://elementsix.github.io/img/tt.jpeg)
![hah](https://elementsix.github.io/gallery/test/tt.jpeg)

</div>
```