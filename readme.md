﻿这是主控固件裸机源代码，裸机指没有使用实时操作系统RTOS。由于没有使用RTOS，所以代码更加简单明了，适合初学者使用。

本次(V4.1）更新(2014.9.20)：
        1.增加电池电压监测校准，具体校准方式见源码battery.c电池检测初始化部分
        2.增加平衡误差调节，具体调节方式见源码receive部分的注释
