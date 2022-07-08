# 实验六：信号失真度测量装置

## 任务

- 设计制作信号失真度测量装置
- 对来自函数/任意波形发生器的周期信号（输入信号）进行采集分析
- 测得输入信号的总谐波失真THD（以下简称为失真度）
- 用多孔板、连孔板或印制PCB方式制作电路板
- 单片机不限
- 用开发板测量和显示

## 分工

- 硬件：Cedar
    - 将输入信号电压大于0V小于3.3V
    - 使用OP37放大约5倍
    - 注意电位器置于下拉电阻，便于调节
- 软件：Ren,Wind

## 基本要求

- 输入信号峰峰值300mV~600mV
- 输入信号基频1kHz
- 输入信号失真度范围5%~50%
- 要求对输入信号失真度测量误差绝对值$\delta=|THD_x-THD_0|<=5%$
- 显示失真度测量值$THD_x$
- 失真度测量与显示用时不超过10秒
