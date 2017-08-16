---
title: record-some-interview-questions
date: 2017-04-11 17:19:50
tags:
   - C#
   - .Net
   - SQL Server
---

## 记录几个面试题

* 写出SQL Server中随机查询出一张表中20条数据的语句

  ```mssql
  select top n * from tableA order by newid()
  ```

* CROSS APPLY和OUTER APPLY的区别
  Outer Apply会将右表查询后的空数据插入到左表对应条目后，而Cross Apply不会。详见下一篇博文。