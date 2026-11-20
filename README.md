# 墨团专注 🐈

陪你专注、提醒喝水的 macOS 桌面小猫。

## 下载最新版 · 0.5.1（2026-11-20）

**[下载墨团 App](https://github.com/LouisWongLab/motuan-focus/releases/download/v0.5.1-beta.1/MotuanFocus-0.5.1-macOS-arm64.zip)** · [版本与安装说明](https://github.com/LouisWongLab/motuan-focus/releases/tag/v0.5.1-beta.1)

仅支持 Apple 芯片 Mac（M1 及后续），macOS 13+。解压后把 staging 中的「墨团专注.app」拖入应用程序，无需编译。更新时先退出旧版本，再替换 App；保留现有用户数据。

当前为未经过 Apple Developer ID 签名与公证的测试版，首次打开可能被 macOS 阻止，不能保证双击即用。不要关闭系统安全保护。

## 交给 Agent 安装

> 请阅读 https://github.com/LouisWongLab/motuan-focus 的版本说明，确认我的电脑兼容，下载 Releases 中的 MotuanFocus-0.5.1-macOS-arm64.zip 并校验 SHA-256，帮我安装。先退出旧版并备份旧 App，保留已有用户数据，遇到系统安全确认交给我处理，不要关闭 Gatekeeper。只使用 App 无需下载或编译源码。

App SHA-256：`7be9ba38670a14c59df2de283c05a8d2c250727e13568b320f8ca8692e949287`

## 开源代码

[下载完整源码](https://github.com/LouisWongLab/motuan-focus/releases/download/v0.5.1-beta.1/MotuanFocus-source-0.5.1.zip)

源码以 Releases 附件提供，包含 Swift 源码、界面资源、构建脚本、测试及文档。程序代码采用 MIT License（包内 LICENSE）；图片和宠物美术素材不属于 MIT 授权范围。

不要使用 GitHub 自动生成的 Source code 下载项：标签仅包含仓库说明文件。请使用上方明确命名的完整源码包。

在 Mac 安装 Xcode Command Line Tools 和 Swift 5.9+ 后，解压源码并进入 motuan-focus 目录：

```sh
chmod +x build.sh
./build.sh
open "dist/墨团专注.app"
```

## 本次发布

按当前本地源码重新构建，版本标识更新为 0.5.1，替代首页原 0.5.0 下载入口。功能保持当前版本，无新增功能。计时、猫粮、抽奖、休息提醒、喝水统计及打包交互自检已通过。

专注与休息计时、桌宠互动、猫粮投喂、独立抽奖、喝水提醒与次数统计、灵感罐头收藏。

下载包和源码不包含作者的专注记录、收藏文件或猫粮余额。
