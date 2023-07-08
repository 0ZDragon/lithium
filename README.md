# lithium

本项目用于收集小米MIX的各种刷机文件

大部分文件来源于[电报群](https://t.me/xdamimix/)<br>

## Recovery

最后更新：```2023年 07月 08日 星期六 10:32:08 CST```

最新的Recovery可以在[电报群的这里](https://t.me/xdamimix/75787)找到

### 为什么需要最新的 Recovery

因为过时的 Recovery 无法刷入 Android 13

### 说明

128GB的型号只能使用[这个TWRP](https://drive.google.com/file/d/1WiXoB5bmM6Yj-dfque7tMVlDJVmrA1SY/view?usp=sharing)，也就是```lithium-twrp-3.7.0_9-0.img```，无法解密内置存储

256GB的型号可以使用：

[TWRP](https://drive.google.com/file/d/1SNKmnLlpDaIwFH2yPr9MH7-mhEwdpEph/view?usp=sharing)，也就是```lithium-twrp-3.7.0_12-0.img```

或者[橙狐](https://drive.google.com/file/d/1iAMBOgxZoAAGXPaZKyvikKEpi4JCtgx5/view?usp=sharing)，也就是```OrangeFox-R11.1-12.1-Unofficial-lithium.zip```

### 刷入方式

```
fastboot flash recovery twrp.img
```

对于橙狐，最好是先刷入TWRP，然后再刷

```
adb sideload OrangeFox-R11.1-12.1-Unofficial-lithium.zip
```

## 官方 MIUI 系统包

[卡刷包](https://drive.google.com/file/d/1iAMBOgxZoAAGXPaZKyvikKEpi4JCtgx5/view?usp=sharing)<br>

6e058c6d8fb8ddbb45256e2cd0877709  miui_MIMIXGlobal_V11.0.2.0.OAHMIXM_6e058c6d8f_8.0.zip

[线刷包](https://bigota.d.miui.com/V11.0.2.0.OAHMIXM/lithium_global_images_V11.0.2.0.OAHMIXM_20191023.0000.00_8.0_global_3454b31c75.tgz)

3454b31c7563db73fbe5eaf58e05eea0  lithium_global_images_V11.0.2.0.OAHMIXM_20191023.0000.00_8.0_global_3454b31c75.tgz

## 类原生

制作：inky

电报：[Nicholas Magill](https://t.me/Inkypen)

GitHub：[Inkypen79](https://github.com/Inkypen79)

crDroid：[crDroidAndroid-13.0-20230602-lithium-v9.5.zip](https://drive.google.com/file/d/1wTpOsuvA2wd1YBvUDJ1QceknDcJxgiTC/view?usp=sharing)，[原链接](https://t.me/xdamimix/76041)

Rising：Here is the latest Rising (with gapps) build for you with the proximity fixes.
[risingOS-v1.1-Babylon-202306012112-lithium-GAPPS-COMMUNITY.zip](https://drive.google.com/file/d/1WyvvL3GjSkXiCMIvaRrt5HQEYZvrOUmL/view?usp=sharing)，[原链接](https://t.me/xdamimix/76003)


