# 【亿泰坊】通讯翻译中枢 下载指引

当前最新版本：5.0.1

## 直接下载完整包

点击下载：[yitaifang-communication-suite-v5.0.1-net8.zip](https://github.com/canglang-88/ewolf-whatsapp-release/releases/download/v5.0.1/yitaifang-communication-suite-v5.0.1-net8.zip)

## 旧版自动更新

如果对方电脑的旧版有自动更新功能：关闭软件后重新打开，旧版本会检测到 5.0.1，点击确认即可更新。

自动更新会先下载小过渡包：
[yitaifang-suite-bootstrap-v5.0.1-net8.zip](https://github.com/canglang-88/ewolf-whatsapp-release/releases/download/v5.0.1/yitaifang-suite-bootstrap-v5.0.1-net8.zip)

过渡包会继续下载完整中枢包，避免旧版直接下载大包时超时或看起来卡死。

## 旧版没有更新功能时

如果对方电脑的旧版没有更新提示，就下载完整包，解压后运行 一键覆盖旧版并启动.cmd。它会尝试自动找到旧版安装目录并覆盖程序文件。

如果自动找不到，就右键旧版桌面快捷方式，点“打开文件所在的位置”，把完整包解压后的文件复制进去并选择全部替换。

## 本次版本

- 纯净四合一中枢：WhatsApp、Google Chat、Google Voice、Gmail。
- 已完全剔除 Signal 模块和旧 Signal 残留。
- 包内包含 一键覆盖旧版并启动.cmd。
- 保留别人电脑上的本地登录数据：更新只覆盖程序文件，不删除 %APPDATA%、%LOCALAPPDATA% 或 D:\亿泰坊通讯翻译系统数据。
- .NET 8 win-x64 自包含包，不需要单独安装 .NET。

## 不包含内容

- OpenAI API Key
- WhatsApp / Google / Gmail 登录数据
- 聊天记录
- 翻译缓存
- 日志和本机配置备份
- Signal 模块