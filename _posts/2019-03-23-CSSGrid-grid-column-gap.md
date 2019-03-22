---
title: "CSSGrid: 使用grid-column-gap创建列间隙"
date: 2019-03-23
---
### 当我们希望创建的列之间的间隔时我们可以使用`grid-column-gap`属性
```bash
grid-column-gap: 10px
```
> 上面代码会在所有列之间创建10px的空白空间。

### Example:
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
  grid-column-gap: 10px;
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
[Try Now!](https://learn.freecodecamp.org/responsive-web-design/css-grid/create-a-column-gap-using-grid-column-gap)
