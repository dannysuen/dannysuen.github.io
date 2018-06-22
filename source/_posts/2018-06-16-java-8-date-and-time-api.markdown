---
layout: post
title: "Java 8 Date & Time API"
date: 2018-06-16 22:43:02 +0700
comments: true
categories:
---

[Android官方文档里](https://developer.android.com/reference/java/time/package-summary)

`java.time.temporal`: lower level access to the fields.        
`java.time.format`: customization options.    

>The offset-based date-time types OffsetTime and OffsetDateTime, are intended primarily for use with network protocols and database access. For example, most databases cannot automatically store a time-zone like 'Europe/Paris', but they can store an offset like '+02:00'.

## 获取当前月份
```java
Month.from(Instant.now().atZone(ZoneId.of("Asia/Bangkok"));
```    
