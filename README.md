# RustDesk 安装与使用指南

开源远程桌面，支持 Windows、macOS、Linux、Android、iOS 等。

- 项目：https://github.com/rustdesk/rustdesk
- 下载：https://github.com/rustdesk/rustdesk/releases

## 安装客户端

从 Releases 下载对应平台安装包并安装。

## 基本使用

1. 被控端打开软件，记下 ID 与密码（可设永久密码）
2. 主控端输入对方 ID 发起连接
3. 按提示输入密码后即可远控

## 自建服务器（可选）

对隐私或稳定性有要求时，可自建：

- `hbbs`：ID / 信号
- `hbbr`：中继

部署后在客户端网络设置中填写 ID 服务器、中继与 Key。端口与防火墙按官方文档开放。

## 说明

请遵守当地法律与软件许可。仅用于合法授权的远程协助与管理。使用风险自负。

## License

本仓库文档 MIT。
