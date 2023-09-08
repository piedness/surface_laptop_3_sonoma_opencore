# surface_laptop_3_sonoma_opencore0.9.4

### 适用于 surface laptop 3 1035G7

### Macos 版本：macOS Sonoma 14beta 7（23A5337a）
### opencore 版本：0.9.4

## 能用：
- cpu
- igpu 显存1536MB
- 触控板
- 扬声器
- 电池
- 触摸屏
- 蓝牙
- 内置摄像头
- 3.5mm耳机
- 亮度调节
- wifi
- 键盘背光
- CPU变频
- 睡眠唤醒

## bug：
- 睡眠后唤醒很慢、
- hidpi开启后花屏
- cpu温度较高

## 待测试
- usb 3.0 
- usb type-c
- 原生电源管理
- 随航




## 参考网址：
- [https://dortania.github.io/OpenCore-Install-Guide/]
- [https://github.com/acidanthera/OpenCorePkg]
## config 编辑
- [https://opencore.slowgeek.com/]
- [https://github.com/demonxjj/ocat]

## 注意事项
- Lilu.kext 须使用 v1.6.6 版本 （macOS Sonoma 14beta 7（23A5337a））

## 23/9/6
- 核显驱动教程
[https://www.rstk.cn/news/1278886.html?action=onClick]
[http://www.imacosx.cn/6546.html]
[https://zhuanlan.zhihu.com/p/568909859]
- OC引导参数设定
[https://zhuanlan.zhihu.com/p/543147047?utm_id=0]
[http://hktiankong.cn/hepg/2022-12-15/1.html]

## 23/9.8
- 帧缓冲设置：
  - framebuffer-stolenmem 设置128M（00000001）及以上时，鼠标不会花屏
  - framebuffer-unifiedmem 设置2048MB（00000080），再开启hidpi 会花屏
  - 








## 持续更新中...
