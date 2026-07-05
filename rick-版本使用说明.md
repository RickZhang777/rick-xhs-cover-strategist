# Rick XHS Cover Strategist 版本使用说明

这个文件夹里有两套用法，不要混用。

## 1. Codex 专用版

给 Codex 使用：

- 文件夹：`rick-xhs-cover-strategist/`
- 入口文件：`SKILL.md`
- 调用方式：

```text
使用 $rick-xhs-cover-strategist 帮我做一张小红书封面提示词。
```

说明：

- Codex 会自动读取 `SKILL.md` 和 `references/`。
- 这是标准 Codex Skill 目录结构。
- 不需要把通用版提示词粘进 Codex。

## 2. 通用系统提示词版

给 Claude、豆包、Kimi、DeepSeek、Hermes 使用：

- 文件：`rick-通用版-Claude豆包KimiDeepSeek-小红书封面助手系统提示词.md`
- 使用方式：把全文复制到对应平台的系统提示词、角色设定、智能体指令或 Project Instructions 里。

说明：

- Claude、豆包、Kimi、DeepSeek 不会自动识别 Codex 的 `SKILL.md` 目录结构。
- 它们只需要这一份通用版系统提示词。
- Kimi 更适合做标题、策略和提示词整理，不建议作为最终生图主力。
- 最终生图优先使用 GPT / Codex；豆包可作为备选，但要使用保守构图和人物锁定提示词。

## 简单判断

- 你在 Codex 里用：用 `$rick-xhs-cover-strategist`
- 你在 Claude / 豆包 / Kimi / DeepSeek / Hermes 里用：复制通用版 `.md` 全文
