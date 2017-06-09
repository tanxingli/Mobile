移动web学习笔记

1、移动端的操作系统：
ios、安卓、黑莓、塞班、windowsphone
2、移动浏览器的内核差不多都是基于webkit
谷歌、safari、uc、QQ、360、百度、猎豹

3、视口
 <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, 
 maximum-scale=1.0, minimum-scale=1.0"> 
 
 viewport：视口属性（ps：只有在移动端该属性才有用）
 name="viewport"---告诉浏览器meta标签设置的是 viewport属性
 content 设置viewport属性值（键和值的方式）
  width=device-width---宽度等于设备的宽度（好处：不用把宽写死，换其他型号手机内容不会溢出）
                    ---宽度不需给单位如px、rem
                    ---设备的屏幕大小比设置的视口大小要大（正常显示）
 user-scalable=no---禁止用户缩放
 initial-scale=1.0---视口默认的缩放比例
 maximum-scale=1.0, minimum-scale=1.0----最大最小缩放值
 
 视口相关网页介绍
 http://www.cnblogs.com/chunyangji/p/5795487.html
 http://www.css88.com/archives/5975
