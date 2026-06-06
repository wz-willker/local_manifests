## 如何使用
```
repo init -u https://github.com/LineageOS/android.git -b lineage-23.2 --git-lfs --no-clone-bundle --depth=1
cd .repo
git clone https://github.com/wz-willker/local_manifests.git
cd ..
repo sync --no-tags
```
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
