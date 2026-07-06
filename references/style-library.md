# XHS Cover Style Library

Use this reference when the user needs to choose a cover style or when a repeated chat starts producing covers that look too similar.

## How to Offer Styles

Recommend 3 styles first, but always show the full 12-style list so the user can choose freely.

Use one combined choice step:

```text
请选择这张封面的风格。AI 根据你的内容先推荐 3 个，但你也可以从完整 12 个里任选。

AI 推荐：
- 2. 巨字拆分冲击风：适合……
- 4. 商业顾问杂志风：适合……
- 8. 工具流程信息图风：适合……

完整风格库：
1. 爆款大字压顶风
2. 巨字拆分冲击风
3. 痛点红标警示风
4. 商业顾问杂志风
5. 访谈人物海报风
6. 白板框架讲解风
7. 产品界面主视觉风
8. 工具流程信息图风
9. 深色效率工作流风
10. 教程清单风
11. 小白科普问答风
12. 案例结果证明风

选择方式：
- 按视觉形式选：回复风格编号，例如 4
- 按内容用途选：回复用途，例如“课程教程”“产品测评”“案例结果”“个人IP”
- 想延续上一张：回复“延续风格”
- 想换掉上一张：回复“换个风格”
```

## Style List

### 1. 爆款大字压顶风

- Best for: 強痛点、強结果、泛流量内容.
- Visual form: top half dominated by huge Chinese title, person or material below/side.
- Title behavior: 4-8 characters, direct, high contrast, thick outline.
- Avoid: long subtitles, too many cards, overly formal color.

### 2. 巨字拆分冲击风

- Best for: strong opinions,反常识, one-sentence conclusion.
- Visual form: title split into 2-3 massive word blocks, person as credibility anchor.
- Title behavior: each line has one visual punch word.
- Avoid: using it for gentle or trust-heavy content.

### 3. 痛点红标警示风

- Best for: mistakes, traps, warnings, “别再...” topics.
- Visual form: warning label, red marker, strike-through, alert tag.
- Title behavior: negative or corrective hook.
- Avoid: making it too scary for premium consulting brands.

### 4. 商业顾问杂志风

- Best for: consulting, B2B, founder IP, professional services.
- Visual form: clean portrait, restrained typography, proof card or framework card.
- Title behavior: strong but credible, not too noisy.
- Avoid: cheap sticker effects and exaggerated social-media noise.

### 5. 访谈人物海报风

- Best for: personal IP, opinions,口播, founder perspective.
- Visual form: large person photo, quote-like title, identity label.
- Title behavior: like a sharp quote or one-line judgment.
- Avoid: letting materials overpower the person.

### 6. 白板框架讲解风

- Best for: methods, frameworks, teaching, business logic.
- Visual form: person beside whiteboard/framework, clear boxes/arrows.
- Title behavior: “X步”“一套系统”“问题在这里”.
- Avoid: too many small labels or unreadable process maps.

### 7. 产品界面主视觉风

- Best for: product demos, SaaS, tool reviews, prototype launches.
- Visual form: product screenshot/prototype as the main proof, person as secondary.
- Title behavior: result or use-case driven.
- Avoid: raw screenshots that are too dense or unreadable.

### 8. 工具流程信息图风

- Best for: tool chains, workflows, automation, process explanation.
- Visual form: cards, arrows, step blocks, tool icons, clean system diagram.
- Title behavior: “从A到B”“自动化流程”“一套跑通”.
- Avoid: turning the whole cover into a tiny infographic.

### 9. 深色效率工作流风

- Best for: AI tools, productivity, technical workflows, premium tool content.
- Visual form: dark background, glowing cards, dashboard/workflow elements.
- Title behavior: concise, high contrast, often white/orange/blue.
- Avoid: making every cover dark; use when the topic needs efficiency or tech feel.

### 10. 教程清单风

- Best for: step-by-step tutorials, checklists, beginner guides.
- Visual form: title plus 3-5 checklist items, person or product as support.
- Title behavior: “X步”“清单”“新手先看”.
- Avoid: more than 5 bullet points.

### 11. 小白科普问答风

- Best for: beginner education, common misconceptions, Q&A content.
- Visual form: question bubble, simple contrast, friendly person expression.
- Title behavior: asks a clear question or answers a basic confusion.
- Avoid: too much jargon.

### 12. 案例结果证明风

- Best for: case studies, data results, before/after, testimonials.
- Visual form: result number, before/after block, proof screenshot or case card.
- Title behavior: result-first or contrast-first.
- Avoid: exposing private data; anonymize cases and screenshots.

## Content Use Mapping

When the user chooses by content use instead of style number, map as follows:

- 产品测评 / 工具推荐: 7, 8, 9, 1
- 课程教程 / 方法论: 6, 10, 11, 4
- 咨询服务 / B2B / 老板增长: 4, 5, 6, 12
- 个人IP / 观点口播: 5, 2, 4, 1
- 案例复盘 / 结果证明: 12, 4, 3, 8
- 小白入门 / 科普答疑: 11, 10, 1, 6
- 强痛点 / 强警示: 3, 1, 2, 5

## Repetition Control

In a continuous session, remember the last selected style.

- If the user says “延续风格”, keep the last style and do not ask again unless the new topic clearly conflicts.
- If the user repeatedly generates covers without specifying style, recommend 1-2 different styles after the second similar cover.
- If the user says “换个风格”, recommend 3 alternatives that are visually different from the last style.
- Do not nag the user about repetition. Mention it once, then follow their preference.
