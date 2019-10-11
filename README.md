# STM32 IAP Demo

STM32上的IAP程序，主要功能是通过YMODEM协议接收固件并将其写进Flash。此项目来源于STM32官方Demo。

## IAP_Main工程

这个是IAP操作的主程序。


## IAP_Binary_Template工程

它的作用是生成一个xxx.bin固件，用于IAP试验。

使用方法：首先在Keil中编译项目，然后使用脚本IAP_Binary_Template/Utilities/axftobin.bat将Keil编译生成的xxx.axf文件转换为xxx.bin文件


## 支持YMODEM协议的上位机

* SecureCRT
* [开源项目JAVA_YMODEM_FOR_STM32_IAP](https://github.com/FanHongchuang/JAVA_YMODEM_FOR_STM32_IAP)
