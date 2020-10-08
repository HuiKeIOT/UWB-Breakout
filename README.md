# 1 简介  

 UWB模块转接板将必要引脚引出至2.54mm间距的插针上，目的是给UWB模组(包括官方DWM1000以及国产BU01）提供引脚转接功能，防止频繁焊接带来的器件损坏，方便开发者调试使用。

# 2 效果图

![]()

# 3 原理图

![原理图](https://github.com/HuiKeIOT/UWB-Breakout/blob/master/doc/%E5%8E%9F%E7%90%86%E5%9B%BE.png?raw=true)

# 4 引脚定义  

| 引脚  |   定义   |        备注        |
| :---: | :------: | :----------------: |
|  3.3  |  电源正  | 电源输入3.3V，必接 |
|  GND  |  电源负  |     地线，必接     |
|  IRQ  | 中断引脚 | 已接10k拉低，必接  |
|  CLK  | SPI时钟  |        必接        |
| MISO  | SPI引脚  |        必接        |
| MOSI  | SPI引脚  |        必接        |
|  CS   | SPI片选  |        必接        |
|  RST  |  复位脚  |        必接        |
| WAKE  |   唤醒   |        必接        |
|  EXT  | 电源使能 |       非必接       |
| GP4-6 |  IO引脚  |    特殊功能引脚    |

# 5 与其他单片机连接

- 以STM32为例  

![](https://github.com/HuiKeIOT/UWB-Breakout/blob/master/doc/%E6%8E%A5%E7%BA%BF%E5%9B%BE.png?raw=true)

# 6 店铺链接  

- 打开手机淘宝扫一扫

![](https://github.com/HuiKeIOT/UWB-Breakout/blob/master/doc/%E6%89%8B%E6%9C%BA%E6%B7%98%E5%AE%9D%E5%BA%97%E9%93%BA%E9%A6%96%E9%A1%B5_%E9%BB%98%E8%AE%A4%E6%B8%A0%E9%81%93_1556266863340.png?raw=true)

- 电脑版本直接点击[地址](https://item.taobao.com/item.htm?spm=a230r.1.14.16.50cd4148hIobW0&id=617810091798&ns=1&abbucket=4#detail)

