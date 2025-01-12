+++
title = "学习定制化博客样式"
tags = [
    "博客样式",
]
categories = [
    "搭建博客",
]
+++

## Emoji

https://emoji6.com/emojiall/

## 更改表格样式

实现表格表头下的横线（`themes/hugo-book/assets/_markdown.scss`）

```tpl
table {
    overflow: auto;
    display: block;
    border-spacing: 0;
    border-collapse: collapse;
    margin-top: $padding-16;
    margin-bottom: $padding-16;
    th {
      border-bottom: 2px solid #000000;
    }
    tr td {
      padding: $padding-8 $padding-16;
      border: none;
      // border-bottom: 1px solid #0000007c;
    }
    tr:nth-child(2n) {
      background: var(--gray-100);
    }
  }
```