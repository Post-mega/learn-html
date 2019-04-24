# CSS 选择器

选择器优先记顺序由低到高依次为：
0. 通配符 *
1. 标签选择器
2. 类名选择器
3. ID 选择器
4. 标签内 style
5. !important

## 通配选择器 " * "

对所以标签都有用

## 标签选择器

直接使用标签名称，例如所有的 div 标签红色背景，所有的 p 标签蓝色背景

```
div {
    background-color: red;
}
p {
    background-color: blue;
}
```

## class 选择器

```
.item {
   /*.开头，对使用该class的标签有用*/
}
```

## ID 选择器

```
#btn {
    /*#开头对使用该id的标签有效果*/
}
```

## 双（多）选择器

```
.item-email.item-name {
    /*对两个都进行设置，中间不加空格*/
}
```

##父子选择器

```
.list .item {
    /*中间有空格，对list下的item标签进行设置*/
}
```

# CSS 常用样式

## 1、尺寸定义

在 CSS 中，每一个元素的都被当做一个盒子，简称为盒模型。每个盒子都有 Margin(外边距)，用来清除边框外的区域，外边距是透明的；Border(边框)，用来围绕在内边距和内容外的边框；Padding(内边距)，用来清除内容周围的区域，内边距是透明的；Content(内容)，盒子的内容，显示文本和图像。

### width 宽度
宽度的单位有 px，vh，%

### max-width 最大宽度


### min-width 最小宽度


### height 高度

### max-height 最大高度

默认值是 0 

### min-height 最小高度



### margin 外边距

### padding 内边距

### border 定义边框样式
可以分为 border-width、border-style、border-color，这三个参数都可以单独定义

### box-sizing 盒模型尺寸计算方式

## 2、位置定义

| 属性名称 | 描述 | CSS 版本 |
| :--- | :--- | :---: |
|float |漂浮|
|
|position |定位方式|
|
|top |距离顶部|
|
|left |左侧距离|
|
|right |右侧距离|
|
|bottom |底部距离|
|
|z-index |垂直距离|
|

## 3、文字修饰

| 属性名称 | 描述 | CSS 版本 |
| :--- | :--- | :---: |
|font-size | 文字大小 |
|
|text-align | 文本对齐 |
|
|text-decoration | 文本修饰 |
|
|letter-spacing | 文字间隔 |
|
|text-indent | 文字缩进 |
|
|line-height | 行高 |
|

## 4、背景颜色

| 属性名称 | 描述 | CSS 版本 |
| :--- | :--- | :---: |
|background-color |背景颜色| |
|background-image |背景图片| |
|background-repeat |背景重复| |
|background-size |背景图片大小| |

## 5、动画属性

| 属性名称 | 描述 | CSS 版本 |
| :--- | :--- | :---: |
|@keyframes	| 定义一个动画,@keyframes定义的动画名称用来被animation-name所使用。 | 3 |
|animation | 复合属性。检索或设置对象所应用的动画特效。	| 3 |
|animation-name	|检索或设置对象所应用的动画名称 ,必须与规则@keyframes配合使用，因为动画名称由@keyframes定义	|3|
|animation-duration	|检索或设置对象动画的持续时间	|3|
|animation-timing-function	|检索或设置对象动画的过渡类型	|3|
|animation-delay	|检索或设置对象动画的延迟时间	|3|
|animation-iteration-count	|检索或设置对象动画的循环次数	|3|
|animation-direction	|检索或设置对象动画在循环中是否反向运动	|3|
|animation-play-state	|检索或设置对象动画的状态	|3|
