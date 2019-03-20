---
title: "Use the flex-direction property to make a Column"
date: 2019-03-20
---

### **flex-direction: column**实现垂直方向布局**row**为水平方向布局

```css
#box-container {
  display: flex;
  height: 500px;
  flex-direction: column;
}
#box-1 {
  background-color: red;
  width: 50%;
  height: 50%;
}
#box-2 {
  background-color: blue;
  height: 50%;
  width: 50%;
}
```

```html
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```
