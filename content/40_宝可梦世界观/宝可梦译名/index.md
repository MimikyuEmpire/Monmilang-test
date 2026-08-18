---
title: 宝可梦命名
date: 2026-08-17
publish: true
---

## 造词方法

宝可梦参考中、日、英三语命名（译名参考 [神奇宝贝百科](https://wiki.52poke.com/wiki/) 相关内容），再拆出词根进行造词

## 进度

目前只有宝可梦的中、日、英名称，**尚无梦谜语命名**

```base
views:
  - type: table
    name: 表格
    filters:
      and:
        - file.inFolder("40_宝可梦世界观/宝可梦译名")
        - file.basename != "index"
    order:
      - file.name
      - monmish
      - tags
    columnSize:
      file.name: 93
      note.monmish: 103

```
