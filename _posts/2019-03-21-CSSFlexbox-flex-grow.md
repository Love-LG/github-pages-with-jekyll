---
title: "CSSFlexbox: 使用flex-grow属性扩展项目"
date: 2019-03-21
---
### `flex-grow`与`flex-shrink`功能刚好相反如果一个项的flex-grow值为1而另一个项的flex-grow值为3，则值为3的那个将增长到另一个的三倍。
```css
#box-container {
  display: flex;
  height: 500px;
}
#box-1 {
  background-color: blue;
  height: 200px;
  flex-grow: 1;
}
#box-2 {
  background-color: red;
  height: 200px;
  flex-grow: 2;
}
```
```html
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"> </div>
</div>
```
