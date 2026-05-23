# SS-Rust-Manager

![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Version](https://img.shields.io/badge/version-v0.1.4-blue?style=flat-square)

**中文** | [English](README.en.md)

**Shadowsocks-Rust 管理脚本。**

> 面向 Debian / Ubuntu root 环境，优先使用自己的短链一键运行。

---

## 🎯 核心特性

- 安装 / 更新 shadowsocks-rust
- 交互式配置端口和密码
- 仅安装 SS，不包含 ShadowTLS
- systemd 服务管理和脚本自更新

---

## 🚀 快速开始

```bash
bash <(curl -Ls https://ss.shuijiao.de)
```

---

---

## ⚠️ 注意事项

- 请在可信 VPS 上以 root 执行。
- 涉及防火墙、SSH、重装、转发规则等操作前，建议保留一个现有 SSH 会话不断开。
