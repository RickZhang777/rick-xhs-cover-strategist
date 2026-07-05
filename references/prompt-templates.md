# Prompt Templates

Use these as structures. Fill in concrete details; do not leave placeholders in final output.

## Standard 3:4 Prompt Structure

```text
使用参考图1作为人物主参考，最大程度保持原图人物本人身份一致：脸型、五官比例、眼镜、发型、年龄感、气质、身材比例和服装都贴近原图，不要美化成另一个人，不要重绘成陌生脸。真人半身出镜。人物位于画面[位置]，占画面约[比例]，表情[表情]，动作[动作]，脸部清晰不被遮挡。

如果生图模型容易改变人物长相，则优先保持参考图1中的人物原形象，必要时可以近似 100% 保留原图人物，只重新设计背景、标题文字、卡片和辅助素材。

这是 3:4 竖版小红书封面，主题是[主题]，目标人群是[人群]。封面主标题必须原样显示为“[标题]”，中文超大粗体，强对比配色，[描边/底板/阴影]，在手机瀑布流缩略图中也清晰可读。

参考图2作为[产品/原型/截图/证明材料]，放在[位置]，以[卡片/手机样机/倾斜截图/背景墙]形式出现；如果还有参考图3，将其作为[用途]。素材辅助说明主题，不遮挡人物脸部和主标题。

整体风格为[高点击冲击/专业可信/产品展示/人设强化/测评对比]，背景为[背景]，颜色以[主色]、[强调色]、[描边色]为主，画面高对比、有层次，信息密度适中。

加入少量[标签/箭头/清单/评分/栏目标签]强化点击理由，文字短而清楚。所有重要文字、人物脸部、产品关键区域都在安全区内。

质量要求：人物自然真实，必须像参考图本人，不要换脸，不要改变核心面部特征，不要脸部变形，不要身体拉伸，不要多手指、断手、融合手，不要标题遮住眼睛和嘴巴，不要产品截图糊成一团，不要出现乱码文字，不要低对比细字，不要杂乱广告感。
```

## Doubao Conservative Prompt Add-on

Use this when the user will generate in Doubao or any model that easily changes the face:

```text
人物必须沿用参考图原始人物，不要重新生成另一张脸；保持原图脸型、五官、眼镜、发型、年龄感和真实气质，必要时直接保留原图人物，只替换背景、标题和卡片元素。

构图保持简单：一个主标题、一个人物、一个证明卡片、最多一个辅助小标题。不要复杂装饰，不要多层半透明效果，不要大量小字标签。人物完整清晰，不裁掉半张脸，不把脸融进背景。
```

## Kimi Usage Note

Use Kimi for prompt drafting, strategy, and copy refinement. Avoid relying on Kimi as the final image generator when person likeness matters. If the user insists on Kimi image generation, use the Doubao conservative add-on and reduce layout complexity further.

## Professional Consulting Variation

Use when trust matters more than loudness.

- Person should look calm, confident, and competent.
- Background can be office, dashboard, framework board, or blurred delivery material.
- Title should still be large, but not messy.
- Add identity label only if it improves trust.

## Product or Prototype Variation

Use when product material is the strongest proof.

- Put product screenshot in a phone or desktop mockup.
- Enlarge only the most meaningful section.
- Add 1-3 callout tags.
- Avoid tiny UI text as the main selling point.

## Review or Comparison Variation

Use when the title contains numbers or comparison.

- Use product cards, ranking labels, or score tags.
- One big number can become the second visual anchor.
- Keep product names/logos readable but secondary to title.

## Past Cover Consistency

If the user uploads past covers:

- Reuse title color logic, outline style, recurring label, and rough hierarchy.
- Do not copy every detail if it hurts the new cover's clarity.
- Mention continuity explicitly in the visual plan and prompt.
