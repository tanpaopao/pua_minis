# GitHub Release Notes — pua-minis v1.1.0

## Title

pua-minis v1.1.0

## Release Notes (中文)

`pua-minis` v1.1.0 发布。  
这一版不是单纯加文案，而是把技能从“能用”推进到“更完整、更稳、更适合真实排障”。

### 新增
- 本质换轨判定（`path-switching.md`）
- 结构化失败退出（`failure-exit.md`）
- 轻量状态块（`status-format.md`）
- 中途自检（`self-check.md`）
- 反转假设流程

### 增强
- 强化 L1 / L2 / L3 升级动作
- 强化“停止空转 → 补取证 → 查到底”的排障闭环
- 明确“换参数不等于换方法”
- 扩展示例与清单，使其和主技能保持一致

### 保持不变
- 继续坚持 Minis-first 风格：**少空话、重动作、强闭环**
- 继续聚焦调试、排障、部署、配置、API、运维、数据故障场景

这不是把通用 PUA 技能直接搬到 Minis，
而是把真正有效的部分重新工程化为 Minis 原生排障协议。

---

## Release Notes (English)

`pua-minis` v1.1.0 is now released.

This version is not just a wording update — it turns the skill into a more complete, low-noise, Minis-native troubleshooting workflow.

### Added
- Path-switching guidance (`path-switching.md`)
- Structured failure exit (`failure-exit.md`)
- Lightweight status block (`status-format.md`)
- Mid-task self-check (`self-check.md`)
- Reverse-hypothesis workflow

### Improved
- Stronger L1 / L2 / L3 escalation guidance
- Better anti-spinning troubleshooting loop
- Clearer distinction between parameter tweaking and real path switching
- Expanded examples and checklist to match the main skill

### Kept
- Minis-first style: **less talk, more action, stronger closure**
- Focus on debugging, troubleshooting, deployment, config, API, ops, and data-failure tasks

This is not a direct port of generic PUA-style prompting.
It is a Minis-native troubleshooting protocol engineered for real execution.
