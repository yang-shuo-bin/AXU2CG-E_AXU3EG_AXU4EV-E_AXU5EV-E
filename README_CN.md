# Xilinx Zynq UltraScale+ MPSoC 系列开发板AXU2CG-E、AXU3EG、AXU4EV-E、AXU5EV-E  
***
## 开发板介绍
### 开发板简介
开发板的整个结构，继承了我们一贯的核心板+扩展板的模式来设计的。核心板和扩展板之间使用高速板间连接器连接，底板包含1 路 M.2 接口、1 路 DP 接口、4 路 USB3.0接口、2 路千兆以太网接口、2 路 UART 串口接口、1 路 SD 卡接口、2 个 40 针扩展接口、2路 CAN 总线接口，2 路 RS485 接口，1 路 MIPI 接口和一些按键 LED。
### 关键特性

| 开发板名称        | AXU2CG-E                                                      | AXU3EG                                                        | AXU4EV-E                                                      | AXU5EV-E                                                      |
|--------------|---------------------------------------------------------------|---------------------------------------------------------------|---------------------------------------------------------------|---------------------------------------------------------------|
| 适配的核心板       | ACU2CG                                                        | ACU3EG                                                        | ACU4EV                                                        | ACU5EV                                                        |
| M.2接口        | 1个PCIEx1(ps),速率6Gbps                                          | 1个PCIEx1(ps),速率6Gbps                                          | 1个PCIEx1(ps),速率6Gbps                                          | 1个PCIEx1(ps),速率6Gbps                                          |
| DP显示接口       | 1路mini DP(ps)，最高支持4kx2k@30fps输出                               | 1路mini DP(ps)，最高支持4kx2k@30fps输出                               | 1路mini DP(ps)，最高支持4kx2k@30fps输出                               | 1路mini DP(ps)，最高支持4kx2k@30fps输出                               |
| USB3.0接口     | 4路usb(ps),速率5.0Gbps,扁型 USB 接口(USB Type A)                     | 4路usb(ps),速率5.1Gbps,扁型 USB 接口(USB Type A)                     | 4路usb(ps),速率5.2Gbps,扁型 USB 接口(USB Type A)                     | 4路usb(ps),速率5.3Gbps,扁型 USB 接口(USB Type A)                     |
| 千兆以太网接口      | 2路jl2121,一路ps，一路pl,rgmii接口                                    | 2路jl2121,一路ps，一路pl,rgmii接口                                    | 2路jl2121,一路ps，一路pl,rgmii接口                                    | 2路jl2121,一路ps，一路pl,rgmii接口                                    |
| USB Uart接口   | 2个uart转usb，一个ps，一个pl                                          | 3个uart转usb，一个ps，一个pl                                          | 4个uart转usb，一个ps，一个pl                                          | 5个uart转usb，一个ps，一个pl                                          |
| SD卡槽         | 1个micro型（ps）                                                  | 2个micro型（ps）                                                  | 3个micro型（ps）                                                  | 4个micro型（ps）                                                  |
| 40针扩展口       | 2 个 2.54mm间距,1路5v,2 路3.3v,3 路gnd，IO 口 34 路。扩展口的 IO 电平标准为 3.3V | 2 个 2.54mm间距,1路5v,2 路3.3v,3 路gnd，IO 口 34 路。扩展口的 IO 电平标准为 3.3V | 2 个 2.54mm间距,1路5v,2 路3.3v,3 路gnd，IO 口 34 路。扩展口的 IO 电平标准为 3.3V | 2 个 2.54mm间距,1路5v,2 路3.3v,3 路gnd，IO 口 34 路。扩展口的 IO 电平标准为 3.3V |
| CAN通信接口      | 2 路(ps)                                                       | 2 路(ps)                                                       | 2 路(ps)                                                       | 2 路(ps)                                                       |
| 485通信接口      | 2路(pl)                                                        | 2路(pl)                                                        | 2 路(pl)                                                       | 2 路(pl)                                                       |
| MIPI接口       | 1路(pl),15PIN的FPC连接器，2个lane数据，1对时钟                             | 1个(pl),15PIN的FPC连接器，2个lane数据，2对时钟                             | 1个(pl),15PIN的FPC连接器，2个lane数据，3对时钟                             | 1个(pl),15PIN的FPC连接器，2个lane数据，4对时钟                             |
| RTC实时时钟      | 32.768KHz无源时钟（ps）                                             | 32.768KHz无源时钟（ps）                                             | 32.768KHz无源时钟（ps）                                             | 32.768KHz无源时钟（ps）                                             |
| EEPROM和温度传感器 | 1片 EEROM 4Kbit（2x256x8bit）(ps)，一片LM75温度芯片(ps)，精度为0.5度         | 1片 EEROM 4Kbit（2x256x8bit）(ps)，一片LM75温度芯片(ps)，精度为0.5度         | 1片 EEROM 4Kbit（2x256x8bit）(ps)，一片LM75温度芯片(ps)，精度为0.5度         | 1片 EEROM 4Kbit（2x256x8bit）(ps)，一片LM75温度芯片(ps)，精度为0.5度         |
| LED灯         | 共3个，1个电源，1个pl控制，1个ps控制                                        | 共3个，1个电源，1个pl控制，2个ps控制                                        | 共3个，1个电源，1个pl控制，3个ps控制                                        | 共3个，1个电源，1个pl控制，4个ps控制                                        |
| 按键           | 共3个，1 个复位按键 RESET 和 2 个用户按键                                   | 共3个，1 个复位按键 RESET 和 3 个用户按键                                   | 共3个，1 个复位按键 RESET 和 4 个用户按键                                   | 共3个，1 个复位按键 RESET 和 5 个用户按键                                   |
| 结构尺寸         | 200mm x 111mm                                                 | 200mm x 112mm                                                 | 200mm x 113mm                                                 | 200mm x 114mm                                                 |
| 电源           | 12v/3A                                                        | 12v/3A                                                        | 12v/3A                                                        | 12v/3A                                                        |


### 赠送配件

| Mini USB 线 | 1根 |
|------------|----|
| 12V电源      | 1个 |
| TF卡        | 1个 |
| 散热风扇       | 1个 |
| USB下载器     | 1套 |
| 透明保护板      | 1块 |
| 读卡器        | 1个 |

***
## 官方网站

https://www.alinx.com