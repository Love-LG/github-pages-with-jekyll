---
title: "CSS Flexbox使用display： flex定位两个Box"
date: 2019-03-20
---
**css**
```css
#box-container {
height: 500px;
display: flex;
}
#box-1 {
background-color: dodgerblue;
width: 50%;
height: 50%;
}
#box-2 {
background-color: orangered;
width: 50%;
height: 50%;
}
```
**Html**
```html
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```
**display: flex**实现box-1和box-2左右布局。
