---
title: "CSS Grid: 使用justify-items水平对齐所有项目"
date: 2019-03-23
---
### 之前介绍的`justify-self`用于对单个项目内容进行水平对齐，当我们需要对所有的项目都水平对齐时就可以使用`justify-items`
```bash
justify-items: center;
```
> 上述代码可以让所有item水平居中

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
  justify-items: center;
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
[Try Now!](https://learn.freecodecamp.org/responsive-web-design/css-grid/align-all-items-horizontally-using-justify-items)
