---
title: "CSSFlexbox: 使用flex-wrap属性包装行或者列"
date: 2019-03-21
---

### CSS flexbox具有将Flex项目拆分为多行（或列）的功能。默认情况下，Flex容器将所有Flex项目放在一起。例如，一行将全部在一行上。
但使用flex-wrap属性会重新包装flex项目。
* **nowrap**默认选项，不包装项目
* ** wrap**如果项目在一行中，则从左到右包装，如果它们在列中，则从上到下包装。
* **wrap-reverse**如果项目在一行中，则从下到上包装项目;如果它们在列中，则从右到左包装。

```css
#box-container {
  background: gray;
  display: flex;
  height: 100%;
  flex-wrap: wrap;
}
#box-1 {
  background-color: blue;
  width: 25%;
  height: 50%;
}
#box-2 {
  background-color: orange;
  width: 25%;
  height: 50%;
}
#box-3 {
  background-color: red;
  width: 25%;
  height: 50%;
}
#box-4 {
  background-color: yellow;
  width: 25%;
  height: 50%;
}
#box-5 {
  background-color: green;
  width: 25%;
  height: 50%;
}
#box-6 {
  background-color: black;
  width: 25%;
  height: 50%;
}
```

```html
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
  <div id="box-3"></div>
  <div id="box-4"></div>
  <div id="box-5"></div>
  <div id="box-6"></div>
</div>
```
