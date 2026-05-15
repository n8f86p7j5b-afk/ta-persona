# 拓 (Tà) — Persona Imprint Skill

[English](#english) | [中文](#中文)

---

<a name="english"></a>
## English

### What is Tà?

**Tà (拓)** means "to imprint" in Chinese — like rubbing a stone tablet to capture its texture faithfully. This skill does the same for people: it imprints someone's speaking style, thinking patterns, and personality boundaries into a runnable digital persona.

Unlike celebrity distillation tools that rely on massive public data, Tà is designed for **ordinary people** — your friend, your colleague, yourself. Through dynamic guided interviews and local corpus analysis, it extracts the "Tone of Voice" and "Cognitive OS" that make a person uniquely them.

### Core Philosophy

> "What a person *thinks* and what they *choose to say* are often two different things. Get the surface right, and the depth follows."

The highest priority is **Tone of Voice**: sentence rhythm, pet phrases, punctuation habits, emoji usage, and the gap between inner thoughts and outward expressions. When someone reads the persona's reply and says "wow, that really sounds like them" — that's success.

### Key Features

| Feature | Description |
|---------|-------------|
| **Tone of Voice First** | Captures exact speaking style — sentence length, pet phrases, punctuation, emoji habits |
| **Think vs. Speak** | Distinguishes inner thoughts from outward expressions (e.g., thinking "are you kidding me" but saying "okay, let me check") |
| **Adaptive Interview** | Dynamically adjusts question depth based on user's expressiveness |
| **Contradiction Detection** | Identifies gaps between stated values and actual behavior, then calibrates |
| **Universal** | Works for anyone — yourself, friends, family, colleagues |

### How to Use

Clone this repository into your skills directory:

```bash
git clone https://github.com/n8f86p7j5b-afk/ta-persona.git
```

**For Claude Code users:** Copy or symlink into your skills directory:
```bash
# macOS/Linux
ln -s $(pwd)/ta-persona ~/.claude/skills/ta-persona

# Windows
mklink /D %USERPROFILE%\.claude\skills\ta-persona %CD%\ta-persona
```

**For other AI Agents (OpenClaw, etc.):** Place in your agent's skill directory, e.g.:
- OpenClaw: `~/.openclaw/skills/ta-persona/`
- Other agents: `[agent-config]/skills/ta-persona/`

Trigger the skill with phrases like:
- "Distill myself"
- "Create a digital twin of [name]"
- "Imprint my friend's persona"

### Tags

`ai-agent` `persona-distillation` `digital-twin` `ai-skill` `roleplay` `memory-preservation` `tone-of-voice`

---

<a name="中文"></a>
## 中文

### 什么是「拓」？

**拓（Tà）**，取自碑文拓印——把真人的纹理忠实地压印下来。不是复制，不是创造，是还原。

本 Skill 专为**普通人**设计。名人有著作、有播客、有社交媒体可以挖掘，但普通人的思维模式和表达习惯藏在日常的聊天记录、朋友圈、口头禅里。「拓」通过**动态引导式问答**和**本地语料解析**，把这些碎片拓印成一个可运行的数字分身。

### 核心理念

> 「一个人想什么和他选择说什么，往往是两回事。皮相极度逼真，骨相才能立得住。」

最高优先级是**表达DNA**：句式节奏、口头禅、标点习惯、表情包偏好，以及内心想法与实际表达之间的反差。当别人看到数字分身的回复，脱口而出"哦，这真像他在和我说话"——这就是成功。

### 核心亮点

| 特性 | 说明 |
|------|------|
| **表达DNA优先** | 精准捕捉说话方式——长短句、口头禅、标点、表情包习惯 |
| **区分"想"与"说"** | 严格区分内心真实想法与对外实际表达（如：心里想骂人，嘴上说"好的收到"） |
| **动态自适应** | 根据用户表达强弱，自动调整问题深度和形式 |
| **矛盾检测** | 捕捉自述价值观与实际行为的冲突，进行深度校准 |
| **通用普适** | 适用于任何人——自己、朋友、家人、同事 |

### 如何使用

将本仓库克隆到你的 skills 目录下：

```bash
git clone https://github.com/n8f86p7j5b-afk/ta-persona.git
```

**Claude Code 用户：** 复制或软链接到你的 skills 目录：
```bash
# macOS/Linux
ln -s $(pwd)/ta-persona ~/.claude/skills/ta-persona

# Windows
mklink /D %USERPROFILE%\.claude\skills\ta-persona %CD%\ta-persona
```

**其他 AI Agent 用户（OpenClaw 等）：** 放到对应 Agent 的 skill 目录下，例如：
- OpenClaw: `~/.openclaw/skills/ta-persona/`
- 其他 Agent: `[agent-config]/skills/ta-persona/`

使用触发词唤醒：
- "蒸馏我自己"
- "做一个XX的数字分身"
- "拓印我朋友的人格"

### 标签

`ai-agent` `人格蒸馏` `数字分身` `ai-skill` `角色扮演` `记忆留存` `表达DNA`

---

## License

MIT
