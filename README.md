# 【亿泰坊】通讯翻译中枢 下载指引

当前最新版本：5.0.0

## 直接下载

点击下载：[yitaifang-communication-suite-v5.0.0-net8.zip](https://github.com/canglang-88/ewolf-whatsapp-release/releases/download/v5.0.0/yitaifang-communication-suite-v5.0.0-net8.zip)

## 旧 WhatsApp 单独版自动更新

如果对方电脑可以正常访问 GitHub，并且已经安装旧版 WhatsApp 单独版：关闭软件后重新打开，旧版本会检测到 5.0.0，弹窗提示更新，点击确认即可自动下载并替换为 5 合一中枢版本。

如果对方电脑访问不了 GitHub：可能不会正常弹出更新提示，需要把上面的 zip 下载链接发给对方手动下载、解压后使用。

## 本次更新

- 从 WhatsApp 单独版升级为 5 合一通讯翻译中枢。
- 包含 WhatsApp、Google Chat、Google Voice、Signal 翻译独立版等模块。
- Signal 支持独立隔离、发送前对照翻译、长文本翻译上限对齐 WhatsApp。
- 翻译缓存改为共用本地缓存。
- OpenAI 设置脚本统一配置接口：Signal 使用环境变量，WhatsApp / Google Chat / Google Voice 写入本机配置。
- .NET 8 win-x64 自包含包，不需要单独安装 .NET。

## 使用提示

1. 自动更新：旧 WhatsApp 单独版弹窗后点击确认，等待下载完成，更新后会启动中枢。
2. 手动安装：完整解压 zip，双击“创建桌面快捷方式.cmd”，然后从桌面“【亿泰坊】通讯翻译中枢”启动。
3. OpenAI：双击“设置OpenAI翻译接口.cmd”，粘贴自己的 OPENAI_API_KEY，设置完成后重启程序。

## 不包含内容

- OpenAI API Key
- WhatsApp / Signal / Google 登录数据
- 聊天记录
- 翻译缓存
- 日志和本机配置备份