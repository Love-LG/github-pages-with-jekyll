---
title: "CSSFelxbox: 使用align-items属性对其元素"
date:  2019-03-21
---
### align-items沿着交叉轴对齐弹性项目属性，可用的不同值包括：
* **flex-start**将项目对齐到Flex容器的开头。对于行，这会将项目对齐到容器的顶部。对于列，这会将项目对齐容器的左侧。
* **flex-end**将项目对齐到Flex容器的末尾。对于行，这会将项目对齐到容器的底部。对于列，这会将项目对齐到容器的右侧。
* **center**将项目对齐到中心。对于行，这会垂直对齐项目（项目上方和下方的空间相等）。对于列，它会水平对齐它们（项目左侧和右侧的空格相等）。
* **stretch**拉伸项目以填充Flex容器。例如，行项目被拉伸以从上到下填充Flex容器。
* **baseline**将项目与其基线对齐。基线是一个文本概念，将其视为字母所在的行

```css
#box-container {
  background: gray;
  display: flex;
  height: 500px;
  align-items: center;
}
#box-1 {
  background-color: red;
  width: 200px;
  font-size: 24px;
}
#box-2 {
  background-color: blue;
  height: 200px;
  font-size: 18px;
}
```

```html
<div id="box-container">
  <div id="box-1"><p>Hello</p></div>
  <div id="box-2"><p>Goodbye</p></div>
</div>
```
