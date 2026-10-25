# N-PagePin Native

把 Notion 页面贴在 macOS 桌面上。此仓库仅用于分发程序安装包和自动更新清单，源码单独维护。

## 下载与安装

从 [最新版本](https://github.com/json2jason/N-PagePin-Releases/releases/latest) 下载 DMG。当前支持 Apple Silicon（M 系列芯片）及 macOS 14 或更高版本。

首次安装：打开 DMG，将「N-PagePin Native」拖到「Applications」。旧版本尚未接入更新器时，先正常退出，再替换同名应用。

当前版本采用本机 ad-hoc 签名，尚未经过 Apple Developer ID 签名和公证。首次下载后如遇系统开发者提示，请按照 [Apple 官方说明](https://support.apple.com/zh-cn/102445) 在「隐私与安全性」中确认打开。

## 程序内更新

在应用菜单或「连接与设置」中选择「检查更新…」，下载后选择安装并重新启动。应用也提供自动检查更新开关。更新前先保存本地草稿，仅替换程序包；本机配置、便签和钥匙串凭据继续保留。

更新清单和更新安装包使用 Sparkle EdDSA 签名验证，SHA-256 校验文件随版本提供。

## 分发内容

公开资产只包含本次构建的应用安装包、更新清单、校验文件和发布说明。不包含开发仓库、Notion 内容、用户数据库、账号密钥、签名私钥、本机配置、备份或验收日志。Notion 集成密钥由每位使用者在自己的电脑上配置并保存到 macOS 钥匙串。

应用包含的开源组件按各自许可证分发。公开下载不代表应用源码开源。
