# SS-Rust-Manager

水饺自用 Shadowsocks-Rust 管理脚本，只安装 SS，不包含 ShadowTLS。

## 一键运行

```bash
curl -L -s ss.shuijiao.de > /root/ss-rust.sh && chmod +x /root/ss-rust.sh && ./ss-rust.sh
```

仅支持 `amd64 / x86_64`，自动从 shadowsocks-rust 最新 Release 下载对应架构。
