---
title: "CSSFlexbox: 使用order属性重新排列项目"
date: 2019-03-21
---
### `order`属性用于告诉CSS弹性项目在弹性容器中的显示顺序。默认情况下，项目将按照它们在源HTML中的顺序显示。该属性将数字作为值，可以使用负数。
```css
#box-container {
  display: flex;
  height: 500px;
}
#box-1 {
  background-color: blue;
  height: 200px;
  width: 200px;
  order: 2;
}
#box-2 {
  background-color: red;
  height: 200px;
  width: 200px;
  order: 1;
}
```

```html
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"> </div>
</div>
```
