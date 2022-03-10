---
title: "StringBuffer、StringBuilder区别"
date: 2022-03-10T16:32:52+08:00
draft: false
tags: [面试]
categories: [面试技巧]
---
### 区别

* StringBuffer更快，但线程不安全，常用
* StringBuilder稍慢，但线程安全

### 线程安全性

* 如果没有额外声明，所有类的默认都是线程不安全的
