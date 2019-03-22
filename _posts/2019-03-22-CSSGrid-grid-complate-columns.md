---
title: "CSS Grid: 使用css grid 的单位改变行或者列的大小"
date:  2019-03-22
---
### 可以使用绝对单位和相对单位比如`px`or`em`来制定网格行或者列的大小还有其他的单位：
* `fr`将行或者列设置为可用空间的一小部分
* `auto`自动将行或者列设置为其内容的宽度或者高度
* `%`将行或者列调整为其容器的百分比宽度
<details>
<summary>:computer_mouse:Example</summary>

```css
grid-template-columns: auto 50px 10% 2fr 1fr;
```
</details>
  
> 上述代码：创建了五列。第一列与其内容一样宽，第二列是50px，第三列是其容器的10％，最后两列; 剩下的空间分为三个部分，两个分配给第四列，一个分配给第五个。

### :keyboard:实列代码
<details>
<summary>CSS</summary>

```css
.d1{background:LightskyBlue;}
.d2{background:LightSalmon;}
.d3{background:PaleTurquoise;}
.d4{background:LightPink;}
.d5{background:PaleGreen;}

.container {
  font-size:40px;
  width: 100%;
  background: LightGray;
  display: grid;
  grid-template-columns: 1fr 100px 2fr; 
  grid-template-rows: 50px 50px;
}
```
<summary>Html</summary>

```html
<div class="container">
  <div class="d1">1</div>
  <div class="d2">2</div>
  <div class="d3">3</div>
  <div class="d4">4</div>
  <div class="d5">5</div>
</div>
```
</details>
