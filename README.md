# Eagle Swift

macOS 素材管理应用 · 公开内测版

**[下载最新版安装文件（DMG）](https://github.com/Yeung9203/eagle-releases/releases/latest/download/Eagle-Swift.dmg)** · [版本记录](https://github.com/Yeung9203/eagle-releases/releases)

## 安装与更新

适用于 Apple 芯片 Mac（M 系列），macOS 14 或更高版本。

1. 下载 Eagle-Swift.dmg，双击打开安装窗口。
2. 把左侧的 Eagle Swift 图标拖到右侧的「Applications／应用程序」文件夹，等待复制完成。然后从 Mac 的「应用程序」中打开 Eagle Swift；安装磁盘可以推出。
3. 此版本尚未经过 Apple Developer ID 签名和公证。如 macOS 阻止打开，在确认下载来源可信后，到「系统设置 → 隐私与安全性」查找这次被阻止的 Eagle Swift，点击「仍要打开」，按系统提示确认。不要关闭整个系统的安全保护。
4. 有新版本时，左下角资料库名称右侧会出现蓝色下载按钮。点击后按提示下载安装、重启即可。也可以使用「Eagle Swift → 检查更新…」，或在设置的「更新」页开启自动检查。

更新时应用会退出并重新打开。素材库和设置保留；首次使用新资料库格式后，旧版本可能无法读取，请保留资料库备份。

下载页面和更新文件是公开的，任何拿到链接的人都可以下载；它不是带邀请验证的私密分发。
浏览器扩展目前仍需在浏览器中单独安装、重新加载，不随应用升级自动刷新。

## 浏览器扩展（Chrome / Edge）

**[下载 Eagle Swift 采集助手 0.6.2](https://github.com/Yeung9203/eagle-releases/releases/latest/download/EagleSwift-Collector.zip)**

1. 下载并解压 ZIP，把 `EagleSwift-Collector` 文件夹放在固定位置，安装后不要删除。
2. Chrome 地址栏输入 `chrome://extensions`，Edge 输入 `edge://extensions`。开启「开发者模式」，点击「加载已解压的扩展程序」，选择该文件夹。
3. 打开 Eagle Swift，进入「设置 → 采集与自动导入」，复制浏览器连接码。
4. 打开浏览器扩展的「设置」，粘贴连接码并连接，然后刷新要采集的网页。

此版本包含图片自动命名、拖拽收藏、批量采集和网页截图。最低需要 Chromium 116，不支持 Safari。扩展更新需替换原文件夹内容后手动「重新加载」；桌面应用的自动更新不会替换单独下载的扩展。详细说明见 ZIP 内 README。

安装操作参考：[Chrome 官方说明](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked)、[Edge 官方说明](https://learn.microsoft.com/en-us/microsoft-edge/extensions/getting-started/extension-sideloading)。

## 下载校验

DMG 安装文件提供 Eagle-Swift.dmg.sha256 校验值。应用内更新会自动验证更新目录和 ZIP 安装包的签名。

扩展下载包另提供 EagleSwift-Collector.zip.sha256 校验值。

此仓库提供安装包、浏览器扩展、安装说明和更新目录。
