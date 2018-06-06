---
layout: post
title: "Java 8 Functional Interfaces笔记"
date: 2018-06-06 17:15:33 +0700
comments: true
categories:
---

最近在准备OCJP 8考试，需要熟悉一下Java 8引入的函数式编程的概念。具体包括了Functional Interfaces、Lambda表达式、Stream API等新知识。

最值得阅读的文档一般都是官方文档。[Oracle](https://docs.oracle.com/javase/8/docs/api/java/util/function/package-summary.html)和[Android](https://developer.android.com/reference/java/util/function/package-summary)都有文档的链接。

## 4个典型的Functional interfaces
1. `Comsumer`    
2. `Supplier`    
3. `Predicate`    
4. `Function`    

## 补充
arity的解释是"元数"，就是参数数目的意思。
