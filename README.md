# 度偶指纹浏览器 Windows

当前正式版：[0.2.0 · Windows x64](https://github.com/DuouTech/duou-browser-downloads/releases/tag/v0.2.0)。本仓库仅用于安装包、ZIP、公钥、签名更新清单、许可证和核验资料的公开分发。

## 安装与升级

- 下载 `DuouBrowser-0.2.0-win32-x64-stable-setup.exe` 安装，或完整解压 ZIP 后运行程序。
- Beta.2 未配置自动更新，首次升级到 0.2.0 需手动安装到原目录。升级前正常关闭应用和浏览器环境，保留原有数据目录。
- 0.2.0 的 NSIS 安装版使用稳定更新通道，验证更新清单签名及安装包完整性，用户确认后才安装并重启。ZIP 不支持应用内原位更新。
- 本版采用浏览器专属长期 Ed25519 应用更新签名，没有 Windows Authenticode 发布者证书签名，Windows 可能显示“未知发布者”。这两种签名不能互相替代。
- 使用发行页的 `SHA256SUMS.txt` 核对下载文件。公开公钥为 `windows-update-public.pem`，更新元数据为 `latest.yml`。

具体功能、验收范围和限制以版本发行说明为准。旧 [Beta.2](https://github.com/DuouTech/duou-browser-downloads/releases/tag/v0.2.0-beta.2) 保留原附件与历史状态。

本仓库不存放开发源码、私钥、凭据或用户浏览器资料。保留上游 MIT 许可及随二进制提供的第三方许可。
