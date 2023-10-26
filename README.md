[中文](./README.md) [English](./README_en.md)
# nanoUART-wl 用户手册
* [产品介绍](#产品介绍) 
* [使用说明](#使用说明)
    * [建立无线连接](#建立无线连接)
	* [打开串口工具](#打开串口工具)
* [FAQ](#faq)
	
# 产品介绍
nanoUART-wl-lr是实验室推出的无线远距离串口工具，即插即用，无需驱动，双向通信，最高可支持460800波特率输出，对于某些调试场景如目标始终处于移动状态或者位于高处等，可有效提高开发效率  

<div align=center>
<img src="https://github.com/wuxx/nanoUART-wl-lr/blob/master/doc/nanoUART-wl-top.jpg" width = "500" alt="" align=center />
<img src="https://github.com/wuxx/nanoUART-wl-lr/blob/master/doc/nanoUART-wl-bottom.jpg" width = "500" alt="" align=center />
</div>

# 使用说明
无线串口分为发射机和接收机，将发射机插入PC中，接收机则和目标板连接。 
当发射机插入PC后，设备管理器中会出现虚拟串口设备。  
![usb_cdc_device](https://github.com/wuxx/nanoUART-wl/blob/master/doc/usb_cdc_device.png)  
## 距离说明
无线串口工作频段为2.4GHz，通过外接天线使用，在空旷场地下的实际测试参考数据如下：  
- 外接全向吸盘天线(增益12DBI), 最远通信距离可达150米
- 外接定向雷达天线(增益10DBI), 最远通信距离可达450米
## 接线说明
一般只需连接三根线，GND，TX，RX，注意发送和接收均是针对板子自身而言，例如接收机上标记为TX的引脚，说明是接收机发送，需要接目标板的串口接收。  

## 建立无线连接
发射机和接收机上电之后，均会开始红灯闪烁，当红灯由闪烁变为绿灯常亮后，说明无线连接建立，此时可开始使用无线串口  
## 打开串口工具
推荐使用sscom或者putty连接串口使用，此时使用方法和有线串口一致，在此不再赘述。  
![sscom](https://github.com/wuxx/nanoUART-wl/blob/master/doc/sscom.png)
# FAQ
