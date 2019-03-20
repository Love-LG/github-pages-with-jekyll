---
title: "在flex容器中使用 flex-direction 实现行反转或列反转"
date: 2019-03-20
---

### flex-direction: row-reverse|column-reverse  defult row-reverse
```css
#box-container {
  display: flex;
  height: 500px;
  flex-direction: row-reverse; //row-reverse or column-reverse
}
#box-1 {
  background-color: red;
  width: 50%;
  height: 50%;
}
#box-2 {
  background-color: blue;
  height: 50%;
  width: 50%;
}
```

```html
<div id="box-container">
  <div id="box-1"></div>
  <div id="box-2"></div>
</div>
```
