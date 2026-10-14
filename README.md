<div align="center">

# 🎬 browser-record-replay

## 录一遍演示，换来一个能重复跑的浏览器 RPA 技能
## Record one demo, get a reusable browser RPA skill

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

面向同机本地直连（Local Direct）场景：用内置浏览器完成一次人工演示，技能负责录制、调试并把演示整理成可复用的浏览器 RPA 技能。流程不可跳步，录制停止后会立刻转入任务说明整理，并明确告诉用户「现在不需要你操作」。它会从演示中核对实际操作与结果，产出包含目标、任务入参、自动完成步骤和结果的说明，等你确认后才交付。严格遵守面向用户的回复边界：内部清单、计划中的工具调用、文档名和命令，都不会被当作进度台词念给用户听。

### ✨ 能做什么

- 人工演示一次 → 录制 → 调试 → 交付可复用的浏览器 RPA 技能
- 录制停止即自动整理任务说明：目标、入参、自动步骤、结果四要素齐全
- 核对自己在演示中做的操作与结果，不靠猜补步骤
- 强制的 Windows 执行契约，保证交付的技能在目标机器上可跑
- 严格的用户可见回复边界：内部清单和命令不当作进度汇报
- 自带核心命令集，覆盖录制、回放与调试全过程

### 📦 包含的技能

- `browser-record-replay` —— 见 [`browser-record-replay/SKILL.md`](browser-record-replay/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/browser-record-replay.git
cp -r browser-record-replay/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Built for same-computer Local Direct workflows: you perform one manual demo in the built-in browser, and the skill records it, debugs it, and turns it into a reusable browser RPA skill. The flow is non-negotiable and step-gated; the moment recording stops it moves straight into writing up the task description and tells the user plainly that no action is needed right now. It re-checks the actual operations and results from the demonstration, then produces a description covering the goal, task inputs, automated steps and results, and waits for confirmation before delivering. A strict user-visible reply boundary keeps internal checklists, planned tool calls, document names and commands out of progress chatter.

### ✨ What it does

- One manual demo becomes a recorded, debugged, reusable browser RPA skill
- Recording stops and a task description is drafted with goal, inputs, steps and results
- Verifies the operations and outcomes actually shown in the demo instead of guessing
- A mandatory Windows execution contract keeps the delivered skill runnable on target machines
- Strict user-visible reply boundary: internal checklists and commands stay off the progress script
- Ships a core command set covering record, replay and debug end to end

### 📦 Skills included

- `browser-record-replay` — [`browser-record-replay/SKILL.md`](browser-record-replay/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/browser-record-replay.git
cp -r browser-record-replay/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
