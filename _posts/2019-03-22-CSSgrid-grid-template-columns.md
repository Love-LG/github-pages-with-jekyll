---
title: "CSSgrid: 使用`grid-template-columns`添加列"
date: 2019-03-22
---
### `grid-template-columns`属性的参数数量表示网格中的列数，每个参数的值表示每列的宽度.
```css
.d1{background:LightskyBlue;}
.d2{background:LightSalmon;}
.d3{background:PaleTurquoise;}
.d4{background:LightPink;}
.d5{background:PaleGreen;}

.container {
  font-size:40px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 50px 50px;
}
```
```html
<div class="container">
  <div class="d1">1</div>
  <div class="d2">2</div>
  <div class="d3">3</div>
  <div class="d4">4</div>
  <div class="d5">5</div>
</div>
```
