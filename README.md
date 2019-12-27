# [CH643](https://github.com/SoCXin/CH643)

* [WCH](http://www.wch.cn/)：[RISC-V](https://github.com/SoCXin/RISC-V)
* [L1R2](https://github.com/SoCXin/Level): 48 MHz

## [简介](https://github.com/SoCXin/CH643/wiki)

[CH643](https://www.wch.cn/products/CH643.html)是基于青稞RISC-V内核设计的RGB显示驱动工业级微控制器。CH643内置USB和PD PHY，支持USB Host主机和USB Device设备功能、USB PD及type C快充功能、PWM驱动RGB LED功能，内置可编程协议I/O 控制器，提供了OPA运放、CMP电压比较器、USART串口、I2C、SPI、定时器、12位ADC、Touchkey等丰富外设资源。

``` mermaid
gantt
    title CH643 SDK
    dateFormat  YYYY-MM-DD
    section Mainline Release
    v1.0           :a1, 2024-06-01, 2024-09-30
```

### 关键特性

* 48MHz RISC-V4C
* 20KB SRAM + 62KB Flash
* 8路通用DMA控制器
* 可编程协议I/O控制器PIOC
* 多组运放OPA/PGA/电压比较器
* 多组模拟电压比较器CMP
* RGB三色LED脉冲宽度调制LEDPWM
* 多路外部12位ADC转换通道，多路TouchKey通道检测
* 多组定时器，包括高级定时器、通用定时器、看门狗定时器以及系统时基定时器
* 多组USART串口：支持LIN和ISO7816
* 1个I2C接口和1个SPI接口
* USB2.0全速控制器及PHY
* USB PD和Type C控制器及PHY
* 快速GPIO端口，支持24个外部中断
* 封装：QFN80、LQFP64、LQFP48、QSOP28

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)
* [mounriver开发环境](http://www.mounriver.com/download)

## [选型建议](https://github.com/SoCXin)

[CH643](https://github.com/SoCXin/CH643) 基于[QingKe](https://www.wch.cn/products/QingKe.html)内核

