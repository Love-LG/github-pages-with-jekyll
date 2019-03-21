---
title: "CSS Flexbox: 使用justify-content属性对齐元素"
date: 2019-03-21
---

flex容器中的flex项不会填充容器的所有空间，所以使用**justify-content**来实现特定方式对齐flex项常用选项有
* **center**将弹性项对齐到弹性容器的中心
* **flex-start**将项目对齐到Flex容器的开头。
* **flex-end**将项目对齐到Flex容器的末尾。
* **space-between**将项目对齐到主轴中心。
* **space-around**和space-between类似。

```css
#box-container {
  display: flex;
  height: 500px;
  justify-content: center;   //flex-start|flex-end|space-between|space-around
#box-1 {
  background-color: red;
  width: 25%;
  height: 100%;
}
#box-2 {
  background-color: blue;
  height: 250%;
  width: 100%;
}
```
```html
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```
