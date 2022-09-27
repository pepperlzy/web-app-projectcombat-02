# 项目核心

## rem布局首先要进行页面初始化

> 动态获取页面宽度，进行计算，动态设置html的font-size的大小

## flex布局中flex-shrink: 1;沾满剩余宽度的用法

## 移动webapp的图片适配问题

> 通过给他套父盒子做适配，避免后台上传图片大小不一

## 图片裁剪和背景图片裁剪

> 如果是图片则使用 ` object-fit: cover;`
> 
> 如果是背景图片则使用 ` background-size: cover;`

## swiper插件的引用

> 页面中使用多个swiper插件时，给swiper-container添加id避免发生冲突
> 
> 先添加swiper结构再进行页面结构样式的搭建
> 
> 再tab切换栏中切换功能中引入swiper要进行初始化

## 行高  line-height: normal;问题

> 行高默认1.2/normal取决于用户端。桌面浏览器（包括 Firefox）使用默认值，约为1.2，这取决于元素的 font-family。

## 样式重用

> 页面可以中相同布局样式可以定义一个公共结构和样式进行重用

## topbar会员购三个字的处理问题

> 通过将 **会员购**进行定位，单独设置，可以不改变flex布局中所占样式

## iPhone刘海区问题

> 可以给视口标签添加`viewport-fit=cover`
> ```html
    <meta name="viewport" content="width=device-width, viewport-fit=cover,initial-scale=1.0" />
> ```

## 项目效果图

![1660831720059](https://user-images.githubusercontent.com/109357565/192484752-f2a4659e-dca3-4c82-92b7-7c2e762531d6.png)
