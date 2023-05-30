## 魅族pro5

### 串口控制开关器件 TSU6721YFFR
```
https://html.alldatasheetcn.com/html-pdf/539577/TI/TSU6721YFFR/28/1/TSU6721YFFR.html
I2C 接口控制，
SDA -  GPD5_2
SCL -   GPD5_3
INT -   GPA0_1 设备插拔中断
具体控制看不懂。。。
串口接在type-c USB接口上
当用2.0usb线时 ：
白色线：DN - DM  - TxD - AP_TXD - GPD1_5
绿色线：DP -  DP   - RxD - AP_RXD - GPD1_4
```

### USB控制器 FUSB302UCX 和 TSU6721YFFR 在一组I2C接口上，地址不同
```
https://pdf1.alldatasheetcn.com/datasheet-pdf/view/1082784/ONSEMI/FUSB302UCX.html
```