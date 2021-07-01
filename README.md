# pSoc6
pSoc6提高实验
基于freeRTOS完成双核 及蓝牙 通信实验，具体为：用一个核通过 CapSense滑条控制 RGBLed 的亮度并显示在 E-INK上，同时将滑条位置信息通过 BLE模块发送给计算机或者手机，另一个核通过 IPC通道获取 RGBLed亮度信息并通过UART发送给计算机。
