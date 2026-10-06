# AI客服 RPA Windows 客户端

本仓库仅用于分发本地手动构建的 Windows 客户端及签名更新清单。应用源码保持私有，不在本仓库公开。

## 下载与更新

首次安装请到 [Releases](https://github.com/LiuZhouZhouJieLun/aikefu-rpa-releases/releases) 下载正式版本的 `AiKeFu-RPA-*-win-x64.zip`，完整解压后运行 `RPA/rpa.exe`。

后续在“多客服会话中心”点击“更新”。客户端验证发布签名后下载更新，正常关闭客服和旧面板，再自动打开新版。更新保留账号配置、聊天记录和安卓环境；客服设备及 AI 回复需重新开启。

GitHub 自动生成的 Source code ZIP/TAR 只含本发布仓库的说明文件，不是客户端安装包。

## 发布方式

维护者在本地打包和运行验证后，手动上传程序 ZIP 与 `update.json` 到同一个正式 Release，再将其设为 Latest。源码快照、构建日志、账号数据和签名私钥均不上传。

第一方源码不随发行包分发。第三方组件的许可证随客户端提供。
