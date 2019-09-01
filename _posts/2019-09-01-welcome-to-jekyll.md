---
layout: post
title: Chapter Zero
date: '2015-12-18 21:45:10 +0800'
tags: 'Mailbox, Theme'
categories: Notes
---
text test...

markdown test:

This is a simple introduction to compiling Markdown in VS Code.

Things you'll need:

* [node](https://nodejs.org)
* [markdown-it](https://www.npmjs.com/package/markdown-it)
* [tasks.json](/docs/editor/tasks)

## Section 1

> This block quote is here for your information.

_下划线_

* point1
* point2

---

表格==测试==

第一格表头 | 第二格表头
--- | ---
内容单元格 第一列第一格 | 内容单元格第二列第一格

```javascript
var num = 0;
for (var i = 0; i < 5; i++) {
    num+=i;
}
console.log(num);
```

- [x] 选项一
- [ ] 选项二  
- [ ] 选项3


|    a    |       b       |      c     |
|:-------:|:------------- | ----------:|
|   居中  |     左对齐    |   右对齐   |
|=========|===============|============|

## Section 2

```mermaid
graph TD
   A --> B
```

```latex {cmd=true,hide}
\documentclass{standalone}
\begin{document}
   Hello world!
\end{document}
```