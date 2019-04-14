# 简介
这个项目收集了一些简单的自定义View，这些View都非常基础，并没有很多复杂的逻辑，适合学习自定义View的新手拿来练手，熟悉Canvas、Paint类的一些API操作。

# 每个View简介
## TowSideProgressBar
这是一个向两边滑动的水平进度条，与系统自带的水平进度条从左向右滑动相比，该View是在控件中间处，分别向左右两边滑动的。点击查看设计思路：[Android自定义View分享——一个水平的进度条](http://blog.csdn.net/u010707039/article/details/52836926)。如下所示是效果图：

![两边滚动的进度条图片](https://raw.githubusercontent.com/JaffarOu/SimpleCustomView/master/PictureInReadMe/TowSideProgressBar.gif)

## TemperatureProgress
这是一个圆形的进度条，用来模拟一些天气类App显示温度用的圆形View。点击查看设计思路：[Android自定义View分享——一个圆形温度显示器](http://blog.csdn.net/u010707039/article/details/52838798)。如下所示是效果图：

![圆形温度进度条图片](https://raw.githubusercontent.com/JaffarOu/SimpleCustomView/master/PictureInReadMe/TemperatureProgress.gif)

## MergePictureView
这是一个仿微信朋友圈合并图片效果的View，如下图所示，第一张图是我做的效果（这是四个MergePictureView，不是一个），第二张是朋友圈的截图

点击查看设计思路：[Android自定义View分享——仿微信朋友圈图片合并效果](http://blog.csdn.net/u010707039/article/details/52846116)

![图片合并View](https://raw.githubusercontent.com/JaffarOu/SimpleCustomView/master/PictureInReadMe/mergePicture.jpg)
![朋友圈截图](https://raw.githubusercontent.com/JaffarOu/SimpleCustomView/master/PictureInReadMe/pengyouquan.png)

## CLockView
这是一个时钟盘，它可以是静止的也可以是动态的，对外提供方法控制启动/暂停，与很多时钟盘不同的是，这个只有时针分针，“秒”变动效果通过弧线来展示。点击查看设计思路：[Android自定义View分享——一个时钟](http://blog.csdn.net/u010707039/article/details/52901101)。如下所示是效果图。

![时钟盘](https://raw.githubusercontent.com/JaffarOu/SimpleCustomView/master/PictureInReadMe/ClockView.gif)

## GramophoneView
仿网易云音乐留声机效果，具有“播放”/“暂停”两个状态。对外提供接口可设置图片半径，可更改图片，可更改整个圆形旋转速度。点击查看设计思路：[Android自定义View分享——仿网易云音乐留声机效果](http://blog.csdn.net/u010707039/article/details/78878324)。如下所示动态效果：

![留声机](https://raw.githubusercontent.com/JaffarOu/SimpleCustomView/master/PictureInReadMe/GramophoneView.gif)
