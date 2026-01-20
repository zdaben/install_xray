# Xray VLESS-Vision-Reality 一键安装脚本

> 专为 Debian 12 / Ubuntu 设计的极简主义安装脚本，部署目前最强抗封锁协议 VLESS + Vision + Reality。

## 🚀 项目特点

- **极简纯净**：无任何面板、无广告、无后台监控，只安装 Xray 官方内核。
- **最新协议**：默认配置 VLESS + XTLS-Vision + Reality 流控模式。
- **智能兼容**：自动识别 Xray 新旧版本密钥输出格式（自动解析 `PrivateKey`/`Password` 字段）。
- **完全自定义**：支持自定义端口、伪装域名 (SNI) 和分享链接备注名称。
- **自动优化**：安装过程中自动开启内核 BBR 加速。
- **一键输出**：安装完毕自动生成 standard `vless://` 分享链接，可直接导入 Hiddify、v2rayN 等客户端。

## 🛠️ 环境要求

- **操作系统**：Debian 12+ (推荐) / Ubuntu 22.04+
- **架构**：x86_64 / amd64
- **权限**：Root 用户

## 💻 一键安装命令

请将下面的命令复制到服务器终端中执行：

```bash
apt update && apt install -y curl && bash <(curl -Ls https://raw.githubusercontent.com/zdaben/install_xray/refs/heads/main/install.sh)
