---
title: "CSSFlexbox: 使用flex-shrink属性收缩项目"
date: 2019-03-21
---
### flex-shrink实现容器的收缩，数字越大收缩得越多，如果一个项目的flex-shrink值为1而另一个项目的flex-shrink值为3，则值为3的项目将缩小为另一个项目的三倍。
```css
#box-container {
  display: flex;
  height: 500px;
}
#box-1 {
bakground-color: blue;
width: 100%;
height: 200px;
flex-shrink: 1;
}
#box-2 {
  bakground-color: red;
  width: 100%;
  height: 200px;
  flex-shrink: 2;
}
```

```html
<div id="box-container">
<div id="box-1"></div>
<div id="box-2"></div>
</div>
```
