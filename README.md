# README


### 魅族PRO5 的适配

```
1.用大佬们原来的代码编译出来而已，开始不会有任何实质性的修改
2.在过程中学习适配，期望后续会有有用的修改
```


#### 计划工作事项


- [x] 1.编译 ResurrectionRemix nougat
- [x] 2.编译 LineageOS cm-14.1
- [ ] 3.减少 proprietary blobs
- [ ] 4.适配 halium-7.1


#### 奢望工作事项

```
1.升级内核版本
2.主线内核
3.适配高版本安卓
```




### 非常感谢

faust93、LINGJP、Samsung Galaxy S6 适配者


### 信息收集罗列

| 硬件/功能      | 型号     | 3.10驱动源码  |主线内核|
| -------- | -------- | -------- | -------- |
| cpu      | Exynos 7420     | -     | https://github.com/PabloPL/linux/tree/exynos7420     |
| 后摄像头  | IMX230     | -     | https://github.com/akhilxavi/debian4.14-imx230driver/blob/master/imx230.c    |
| 前摄像头  | OV5670     | -     | drivers/media/i2c/ov5670.c    |
| NFC      | NXP PN65T NFC 芯片、pn547    | LineageOS/android_external_libnfc-nxp     | -     |
| 蓝牙     | -     | -     | -     |
| wifi     | -     | -     | -     |
| 内存     | -     | -     | -     |
| 屏幕     | CONFIG_MEIZU_DECON_LCD_S6E3FA3     | -     | https://gitlab.com/msm8996-mainline/linux/-/blob/msm8996-staging/drivers/gpu/drm/panel/panel-samsung-s6e3fa3.c     |
| 声音     | WM8998     | -     | sound/soc/codecs/wm8998.c     |
| 声音     | ESS9018K2M     | -     | -     |
| 声音     | tfa9890     | android_hardware_samsung_slsi/cm-14.1/tfa9890     | -     |
| 充电IC     | -     | -     | -     |
| gps     | -     | -     | -     |
| usb net     | -     | -     | -     |
| usb otg     | -     | -     | -     |
| gpu     | Mali-T760     | -     | linux 5.2/panfrost  mesa/19.2-21.1      |
| Mobile Data     | -     | -     | -     |
| SMS      | -     | -     | -     |
| Calls      | -     | -     | -     |
| 背光控制      | -     | -     | -     |
| 指纹      | Fingerprint FPC1150     | android_device_meizu_m86/cm-14.1-latest/libfprint     | -     |
| 震动      | -     | √     | -     |
| 光线感应      | -     | -     | -     |
| 距离感应      | -     | -     | -     |
| 陀螺仪      | -     | -     | -     |
| bootloader      | -     | -     | https://github.com/kaleao/exynos/tree/master/kaleao/system/u-boot  https://github.com/suxiaocheng/exynos7_u_f_s    |




