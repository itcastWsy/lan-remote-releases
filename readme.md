# LanRemote 局域网远控 · 发布仓库

本仓库只存放 **LanRemote** 的桌面端安装包（Windows / macOS），源码在私有仓库开发，经 CI 自动构建后发布到这里。

## 下载

前往 **[Releases](../../releases/latest)** 页面下载最新版本：

| 平台 | 文件 | 说明 |
|---|---|---|
| Windows | `LanRemote-<版本>-win-x64.exe` | NSIS 安装包（推荐） |
| Windows | `LanRemote-<版本>-win-x64-portable.exe` | 免安装单文件版 |
| macOS | `LanRemote-<版本>-mac-*.dmg` | ⚠️ 未签名预览（mac 控制功能开发中） |

## 产品简介

LanRemote 是一款**局域网内**的远程控制工具（类似 UU 远程 / ToDesk 的局域网场景）：

- 支持 **Windows ⇄ 鸿蒙 PC** 互相远程控制（macOS 端开发中）
- 设备自动发现，一键连接；支持 **无线局域网** 与 **USB 数据线直连** 两种通道
- 实时屏幕流 + 键鼠 1:1 控制，多档清晰度
- 鸿蒙 PC 被控端经 **华为 AppGallery** 分发（上架筹备中）

## 注意事项

- Windows 安装包未做代码签名，首次运行若出现 SmartScreen 提示，选择「更多信息 → 仍要运行」。
- macOS 包未签名：右键 → 打开；当前版本注入功能仅支持 Windows 被控端。
- 仅限可信局域网使用；当前版本为明文传输（加密与配对认证在路线图中）。

## 反馈

问题与建议请通过源码仓库 Issue 或开发者联系方式反馈。