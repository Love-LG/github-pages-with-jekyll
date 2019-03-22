---
title: "CSS Grid: 使用justify-self水平对其项目"
date: 2019-03-23
---
### 在CSS Grid中，每个项目的内容位于一个称为单元格的框中。可以使用`justify-self`网格项上的属性水平对齐内容在其单元格中的位置。默认情况下，此属性的值为stretch，这将使内容填充单元格的整个宽度。此CSS Grid属性也接受其他值：
* `start`对齐单元格左侧的内容
* `center`对齐单元格中心的内容
* `end`对齐单元格右侧内容
### Example：
```css
.item1{background:LightskyBlue;}
.item2{
  background:LightSalmon;
  justify-self: center;
}
.item3{background:PaleTurquoise;}
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
