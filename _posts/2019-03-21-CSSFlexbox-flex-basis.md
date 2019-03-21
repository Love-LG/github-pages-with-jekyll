---
title: "CSS Flexbox：使用flex-basis属性设置项的初始大小"
date: 2019-03-21
---
### flex-basis在CSS使用flex-shrink或进行调整之前，该属性指定项目的初始大小flex-grow,单位有`px`,`em`,`%`等

```css
#box-container {
  display: flex;
  height: 500px;
}
#box-1 {
  background-color: blue;
  height: 200px;
  flex-basis: 10em;
}
#box-2 {
  background-color: red;
  height: 200px;
  flex-basis: 20em;
}
```

```html
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"> </div>
</div>
```
