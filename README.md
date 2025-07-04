# Rigel: A Secure, Cross-platform Remote Agent in Rust
# Rigel：用 Rust 编写的安全跨平台远程 Agent

Rigel is a lightweight, secure, and highly extensible remote agent written in Rust. It enables secure remote execution, telemetry, and device control across diverse platforms.

Rigel 是一款用 Rust 编写的轻量级安全远程 Agent，支持远程执行任务、数据上报、设备控制，适用于多平台部署与大规模集群管理。

---

## ✨ Features / 功能特色

- 🔐 Secure communication (TLS, Auth Token)
- 🌐 Multiple protocols supported (HTTP, WebSocket, Protobuf, MessagePack, Thrift)
- ⚙️ Cross-platform support: Linux, macOS, Windows (HarmonyOS IoT planned)
- 💾 Embedded DB for local task logs (sled/sqlite)
- 📆 Scheduled tasks (recurrent / delayed)
- 🧠 Installable as system service / daemon
- 🧩 Pluggable protocol & task engine

---

## 📦 Installation / 安装方法

```bash
cargo install rigel