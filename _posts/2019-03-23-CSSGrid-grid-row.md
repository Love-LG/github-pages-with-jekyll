---
title: "CSS Grid: 使用grid-row来控制间距"
date: 2019-03-23
---
### 使用`grid-row`来合并行

### Example:
```css
.item1{background:LightskyBlue;}
.item2{background:LightSalmon;}
.item3{background:PaleTurquoise;}
.item4{background:LightPink;}

.item5 {
  background: paleGreen;
  grid-column: 2/4;
  grid-row: 2/4;
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
[Try Now!](https://learn.freecodecamp.org/responsive-web-design/css-grid/use-grid-row-to-control-spacing)
