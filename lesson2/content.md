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

width 宽度

height 高度

margin 外边距

padding 内边距

border 定义边框样式，可以分为 border-width、border-style、border-color，这三个参数都可以单独定义

box-sizing 盒模型尺寸计算方式

## 2、位置定义

float 漂浮

position 定位方式

top 距离顶部

left 左侧距离

right 右侧距离

bottom 底部距离

z-index 垂直距离

## 3、文字修饰

font-size 文字大小

text-align 文本对齐

text-decoration 文本修饰

letter-spacing 文字间隔

text-indent 文字缩进

line-height 行高

## 4、背景颜色

background-color 背景颜色

background-image 背景图片

background-repeat 背景重复

background-size 背景图片大小

## 5、其他类型

box-shadow
