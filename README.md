# 墨团专注 🐈

陪你专注、提醒喝水的 macOS 桌面小猫。

## 直接下载安装

**[下载墨团 App](https://github.com/LouisWongLab/motuan-focus/releases/download/v0.5.0-beta.1/MotuanFocus-0.5.0-macOS-arm64.zip)** · [版本与安装说明](https://github.com/LouisWongLab/motuan-focus/releases/tag/v0.5.0-beta.1)

仅支持 Apple 芯片 Mac（M1 及后续），macOS 13+。解压后把「墨团专注.app」拖入应用程序，无需编译。

当前为未经过 Apple Developer ID 签名与公证的测试版，首次打开可能被 macOS 阻止，不能保证双击即用。

## 交给 Agent 安装

复制下面这段给有联网及本机操作能力的 Agent：

> 请阅读 https://github.com/LouisWongLab/motuan-focus 的版本说明，确认我的电脑兼容，下载 Releases 中的 MotuanFocus-0.5.0-macOS-arm64.zip 并校验 SHA-256，帮我安装。保留已有数据，遇到系统安全确认交给我处理，不要关闭 Gatekeeper。只使用 App 无需下载或编译源码。

App SHA-256：`d741976b78d0b7719f0dec3e862f7a3ca9343b7e3d7b7c08c955447f86b34ab7`

## 开源代码

**[下载完整源码](https://github.com/LouisWongLab/motuan-focus/releases/download/v0.5.0-beta.1/MotuanFocus-source-0.5.0.zip)**

源码暂以 Releases 附件提供，包含 Swift 源码、界面资源、构建脚本、测试及文档。程序代码采用 MIT License（包内 LICENSE）；图片和宠物美术素材不属于 MIT 授权范围。

不要使用 GitHub 自动生成的 Source code 下载项：早期标签仅包含说明文件。请使用上方明确命名的完整源码包。

在 Mac 安装 Xcode Command Line Tools 和 Swift 5.9+ 后，解压源码并进入 motuan-focus 目录：

```sh
chmod +x build.sh
./build.sh
open "dist/墨团专注.app"
```

相关统计、休息规则测试及独立源码构建已通过。构建脚本使用本地 ad-hoc 签名，不等于 Apple 公证。

## 功能

专注与休息计时、桌宠互动、猫粮投喂、独立抽奖、喝水提醒与次数统计、灵感罐头收藏。

下载包和源码不包含作者的专注记录、收藏文件或猫粮余额。
