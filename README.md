# STM32F4-FreeRTOS
learn STM32F4 FreeRTOS
1.从空工程建立STM32F407工程
2.从空工程建立FreeRTOS工程
3.从STM32F407工程建立FreeRTOS工程
4.由工程模板进行实验建立实验工程

实验工程
1. 移植。点灯
2. 中断。按键中断
3. 任务添加删除。 

知识点的关键字记录
系统配置文件：FreeRTOSConfig.h
FreeRTOS.h
delay_us()和delay_xms()不会导致任务切换，使用 delay_ms()的时候就会导致任务切换；
“config”宏和“INCLUDE_”宏，用来完成 FreeRTOS 的配置和裁剪
移植实践:1..lcf配置。2.源码文件。3.头文件路径。
xxHook：钩子函数、回调函数
