# GPS轨迹重现项目

>关于我，欢迎关注  
项目地址： [Github](https://github.com/shlllshlll/GPSLoc)  
我的小站： [SHLLL的小站](http://shlll.me)  
我的博客： [SHLLL's blog](https://shlllshlll.github.io/)

本项目是电子信息系统综合设计中运动参数提取与轨迹重现实验的实现。为完成实验要求，我们开发了以下几个项目：

1. 基于LeafletJS的GPS轨迹重现的WEB端  
2. 基于Qt WebEngine的桌面端程序  
3. 基于NodeJS和MySQL数据库的地图离线服务器  

## GPS轨迹重现WEB版
![项目效果展示](https://i.loli.net/2017/11/13/5a09648b66c54.gif "GPS轨迹重现效果")
使用LeafletJS为基础，并全面扩展了LeafletJS的功能，实现了读取GPS数据并重现轨迹的功能。

## GPS轨迹重现桌面版
![项目效果展示](https://i.loli.net/2017/11/13/5a0967937a0a4.gif "GPS轨迹重现效果")
基于Qt5的QWebEngineWidget实现了一个Windows客户端，从而使得不需要浏览器环境即可运行轨迹重现项目。

## 本地离线地图服务器
基于Node.JS实现的离线地图服务端，读取存储至MySQL中的离线瓦片地图数据，并家庭本地端口实现本地服务器。

## 总结
通过以上几个项目，我们完整的实现了从GPS数据读取到轨迹重现再到离线地图加载等各个功能，较为完整的完成了实验。



