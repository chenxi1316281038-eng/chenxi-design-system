---
name: chenxi-design-system
description: 为陈晞的个人网站、作品集、HR 求职内容、应用心理学文章、AI 陪伴产品介绍、教程页、Landing Page、图文卡片和公众号排版创建一致的前端视觉。使用 Lucion 个人 IP、明亮嫩绿色和现有组件模板；当任务涉及这些页面或内容配图时使用。
---

# Lucion 个人设计系统

> 改编自 [Esther Design System](https://github.com/esthersjw/esther-design-system)，原作者 ESTHER不二（esthersjw），采用 CC BY-NC-SA 4.0。保留署名、非商用和同协议分享要求。

## 工作流

1. 确认交付类型、受众、内容、页数和硬约束；信息不足时做最少必要追问。
2. 先读 `brand-dna.md`；再按类型读一个场景文件：教程 `references/scene-tutorial.md`、Landing `references/scene-landing.md`、App `references/scene-app.md`、图文卡片 `references/scene-cards.md`、公众号 `references/scene-wechat.md`。
3. 从 `assets/template-*.html` 复制对应模板，不从零搭通用页面。需要人物时使用 `assets/avatar.jpg` 或 `assets/character.png`，不得使用占位头像。
4. 从 `references/layouts.md` 选择 3–5 种布局；相邻 section 不重复。组件必须从 `references/components.md` 取用或按其风格补全，禁止浏览器默认的引用块、列表和表格。
5. 将模板变量保留为 `--blue / --yellow / --red`，它们已映射到 Lucion 的绿色体系；不要将旧变量名理解为蓝黄红。
6. 交付前按 `references/checklist.md` 自检，尤其检查角色一致性、绿色比例、留白、响应式和无默认 HTML 样式。
7. 交付可直接在浏览器打开的 HTML；图文卡片额外在 localhost 下验证导出。

## 资源速查

| 类型 | 场景规则 | 起始模板 |
|---|---|---|
| 教程 / 介绍 / 科普 | `references/scene-tutorial.md` | `assets/template-tutorial.html` |
| 活动 / 项目 / Landing | `references/scene-landing.md` | `assets/template-landing.html` |
| App / 功能原型 | `references/scene-app.md` | `assets/template-app.html` |
| 小红书 / 文章卡片 | `references/scene-cards.md` | `assets/template-cards.html` |
| 公众号 | `references/scene-wechat.md` | `assets/template-wechat.html` |

## 底线

- 保持 Lucion 的固定发型、浅绿蝴蝶发夹、嫩绿外套、暖白底和手绘蜡笔感。
- 画面清新明亮且留白充足；不生成写实、3D、复杂背景、蓝紫霓虹或诊断式心理承诺。
- `references/components.md` 是保留的通用组件库，不为一次页面任务修改它的结构。
