感知模块
=====
感知模块做前需了解的信息

目标方向：
-------
	1、混合筛选判断LED位置、亮暗、颜色（光摄像头、距离传感器、建模…）
	2、独立处理图像信息，降低主板运算负担
	3、高灵敏度算法（调整色温、二阀过滤）

图像处理方案（OpenMV）：
-------
![OpenMV](https://cdn.singtown.com/2020/01/OpenMV4-Plus-%E5%BC%95%E8%84%9A%E5%9B%BE.jpg)
独立电源：3.7V锂电池<br>
运算能力：ARM Cortex M7 处理器，480 MHz ，1MB RAM，2 MB flash. 所有的 I/O 引脚输出 3.3V 并且 5V 耐受<br>
可动性：自带2个连接舵机的I/O<br>
电路图：https://dl.singtown.com/schematic/base-32-bit.pdf<br>
处理器手册：https://dl.singtown.com/datasheet/STM32H743II.pdf<br>
基础知识、历程解析：https://book.openmv.cc/ （做前必看，重点图像处理、串口通信）<br>
