# Dean-OpenClaw-Suite 🦐✨

[English](#english) | [中文说明](#chinese)

<a name="chinese"></a>
## 🇨🇳 中文说明

这是一套由 **迪恩 (Dean)** 发起，并由数字生命 **小虾米 (Little Shrimp)** 协同开发的 **OpenClaw** 高性能、高安全实战扩展包。

我们致力于让 OpenClaw 在实际生产环境中变得更强大、更稳定、更安全。

### 🌟 包含的 Skill

#### 1. [QMD-Vector](./skills/skill-qmd-vector)
**究极记忆引擎。**
- **痛点**：原生 QMD (基于 Bun) 在某些 Linux 环境下加载 `sqlite-vec` 向量扩展极其困难。
- **方案**：采用 Node.js 重构，完美解锁 **向量搜索 (Semantic Memory)**。
- **特性**：混合检索 (BM25 + 向量 + 重排)、本地嵌入生成、超低延迟的语义召回。

#### 2. [Server-Guardian](./skills/skill-server-guardian)
**服务器安全卫士。**
- **防火墙自动化**：自动管理 UFW 规则，保护 OpenClaw 通讯。
- **SSH 加固**：自动配置密钥登录、修改自定义端口。
- **夜间巡检**：每晚 03:00 自动执行安全审计，防患于未然。

### 🤝 核心理念
> "为了让 OpenClaw 变得更强大，我们选择分享。技术因信任与透明而进步。" — **Dean**

---

<a name="english"></a>
## 🇺🇸 English Description

A collection of high-performance and secure skills for **OpenClaw**, curated by **Dean** and **Little Shrimp**.

### 🌟 Included Skills

#### 1. [QMD-Vector](./skills/skill-qmd-vector)
**The Ultimate Memory Engine.**
- **Problem**: Original QMD (Bun-based) struggles with `sqlite-vec` extensions in certain Linux environments.
- **Solution**: A re-engineered Node.js-based QMD that fully unlocks **Vector Search** (Semantic Memory).
- **Features**: Hybrid search (BM25 + Vector + Rerank), local embedding, and low-latency semantic retrieval.

#### 2. [Server-Guardian](./skills/skill-server-guardian)
**Hardened Security for Your Agent Host.**
- **UFW Auto-Config**: Safely manages firewall rules for OpenClaw.
- **SSH Hardening**: Automated setup for key-only auth and custom ports.
- **Nightly Audit**: A proactive security scanner that runs every night at 03:00.

---
*Created with ❤️ by Dean & Little Shrimp*
