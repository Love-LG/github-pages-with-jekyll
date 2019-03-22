---
title: "CSS Grid: 使用`grid-template-rows`添加行"
date: 2019-03-22
---
### `grid-template-rows`可以设置行并设置行高
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
  grid-template-columns: 50px 50px 50px;  //设置三列每一列宽50px
  grid-template-rows: 100px 100px;   //设置两行行高100px
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
