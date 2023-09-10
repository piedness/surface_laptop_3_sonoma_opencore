# surface_laptop_3_sonoma_opencore

### 适用于 surface laptop 3 1035G7

### Macos 版本：macOS Sonoma 14beta 7（23A5337a）
### opencore 版本：0.9.4

## 注意事项：    
- Lilu.kext 须使用 v1.6.6 版本 （macOS Sonoma 14beta 7（23A5337a）），原因未知


## 能用：
- cpu
- igpu 显存1536MB，解码正常
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
- hidpi ( 1368 x 912 )



## 不完美：
- 睡眠后唤醒很慢
- cpu温度较高
- usb 未定制
- 鼠标图标显示不全


## 待测试
- usb 3.0 
- usb type-c
- 随航


## config 编辑

- boot-args：
  - alcid=35
  - -noDC9
  - igfxonln=1


- DP ：
  - 缓冲帧设置：
    - AAPL,ig-platform-id: 0000528A
    - framebuffer-patch-enable：01000000
    - framebuffer-stolenmem：0000B003
    - framebuffer-fbmem：00009000
 
  - 修复设置：
    - GraphicsBacklightSetup-0：0000010000000000AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA00000000000000000000000000000000
    - GraphicsDisplaySetup：0000010000000000040000008C0A00000100000000000100000003000000906C8A0F00000000000A0000400600005000000000000000000000002E000000000000000000000008000000200000000120000000080000000000010001000000000001000000040000000000000101000000000000000000400B000008070000002D0000010000000000000000
    - enable-hdmi20: 01000000
    - enable-dpcd-max-link-rate-fix: 01000000
    - dpcd-max-link-rate: 14000000
    - igfxfw: 02000000






## 参考网址：
- 下载：
  - [https://github.com/demonxjj/ocat]
  - [https://github.com/acidanthera/OpenCorePkg]
    
- 验证plist：
  - [https://opencore.slowgeek.com/]
    
 - 其他教程：
   - [https://dortania.github.io/OpenCore-Install-Guide/]
   - [https://dortania.github.io/OpenCore-Post-Install/]
   - [https://www.rstk.cn/news/1278886.html?action=onClick]
   - [https://zhuanlan.zhihu.com/p/568909859]
   - [https://zhuanlan.zhihu.com/p/543147047?utm_id=0]
   - [http://hktiankong.cn/hepg/2022-12-15/1.html]
   - [https://github.com/acidanthera/WhateverGreen/blob/master/Manual/FAQ.IntelHD.cn.md]
   - [http://imacos.top/2020/09/03/2216/]
   - [https://blog.daliansky.net/OpenCore-BootLoader.html]

















## 持续更新中...
