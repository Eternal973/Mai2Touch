# MaimaiTouch
基于[Mai2Touch](https://github.com/Sucareto/Mai2Touch)使用 Arduino 制作的 maimai 触摸输入和 LED 控制板（837-15070-02）兼容示例程序。  
触摸设备通信数据格式可参考 [MaimaiTouch 数据分析](MaimaiTouch/README.md)  
LED 控制板通信数据格式可参考 [MaimaiLED 数据分析](MaimaiLED/README.md)  

### 待完成：  
- [ ] 收集官方设备(15070-02)与SDEY的通信串口数据
- [ ] 添加顶灯、音响灯的实现

### MaimaiTouch 使用方法：  
- 上传程序
- 打开设备管理器，设置 Arduino 的 COM 号为 COM3
- `GrooveMaster.ini`内，确保`NO_SERIAL 0`
- 启动游戏

### MaimaiLED 使用方法：  
- 上传程序
- 打开设备管理器，设置 Arduino 的 COM 号
- 启动游戏

### 引用库：
- 驱动 mpr121：[Adafruit_MPR121](https://github.com/adafruit/Adafruit_MPR121)

