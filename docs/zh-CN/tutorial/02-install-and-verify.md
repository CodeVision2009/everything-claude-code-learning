# 第 2 篇：安装与第一次验证

## 本篇要花多久

- **阅读**：约 20～35 分钟  
- **动手**：约 30～60 分钟（取决于你是否第一次配置 harness）

## 学前需备

- 已读 [第 1 篇：ECC 是什么](./01-what-is-ecc.md)。  
- 本机已安装 **Node.js**（用于运行本仓库测试；版本以能跑通 `package.json` / CI 为准）。  
- 想清楚你的 **主 harness**：Claude Code、Cursor、OpenCode、Codex 等之一。

---

## 安装路径总览（文档优先级）

1. **各 harness 官方文档** — 安装客户端、登录、权限；本教程不代替逐步截图。  
2. **本仓库 [README.zh-CN.md](../../../README.zh-CN.md)** — ECC 如何作为插件/配置集接入、有哪些组件。  
3. **`plugins/` 及子 README** — 多工具链时的差异说明；若你选择 Cursor/Codex 路径，请对照对应子文档。

原则：**ECC 提供能力与约定，不负责替你装操作系统或 IDE。**

---

## 按主 harness 理解差异（维护表）

你在阅读本系列时只需选 **一行**当作「主环境」深入，其余知道「路径/文件名可能不同」即可；大版本后若路径有变，以仓库 `plugins/` 与 README 为准。

| Harness（示例） | 你需要自己核对什么 |
|-----------------|-------------------|
| Claude Code | 与 `.claude`、插件市场或本仓库安装脚本相关的说明；通常作为本系列**主参考**。 |
| Cursor | `.cursor` 规则、命令与 MCP 在 UI 中的挂载方式可能与 Claude Code 不同。 |
| Codex / OpenCode | 可能更依赖 `AGENTS.md`、`opencode.json` 等入口；见仓库内对应目录。 |

**Hook** 与 **部分斜杠命令** 在非主 harness 上可能**不等价、部分不生效或行为不同**——这不一定是 bug，而是集成深度差异。遇到现象先查 [TROUBLESHOOTING](../TROUBLESHOOTING.md) 与根目录 [`TROUBLESHOOTING.md`](../../../TROUBLESHOOTING.md)。

---

## 实验 A：仓库自检

本实验验证的是：**你手上的 ECC 源码副本与其测试套件是否健康**，与 harness 是否「聪明」无关。

1. 在终端进入本仓库**根目录**（与 `package.json`、`tests/` 同级）。  
2. 执行（与 [`CLAUDE.md`](../../../CLAUDE.md) 中 Running Tests 一致）：

```bash
node tests/run-all.js
```

3. （可选）抽一条单测，例如：

```bash
node tests/lib/utils.test.js
```

**验收标准**：`run-all.js` 退出码为 0、输出表明测试通过。若失败：记录 Node 版本与完整错误信息，到排错文档中对应段落排查（常见问题包括 Node 版本、路径、权限）。

**你要带走的心智模型**：这是 **ECC 自己的回归测试**；通过说明「插件源码在这一环境可测」，不等于你的业务项目已配置好 ECC。

---

## 排错入口怎么分工

- **根目录** [`TROUBLESHOOTING.md`](../../../TROUBLESHOOTING.md) — 偏通用、英文维护的全面索引。  
- **[docs/zh-CN/TROUBLESHOOTING.md](../TROUBLESHOOTING.md)** — 中文读者的场景化入口（若某条失效，以根目录为准）。

写作或内部推广教程时：**不要在正文粘贴过时排错全文**，只链到上述两处之一。

---

## 常见坑

- **Node 未装或未在 PATH**：`node` 命令不存在时，先解决环境再谈 ECC。  
- **在子目录里跑测试**：请在仓库根执行，否则相对路径可能找不到 `tests/`。  
- **期待所有 hook 在 Cursor 等行为与 Claude Code 完全一致**：以实际 harness 文档为准。

---

## 延伸阅读

- [README.zh-CN.md](../../../README.zh-CN.md)  
- [`CLAUDE.md`](../../../CLAUDE.md)（Running Tests）  
- [TROUBLESHOOTING.md](../TROUBLESHOOTING.md)  

---

## 下一篇预告

用 `/plan`、`/tdd`、`/code-review` 串一条最小工作流，并打开 [COMMAND-AGENT-MAP.md](../../COMMAND-AGENT-MAP.md) 说出每条命令对应的主要 Agent。
