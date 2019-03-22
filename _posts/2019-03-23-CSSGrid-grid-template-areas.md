---
title: "CSS　Grid： 将网格划分为区域模块"
date: 2019-03-23
---
### 可以将网格的单元格组合到一个区域中，并为该区域指定一个自定义名称。通过`grid-template-areas`在容器上使用这样做：
```bash
grid-template-areas:
     "header header header"
     "advert content content"
     "footer footer footer";
```

#### 面的代码将前三个单元格合并为一个区域`header`，将底部的三个单元格合并为一个`footer`区域，并在中间行中生成两个区域; `advert`和`conten`

> 注意！
* 代码中的每个单词代表一个单元格，每对引号代表一行。
* 除自定义标签外，您还可以使用句点`.`来指定网格中的空单元格。

[Try Now!](https://learn.freecodecamp.org/responsive-web-design/css-grid/divide-the-grid-into-an-area-template)
