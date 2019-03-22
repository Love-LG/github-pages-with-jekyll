---
title: "CSS Grid: 使用grid-column来控制间距"
date: 2019-03-23
---
### `grid-column`实现跨列，可实现合并行的功能，是第一个用于网格本身的属性。
### Example：
```css
.item1{background:LightskyBlue;}
.item2{background:LightSalmon;}
.item3{background:PaleTurquoise;}
.item4{background:LightPink;}

.item5 {
  background: paleGreen;
  grid-column: 2/4;
}

.container {
  font-size:40px;
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
