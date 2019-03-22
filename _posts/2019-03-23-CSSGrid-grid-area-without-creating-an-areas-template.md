---
title: "CSS Grid: Use grid-area Without Creating an Areas Template"
date: 2019-03-23
---
### 如果网格没有要引用的区域模板，您可以动态创建一个区域，以便放置一个项目，如下所示:
```bash
.item1 {grid-area: 1/1/2/4; }
```
```
grid-area: 水平线开始于/垂直线开始于/水平线结束于/垂直线结束于;
```
> 竖直方向为水平线方向，横向为垂直方向

### Example:
```css
.item1{background:LightskyBlue;}
.item2{
  background:LightSalmon;
}
.item3{
  background:PaleTurquoise;
}
.item4{background:LightPink;}

.item5 {
  background: palegreen;
  grid-area: 3/1/4/4
}

.container {
  font-size:40px;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr; 
  grid-template-rows: 1fr 1fr 1fr;
  grid-gap: 10px;
}
```
```html
<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>
```
[Try Now!](https://learn.freecodecamp.org/responsive-web-design/css-grid/use-grid-area-without-creating-an-areas-template)
