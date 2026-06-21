# 【亿泰坊】通讯翻译中枢 下载指引

当前最新版本：5.0.6

## 直接下载完整包

点击下载：[yitaifang-communication-suite-v5.0.6-net8.zip](https://github.com/canglang-88/ewolf-whatsapp-release/releases/download/v5.0.6/yitaifang-communication-suite-v5.0.6-net8.zip)

## 自动更新

有自动更新功能的版本，关闭软件后重新打开中枢即可检测到 5.0.6。

- 5.0.1 及以上版本会优先下载补丁包：[yitaifang-communication-suite-patch-v5.0.6-net8.zip](https://github.com/canglang-88/ewolf-whatsapp-release/releases/download/v5.0.6/yitaifang-communication-suite-patch-v5.0.6-net8.zip)
- 更早版本或没有更新入口的旧包，需要手动下载完整包覆盖一次。
- 本版开始按中枢整体更新逻辑处理：中枢检查更新、覆盖整套外壳内对应模块文件、更新后重启中枢。
- Google Voice 和 Google Chat 使用 WhatsApp 的翻译 API 地址、KEY 和模型；模块内只保留翻译开关、语言、颜色等独立设置。

## 不包含内容

- OpenAI API Key
- WhatsApp / Google / Gmail 登录数据
- 聊天记录
- 翻译缓存
- 日志和本机配置备份
- Signal 模块
## 旧版没有更新功能时

如果对方电脑的旧版没有更新提示，就下载完整包，解压后运行 一键覆盖旧版并启动.cmd。它会尝试自动找到旧版安装目录并覆盖程序文件。

如果自动找不到，就右键旧版桌面快捷方式，点“打开文件所在的位置”，把完整包解压后的文件复制进去并选择全部替换。