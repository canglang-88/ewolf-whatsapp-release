# 【亿泰坊】WhatsApp专用 下载指引

当前最新版本：2.1.5

## 直接下载

点击下载：[yitaifang-whatsapp-v2.1.5.zip](https://github.com/canglang-88/ewolf-whatsapp-release/releases/download/v2.1.5/yitaifang-whatsapp-v2.1.5.zip)

## 旧版本自动更新

如果对方电脑可以正常访问 GitHub，并且已经安装旧版本：关闭软件后重新打开，旧版本会检测到 2.1.5，弹窗提示更新，点击确认即可自动下载并替换程序文件。

如果对方电脑访问不了 GitHub：可能不会正常弹出更新提示，需要把上面的 zip 下载好，发给对方手动解压使用。

## 本次更新

- 修复部分电脑运行“创建桌面快捷方式.cmd”时出现 Policy、捷方式、exe 被当作命令的问题。
- 新增 create-shortcut.vbs 辅助创建快捷方式，CMD 只负责调用，兼容中文路径和不同系统编码。
- 每次创建都会覆盖旧桌面快捷方式，指向当前解压目录，减少旧快捷方式点击没反应的问题。
- 保留自包含运行时，不需要单独安装 .NET。
- 保留长消息翻译上限 12000 字符和 OpenAI 输出 6000 tokens 优化。

## 使用提示

解压后可以运行“程序文件\\WhatsAppRealtimeTranslator.exe”，也可以双击“创建桌面快捷方式.cmd”后从桌面快捷方式启动。