# parent-book-chapter-review

An agent skill (Claude Skills / SKILL.md format) for revising **expert-written education and parenting books for parents**, paragraph by paragraph.

一个用于逐段修改"专家撰写、面向父母阅读的教育类图书"的 AI 技能（Claude Skills / SKILL.md 格式）。

## What it does / 功能

- Revises every paragraph in order, without pausing, and logs what changed.
  逐段修改全文，中途不停顿，并记录每段改动。
- Four standards for every paragraph: fluency (通顺), quality (高质量), strong logic (逻辑性强), and theory that is sufficient and solid (理论性足且实).
- Anchors key claims in real, named theories and scholars; never invents citations. Unverifiable details are marked 【待核】.
  核心论断以真实存在的理论与学者为支撑，不编造文献；无法确认的细节标注【待核】。
- At chapter level, adds missing parent-reader elements: an opening scene, one memorable core idea, practical tools, answers to common parent objections, and a takeaway box.
  每章补足面向父母读者的要素：开篇场景、核心金句、可操作方法、对常见疑虑的回应、章末要点框。
- Keeps the author's viewpoints, voice, and academic identity.
  保留作者观点、叙述人称与学术身份。
- Delivers a per-chapter change log and a clean revised manuscript.
  输出每章修改记录及干净的修订稿。

## Install / 安装

**Claude (claude.ai / desktop app):** zip the `parent-book-chapter-review` folder (so `SKILL.md` sits at the top of the folder) and upload it under Settings → Capabilities → Skills.

**Claude Code:** copy the `parent-book-chapter-review` folder into `~/.claude/skills/`.

## Usage / 使用

Attach a chapter or a full manuscript and ask, for example:

> 用 parent-book-chapter-review 修改这一章

## License

MIT
