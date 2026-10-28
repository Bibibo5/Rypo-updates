# Rypo for macOS

Rypo 的公开安装文件和签名更新目录。

[下载最新版本](https://github.com/Bibibo5/Rypo-updates/releases/latest)

支持 Apple 芯片 Mac、macOS 15 或以上。首次安装使用发布页的 `.pkg`；安装 0.37.0 或之后的版本后，可在 **Rypo → 检查更新** 或 **设置 → 关于 Rypo → 软件更新** 中升级。

更新包和更新目录均使用 Ed25519 签名，应用在解压前验证。项目、聊天、草稿与登录保留在各自电脑，远程 Worker 单独维护。

此仓库只托管安装/更新文件与说明，不托管工程源码目录、业务项目、聊天、账号配置或签名私钥。安装包包含运行所需的程序及 JavaScript 模块。

当前应用采用 ad-hoc 签名，尚未获得 Apple Developer ID 签名与公证。首次运行及更新安装可能需要按 macOS 提示完成用户确认或管理员授权。
