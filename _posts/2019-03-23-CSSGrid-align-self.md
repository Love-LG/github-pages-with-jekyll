---
title: "CSS Grid: 使用align-self垂直对齐项目"
date: 2019-03-23
---
### `justify-self`用于水平对齐项目`align-self`用于垂直对齐项目，align-self接受justify-self相同的值
```css
.item1{background:LightskyBlue;}
.item2{
  background:LightSalmon;
  justify-self: center;
}
.item3{
  background:PaleTurquoise;
  align-self: end;
}
.item4{background:LightPink;}

.item5 {
  background: palegreen;
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
[Try Now!](https://learn.freecodecamp.org/responsive-web-design/css-grid/align-an-item-vertically-using-align-self)
