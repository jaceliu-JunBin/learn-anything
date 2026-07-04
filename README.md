# learn-anything

通用学习教练 skill——用六条规则把任何大领域（英语、数学、经济学、编程等）的学习变成可执行的系统。

A general-purpose learning coach skill for Claude: six rules for mastering any subject.

## 六条规则 / The Six Rules

1. **搭建分层学习阶梯** — 大领域拆成五级，每级标注内容、易错点、进阶标准，避免越级混乱
2. **抓 20% 核心** — 二八法则：找出最重要的 20% 内容，设计有限总时长的闭环学习计划（练习+资源+复盘）
3. **学完即验证** — 一次只问一个问题（简单→困难），✅/❌ 打分，只重新解释没掌握的
4. **一页速查表** — 学完一个主题压缩成一页：一句话定义、最重要概念、真实例子、常见错误、使用前检查清单、5 个自测问题
5. **从噪音里找信号** — 只筛选最值得看的 5 个资源（适合谁/难度/怎么用/不用看哪里）+ 学习路径
6. **费曼学习法** — 用 12 岁孩子能听懂的话解释 → 学习者用自己的话讲回来 → 诊断（讲对/漏了/混淆/只是用了高级词汇）→ 重讲到真正明白

## 安装 / Install（Claude Code）

克隆到个人 skills 目录：

```bash
git clone https://github.com/jaceliu-JunBin/learn-anything ~/.claude/skills/learn-anything
```

或者手动把 `SKILL.md` 复制到 `~/.claude/skills/learn-anything/SKILL.md`。

## 使用 / Usage

安装后直接对 Claude 说：

- "我想学经济学，帮我规划一下"（触发规则 1 → 2 → 5）
- "我刚学完机会成本，考考我"（触发规则 3）
- "供需关系这个主题学完了，帮我收尾"（触发规则 6 → 4）
