# BongoCat Counter 更新包

这个仓库仅用于发布 BongoCat Counter 的 Windows 安装包和 Tauri 自动更新文件（`latest.json`、安装包及 `.sig` 签名）。它不包含应用源码，也不包含第三方社区皮肤。

首次启用自动更新，请从 [Releases](https://github.com/PLA0185/BongoCat-Counter-Updates/releases) 手动安装 v1.2.3 或更新版本；更早版本没有更新器，无法自行升级。此后可在软件的“偏好设置 → 通用设置”开启或关闭自动检查，并在“关于”中手动检查更新。更新包由应用内置的公钥验证，签名私钥不会上传到此仓库。

安装包未经过 Windows 代码签名，系统可能显示 SmartScreen 警告。Tauri 更新签名用于验证更新来源，不等同于 Windows 代码签名。

## 作者与授权

BongoCat Counter 是基于 [ayangweb/BongoCat](https://github.com/ayangweb/BongoCat) 的非官方修改版，并非原作者的官方发布。

- 原项目：Copyright (c) 2025 ayangweb。
- BongoCat Counter 修改：Copyright (c) 2026 PLA0185。
- 软件按 [MIT License](LICENSE) 发布。请保留原作者的版权与许可声明。
- [Awesome-BongoCat](https://github.com/ayangweb/Awesome-BongoCat) 收录的社区皮肤各有作者与授权条件，不随本仓库的安装包分发。
