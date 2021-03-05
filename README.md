# HDMI转MIPI屏幕驱动

>基于稚晖君的HDMI-PI项目的东芝TC355870方案，他本人做出了龙迅的方案，但基于龙讯的调性，代码是没有开源的。而东芝方案有一版硬件，软件没有进行相关调试。开源连接：https://github.com/peng-zhihui/HDMI-PI

# 关于硬件和软件

>项目的硬件部分参考了稚晖君的原理图，PCB部分采用核心板加转接板的方式，这样可以灵活匹配不同接口的显示屏。
>项目的软件基于网上代码拼凑，目前已经点亮4款屏幕，代码的状态切换未完善，目前只能在HDMI连接正常情况下上电方可出图像，有兴趣的朋友欢迎一同完善代码。
>文档含很多艰难收集的
>
>2021.01.24 更新了夏普屏的转接板PCB与驱动代码，型号LQ055T3SX02Z，分辨率1080x1920。底板有一点小问题，需要给PA2的排针接口，飞一个1.8v的上拉电阻。

# 交流
感兴趣的可以加QQ群：879256453交流。PS:不是我的群。

# 一些注意事项
> 本仓库的项目是**GPL协议**，不支持任何形式的私自产品化，当然自己DIY是没有任何问题的。
