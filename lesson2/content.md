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
