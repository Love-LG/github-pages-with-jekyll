---
title: "CSS Grid: 使用minmax函数限制项目的大小"
date: 2019-03-24
---
### 当我们想限制网格中项目的大小时可以使用`grid-template-columns`和`grid-template-rows`调用`minmax`
他接受两个参数一个是最小值、一个是最大值
```css
grid-template-columns: 100px minmax (50px, 200px);
```

> 上面代码，`grid-template-columns`创建了两列，第一个是100px宽，第二个是最小宽度50px 最大宽度200px

### Example:
使用`grid-template-columns`属性创建重复3列，每一列最小宽度90px最大宽度1fr
```css
grid-template-columns: repeat(3, minmax(90px,1fr));
```
