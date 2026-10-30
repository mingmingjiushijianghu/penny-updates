# Penny

Penny 是一款简洁的 Android 记账应用，支持日常收支、多个账户、账户转账、分类统计和账本备份。账目保存在设备上，无需注册。

本仓库提供安装包、更新信息与许可文件。当前版本为 **1.1.0**，支持 Android 7.0 及以上。

## 安装与升级

从本仓库 Releases 下载 `Penny-1.1.0.apk`，在安卓手机上打开，并按系统提示确认安装。可用 `SHA256SUMS.txt` 核对安装包的 SHA-256。

已经安装清禾记账或 Penny 1.0.1 时，直接覆盖安装，保留原有账本。Penny 1.0.1 尚无应用内更新功能，需要手动完成这一次升级。

安装 1.1.0 后，可在「设置 → 应用更新」检查后续版本。自动检查只读取版本信息；下载和安装由你确认，最终仍需经过安卓系统安装界面。

## 数据与网络

日常记账可离线使用。检查更新与下载安装包需要连接更新服务器；更新请求不包含账本、账户、交易或备注。可关闭自动检查，手动选择检查时间。

可在设置中导出账本备份或 CSV。备份包含个人记账数据，请自行保存，不要提交到此公开仓库。

## 开源致谢

Penny 基于 [Tally Android](https://github.com/IamAndelib/Tally-android) 修改。原项目采用 MIT License，原作者版权声明完整保留于 [LICENSE](LICENSE)。字体、图标和币种数据的许可见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) 与 [LICENSES](LICENSES)。

版本变化见 [release-notes.md](release-notes.md)。
