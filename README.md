## 如何使用
```
git clone https://github.com/wz-willker/LineageOS.git
cd LineageOS/src
repo init -u https://github.com/LineageOS/android.git -b lineage-23.2 --git-lfs --no-clone-bundle --depth=1
repo sync --no-tags
```
## 相较官方改动
### 通用
- 使用 GrapheneOS 提供的网络验证地址
- 启用 microg 签名伪装
- 修复支付宝聊天页面闪退
- 添加 CatShare
- 添加人脸解锁
- 调整 5G 信号显示阈值
- 更换 NTP 服务器为 pool.ntp.org
### Redmi Note 12 Turbo
- 还原内核 GKI 兼容性
- 修改内核名称为 KMI 标准版本号
- 修改设备指纹以匹配系统版本
- 内置假小米安全中心以伪装设备可信
- 适配 Droidspaces
- 合并 [LineageOS Qcom](https://github.com/LineageOS/android_kernel_qcom_sm8450) 和 [AOSP android12-5.10-lts](https://android.googlesource.com/kernel/common/+/refs/heads/android12-5.10-lts) 最新内核更新
- 添加 OpenEUICC（实体 esim 支持）
- 替换相机为 MIUI 相机
### Xiaomi Pad 5
- 移除 KernelSU-Next 和 SUSFS
- 修改设备指纹以匹配系统版本
- 内置假小米安全中心以伪装设备可信
- 内置 ReSukiSU
### Google Pixel 7a
- 修改设备指纹以匹配系统版本
- 替换相机为 Pixel 相机
- 添加 Pixel 人脸解锁
## 更新日志
- [Redmi Note 12 Turbo](docs/changelog_marble.md)
- [Xiaomi Pad 5](docs/changelog_nabu.md)
## 鸣谢
### [LineageOS](https://github.com/LineageOS)
- 一切的开始
### [ravindu644](https://github.com/ravindu644)
- [Droidspaces](https://github.com/ravindu644/Droidspaces-OSS)
### [ReSukiSU](https://github.com/ReSukiSU/ReSukiSU)
- 集成给非 GKI 内核
### [Pzqqt](https://github.com/Pzqqt)
- [还原 sm8450 内核 GKI 兼容性](https://t.me/pzqqt_c/6283)
### [WeiguangTWK & Project NH](https://github.com/WeiguangTWK)
- [部分补丁来源](https://github.com/WeiguangTWK/patches_for_build_marble_AOSP)
- [伪造小米安全中心](https://github.com/WeiguangTWK/android_platform_packages_apps_MiuiSecurityCenter)
### [GrapheneOS](https://github.com/GrapheneOS)
- Captive Portal 服务器
### [AviumUI](https://github.com/AviumUI)
- [CatShare](https://github.com/AviumUI/android_packages_apps_CatShare)（[源码](https://github.com/Ruyue-Kinsenka/CatShare)）
- [ParanoidSense（人脸识别）](https://github.com/AviumUI/android_packages_apps_ParanoidSense)
### [Francescodario Cuzzocrea](https://github.com/fcuzzocrea)
- [为 LineageOS 适配人脸识别](https://review.lineageos.org/q/topic:%2223fu%22)
### [OpenEUICC](https://gitea.angry.im/PeterCxy/OpenEUICC)
- esim 支持
### [chaitanya](https://github.com/Chaitanyakm)
- [marble MIUI 相机](https://github.com/Chaitanyakm/device_xiaomi_miuicamera-marble)
### [克莱德](https://sspai.com/u/clyde/updates)
- [国内 5G 信号阈值调整](https://sspai.com/post/78200)
### [NTP Pool Project](pool.ntp.org)
- NTP 服务器
### [crDroid Android](https://github.com/crdroidandroid)
- [Pixel 相机](https://gitlab.com/crdroidandroid/proprietary_vendor_google_camera)
- [Pixel 人脸解锁](https://gitlab.com/crdroidandroid/proprietary_vendor_google_faceunlock)
## 特别鸣谢
- [Gemini](https://gemini.google.com/)
