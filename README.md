# Commodore

```
Independent research and development
Project：UAV_Control_System
Author：Honglin Chu,  Yuhao, Hu
Version：1.0
                                     
      _____                                        __    
     / ____\                                      / /
    / /                                          / /      _    
   / /   _____  ________  ________  _____  _____/ /____  / \_______ 
  / /   / ___ \/ __  __ \/ __  __ \/ ___ \/ ___  / ___ \/ ___/ ___ \
 / /___/ /__/ / / / / / / / / / / / /__/ / /__/ / /__/ / /  / /____/
 \____/\_____/_/ /_/ /_/_/ /_/ / /\_____/\_____/\_____/_/   \_____\
                                                                                                                
Date:2016.11
```
## Hardware
![img](./img/四轴项目.png)

## Software
![img](./img/系统初始化.png)

## Description

1 https://www.bilibili.com/video/BV1KW411N7hR

2 https://www.bilibili.com/video/BV1CW411P7K2

3 https://www.bilibili.com/video/BV1KW411N7eC

## Tree

```
├── CORE
│   ├── core_cm3.c
│   ├── core_cm3.h
│   ├── startup_stm32f10x_hd.s
│   └── startup_stm32f10x_md.s
├── HARDWARE
│   ├── ADNS3080
│   ├── Attitude_Count
│   ├── BMP085
│   ├── Data_ReadWrite
│   ├── Data_Trans
│   ├── DMA_Config
│   ├── EEPROM
│   ├── FLASH
│   ├── FLOW
│   ├── Height
│   ├── HMC5883L
│   ├── LED
│   ├── MOTOR
│   ├── MPU6050
│   ├── PID_Control
│   ├── PWM_Capture
│   ├── RC_Config
│   ├── SPI
│   ├── TIM4
│   ├── ULTRASONIC
│   └── USART1
├── OBJ
│   └── EXTI.hex
├── STM32F10x_FWLib
│   ├── inc
│   └── src
├── SYSTEM
│   ├── delay
│   ├── sys
│   └── usart
├── UCOSII
│   ├── CONFIG
│   ├── CORE
│   └── PORT
└── USER
    ├── Includes.h
    ├── JLinkSettings.ini
    ├── main.c
    ├── QuadCopter.uvoptx
    ├── QuadCopter.uvprojx
    ├── stm32f10x_conf.h
    ├── stm32f10x.h
    ├── stm32f10x_it.c
    ├── stm32f10x_it.h
    ├── system_stm32f10x.c
    └── system_stm32f10x.h

```
