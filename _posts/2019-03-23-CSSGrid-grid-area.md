---
title: "CSS Grid：使用grid-area属性往网格区域中放置项目"
date: 2019-03-23
---
### 利用可以使用`grid-area`属性将项目放在自定义区域中
```bash
.item1 {grid-area: header;}
```
#### 上述代码可以让'item1'变成header区域，并且占据整个顶行

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
  grid-area: footer;
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
  grid-template-areas:
    "headr header header"
    "advert content content"
    "footer footer footer";
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
[Try Now!](https://learn.freecodecamp.org/responsive-web-design/css-grid/place-items-in-grid-areas-using-the-grid-area-property)
