# 前言
1、本仓库所有的RP都是使用Axure

2、本仓库包含的内容有 RP、PPT **(xxx.pptx在合肥工业大学学术报告厅演讲)** 、PSD、线路图、文档、方案

3、可能比较乱，我只选出还能看的设计在.md文件中展示

## 1、流程表达Custom
其实这样写不严谨，但是省时间，表达的效果要更好一点

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/ros.png)

## 2、客户端设计第三版
在B端的项目里面过多的以C端的思维去设计，结果管理端不像管理端、APP不像APP，后续会有第四版，用设计B端的设计思维去设计

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/%E5%AE%A2%E6%88%B7%E7%AB%AF3.png)

## 3、客户端设计第四版
加入IM

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/%E5%AE%A2%E6%88%B7%E7%AB%AF4.0.png)

使用说明

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/%E5%AE%A2%E6%88%B7%E7%AB%AF4.0%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.png)

## 4、客户端设计第四-1版
删去IM，加入server主动触发

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/%E5%AE%A2%E6%88%B7%E7%AB%AF4.1.png)

使用说明

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/%E5%AE%A2%E6%88%B7%E7%AB%AF4.1%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.png)

## 5、设备端设计第四版

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/%E8%AE%BE%E5%A4%87%E7%AB%AF4.0.png)

## 6、应用场景Custom
为什么设计这样的图？是因为我要和非行业的人去沟通，我要告诉他机器是怎么运行的，非行业客户不会告诉你我的需求是什么，而是需要我们去发现，去提、去尝试，比如，“你看，如果这样做怎么样？”，其实前者是在一个大的需求里面逐个去优化的过程

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/%E6%A8%A1%E5%9E%8B1.png)

## 7、验证码业务
两个区别：

1、设备与server之间的通信是基于node，非tcp/udp/http

2、这里客户端与设备的交互统一交由server，其中客户端A与设备A之间的直线只是为了说明人从客户端A读取验证码在设备端进行输入设备端从server中得到验证从而继续后面的业务

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/%E9%AA%8C%E8%AF%81%E7%A0%81%E6%97%B6%E5%BA%8F%E5%9B%BE.png)

## 8、管理端
管理端1.0设计，基于jfx

![custom image](https://github.com/whsgzcy/Design_To_MySelf_ATW/blob/master/images/server.png)
