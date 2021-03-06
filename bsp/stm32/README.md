# STM32 BSP 说明

STM32 系列 BSP 目前支持情况如下表所示：

| BSP 文件夹名称       | 开发板名称                 |
|:------------------------- |:-------------------------- |
| **F0 系列** |  |
| [stm32f091-nucleo](stm32f091-nucleo/) | ST 官方 stm32f091-nucleo 开发板 |
| **F1 系列** |  |
| [stm32f103-atk-nano](stm32f103-atk-nano/)        | 正点原子 F103 NANO 开发板  |
| [stm32f103-fire-arbitrary](stm32f103-fire-arbitrary/)  | 野火 F103  霸道开发板      |
| **F4 系列** |  |
| [stm32f407-st-discovery](stm32f407-st-discovery/) | ST 官方 stm32f407-discovery 开发板 |
| [stm32f407-atk-explorer](stm32f407-atk-explorer/)    | 正点原子 F407 探索者开发板 |
| [stm32f429-atk-apollo](stm32f429-atk-apollo/)      | 正点原子 F429 阿波罗开发板 |
| [stm32f429-fire-challenger](stm32f429-fire-challenger/) | 野火 F429 挑战者开发板     |
| [stm32f429-armfly-v6](stm32f429-armfly-v6) | 安富莱 f429-v6 开发板 |
| **F7 系列** |  |
| [stm32f767-atk-apollo](stm32f767-atk-apollo) | 正点原子 F767 阿波罗开发板 |
| [stm32f767-fire-challenger](stm32f767-fire-challenger/) | 野火 F767 挑战者开发板 |
| **L4 系列** |  |
| [stm32l475-atk-pandora](stm32l475-atk-pandora/) | 正点原子 L475 潘多拉 IoT 开发板    |

可以通过阅读相应 BSP 下的 README 来快速上手，如果想要使用 BSP 更多功能可参考 docs 文件夹下提供的说明文档，如下表所示：

| **BSP 使用教程** | **简介**                                          |
|:-------------------- |:------------------------------------------------- |
| [外设驱动使用教程](docs/STM32系列BSP外设驱动使用教程.md) | 讲解 BSP 上更多外设驱动的使用方法 |
| [外设驱动介绍与应用](docs/STM32系列驱动介绍.md) | 讲解 STM32 系列 BSP 驱动的支持情况，以及如何利用驱动框架开发应用程序 |
| **BSP 制作与提交** | **简介**                                     |
| [BSP 制作教程](docs/STM32系列BSP制作教程.md) | 讲解 STM32 系列 BSP 的制作方法，以及在制作 BSP 和提交 BSP 时应当遵守的规范 |
| [外设驱动添加指南](docs/STM32系列外设驱动添加指南.md) | 讲解 BSP 添加更多设备驱动的方法 |
