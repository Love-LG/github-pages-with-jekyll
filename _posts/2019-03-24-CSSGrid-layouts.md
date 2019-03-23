---
title: "CSS　Grid: 使用媒体查询创建响应布局"
date: 2019-03-24
---
### 通过使用媒体查询重新排列网格区域，更改网格的尺寸以及重新排列项目的位置，CSS网格可以轻松地使网站更具响应性。

#### Eg:下面的列子当视口宽度小于300px时将显示header advert content footer四行一列，当视口宽度大于等于300px时变成两列左侧为advert右侧为三行分别是headr content footer当视口宽度大于等于400px时将变成三行分别是header content footer但是content左侧是advert右侧是content
```css
.item1{
  background:LightskyBlue;
  grid-area: header;
}
.item2{
  background:LightSalmon;
  grid-area: advert;
}
.item3{
  background:PaleTurquoise;
  grid-area: content;
}
.item4{
  background: palegreen;
  grid-area: footer;
}

.container {
  font-size: 1.5em;
  min-height: 300px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 1fr; 
  grid-template-rows: 50px auto 1fr auto;
  grid-gap: 10px;
  grid-template-areas:
    "header"
    "advert"
    "content"
    "footer";
}
@media (min-width: 300px){
  .container{
    grid-template-columns: auto 1fr;
    grid-template-rows: auto 1fr auto;
    grid-template-areas:
      "advert header"
      "advert content"
      "advert footer";
  }
}
@media (min-width: 400px){
  .container{
    grid-template-areas:
      "header header"
      "advert content"
      "footer footer";
  }
}
```
```html
<div class="container">
  <div class="item1">header</div>
  <div class="item2">advert</div>
  <div class="item3">content</div>
  <div class="item4">footer</div>
</div>
```
