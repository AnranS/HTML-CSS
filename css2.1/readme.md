# css2.1复习

## 1、定位的参照物

- 没有定位：包含块
- 相对定位：元素本来的位置
- 绝对定位：包含块
  - 如果最近祖先元素中存在定位元素，则这个定位元素就是包含块，如果过没有，包含块是初始包含块

## 2、什么是包含块

​	是一个视窗大小的矩形，不等于视窗

## 3、一些属性的默认值

- left right top bottom width height 默认值都为auto
- margin pading 默认值是0

## 4、百分比参照

- width margin padding：参照与包含块的width
- height：参照与包含块的height
- left：包含块的width
- top：包含块的height
- ![image-20180510190720417](/var/folders/qk/zlt5hvq96qsgpgnby8bryc240000gn/T/abnerworks.Typora/image-20180510190720417.png)
- ![image-20180510190700291](/var/folders/qk/zlt5hvq96qsgpgnby8bryc240000gn/T/abnerworks.Typora/image-20180510190700291.png)
- 

## 5、浮动

- 浮动只提升半级别层级

## 6、margin为负值（margin不影响元素位置）

- 负值：将元素边界往里收
- 正值：将元素边界往外扩

