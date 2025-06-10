# DOIT_AI_BluFi

*   首先致谢虾哥的开源项目：https://github.com/78/xiaozhi-esp32
*   其次致谢：https://github.com/xinnan-tech/xiaozhi-esp32-server


## 项目简介
ESP32-C3作为主控，驱动240*240屏幕，使用blufi一键配网绑定，软件硬件全开源

特色：

1. 实现通过蓝牙BluFi的方式给小智配网。
2. 小程序自动添加设备。
3. 完全兼容 xiaozhi-esp32-server.


## 效果视频

## 使用说明
1. 获取代码：git clone https://github.com/SmartArduino/DOIT_AI_BluFi.git
2. 使用vscode打开工程（需espidf版本>5.3.2,建议使用5.4.1版本）,设置目标芯片为esp32c3，命令：idf.py set-target esp32c3
3. 编译工程：idf.py build
4. 修改menuconfig:idf.py menuconfig
    将Xiaozhi Assistant->Board Type设置为doit-ai-02-kit-lcd
5. 烧录代码:idf.py flash
6. 使用小程序小智小助理blufi配网
![alt text](image1.jpg)


## 技术支持
![alt text](image.png)

## 购买链接
购买地址：https://item.taobao.com/item.htm?id=904320615994
