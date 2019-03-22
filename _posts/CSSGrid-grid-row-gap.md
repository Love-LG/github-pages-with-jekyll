---
title: "CSS Grid: 使用grid-row-gap创建行间隙"
date: 2019-03-23
---
### 当我们想为网格行添加间隙可以使用`grid-row-gap`属性。
```bash
grid-row-gap: 5px;
```
> 上面代码表示为每一行建立间隙为5px

## Example：
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
  grid-template-columns: 1fr 1fr 1fr; 
  grid-template-rows: 1fr 1fr 1fr;
  grid-row-gap: 5px;
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
[Try Now!](https://learn.freecodecamp.org/responsive-web-design/css-grid/create-a-row-gap-using-grid-row-gap)
