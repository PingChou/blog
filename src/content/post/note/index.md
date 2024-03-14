---
title: 关于递归和尾递归的学习理解
description: "Please enter a description of your post here, between 50-160 chars!"
publishDate: 14 March 2024
tags: ["note"]
draft: false
---

> 尾递归是递归函数在最后一行返回调用函数本身。起到的作用的是，省略函数的上下文，防止递归函数堆栈溢出。但是 chrome 的 V8 引擎并没有针对尾递归进行函数的优化，目前仍然会导致堆栈溢出
