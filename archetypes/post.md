---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
lastmod: {{ .Date }}
author: ["作者"]
categories:
- 分类1
- 分类2
tags:
- 标签1
- 标签2
# summary->在列表页展现的摘要内容，自动生成，内容默认前70个字符，可通过此参数自定义，一般无需专门设置
summary: ""
# description->需要自己编写的文章描述，是搜索引擎呈现在搜索结果链接下方的网页简介，建议设置
description: ""
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: ""
draft: false # 是否为草稿
comments: true
showToc: true # 显示目录
TocOpen: true # 自动展开目录
hidemeta: false # 是否隐藏文章的元信息，如发布日期、作者等
disableShare: true # 底部不显示分享栏
showbreadcrumbs: true #顶部显示当前路径
mermaid: true #是否开启mermaid
math: true # 是否开启mathjax
cover:
    image: ""
    caption: ""
    alt: ""
    relative: false
---

此处内容将会出现在摘要（summary）里

<!--more--> # 此处的“\”用于转义，否则无法正常显示，实际使用须删去。

此处开始为正文