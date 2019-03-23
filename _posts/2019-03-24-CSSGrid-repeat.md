---
title: "CSS Grid: 使用repeat函数减少重复"
date: 2019-03-24
---
### 使用`grid-template-columns`和`grid-template-rows`定义网格结构时，为所创建的每个行或列输入了一个值,
当我们想要创建很多行相同高度的网格时，要单独插入值肯定不现实，所以我们可以使用`repeat`函数指定我们希望重复的列或者行的次数，然后使用`,`号和要重复的值
```css
grid-template-rows: repeat (100,50px)
```
> 上述代码创建一百行网格，每行高度50px

Eg: 详列两行代码等价：
```css
grid-template-columns: repeat (2,1fr 50px) 20px;
```
```css
grid-template-columns: 1fr 50px 1fr 50px 20px;
```
`1fr 50px`重复两次，然后是20px

### Example：
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
  grid-template-rows: repeat(3,1fr);
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


