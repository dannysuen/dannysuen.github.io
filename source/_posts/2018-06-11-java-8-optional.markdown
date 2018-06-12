---
layout: post
title: "Java 8 Optional"
date: 2018-06-11 21:15:02 +0700
comments: true
categories:
---

首先仔细浏览[Oracle](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)和[Android](https://developer.android.com/reference/java/util/Optional)官方API文档。

Urma关于空指针的一段话：
>I will argue in this article that using null to represent the absence of a value is a wrong approach. What we need is a better way to model the absence and presence of a value.

关于引入`java.util.Optional`类的初衷：
>It is important to note that the intention of the Optional class is not to replace every single null reference. Instead, its purpose is to help design more-comprehensible APIs so that by just reading the signature of a method, you can tell whether you can expect an optional value. This forces you to actively unwrap an Optional to deal with the absence of a value.
