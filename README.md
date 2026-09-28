# 教员skill

基于《毛泽东选集》所读文本蒸馏的现代复杂问题诊断与行动方法。中文版本是默认、可调用的主版本；英文版本作为同仓库内的完整备份。

## 版本结构

| 用途 | 中文主版本 | 英文备份 |
|---|---|---|
| 技能入口 | `SKILL.md` | `SKILL.en.md` |
| 界面元数据 | `agents/openai.yaml` | `agents/openai.en.yaml` |
| 方法卡 | `references/method-cards.md` | `references/method-cards.en.md` |
| 来源与证据 | `references/sources.md` | `references/sources.en.md` |
| 验证记录 | `references/validation.md` | `references/validation.en.md` |

## 名称约定

- 对外显示名称：**教员skill**
- Codex 技术标识与调用名：`teacher-skill` / `$teacher-skill`
- GitHub 仓库：`teacher-skill`

技术标识使用小写英文和连字符，以满足 Codex 技能发现与校验规则；它不改变对外显示名称。

## 使用

读取 `SKILL.md`，或在安装后调用 `$teacher-skill`：

> 使用教员skill调查并分析这个复杂问题，给出阶段重点、行动计划和验证闭环。

## English backup

The Chinese `SKILL.md` is the canonical entrypoint. The complete English backup uses the `.en.md` and `.en.yaml` files listed above. The user-facing name remains **教员skill**.
