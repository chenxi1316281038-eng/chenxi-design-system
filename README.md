# Lucion 个人设计系统

陈晞的个人品牌设计 Skill：让 AI 为个人网站、作品集、HR 求职内容、应用心理学文章与 AI 陪伴产品持续输出同一套视觉语言。

核心是把已确定的审美转为可执行规则：明亮嫩绿、暖白留白、温和但清晰的表达，以及 Q 版手绘个人 IP「Lucion」。

## 已配置内容

- `brand-dna.md`：颜色、字体、气质、构图与禁忌。
- `assets/avatar.jpg`：用于署名、作者区和小头像的 Lucion 头像。
- `assets/character.png`：用于 Hero 与项目叙事的角色母版。
- `assets/template-*.html`：已映射到本品牌色板的五类页面起点。
- `references/`：场景规范、布局、组件库与质量检查。
- `SKILL.md`：供 AI 读取的工作流。

## 快速使用

将整个目录放入 Codex 可读取的技能目录，例如：

```text
~/.codex/skills/chenxi-design-system/
```

然后直接说：

> 使用 Lucion 个人设计系统，为我的 AI 陪伴产品做一个清新明亮的项目介绍页。

AI 会先读取 `brand-dna.md` 和对应场景规范，再从 `assets/template-*.html` 开始搭建。组件库 `references/components.md` 保持上游结构不动，以便长期复用。

## 品牌速览

| 元素 | 规范 |
|---|---|
| 主色 | 嫩叶绿 `#B4D878` |
| 支持色 | 柔叶绿 `#E4F3BF`、蜂蜜黄 `#FFD77B`、腮红粉 `#F4B6AB` |
| 背景 / 文字 | 暖白 `#FFFDF4` / 炭灰 `#3E4239` |
| 标题 / 正文 | Noto Serif SC / Noto Sans SC |
| 角色 | Lucion：深色侧分短发、浅绿蝴蝶发夹、嫩绿外套、笔记本与叶脉背包 |
| 气质 | 清新、明亮、温暖、观察、陪伴、可信赖 |

## 许可证与署名

本仓库是 [Esther Design System](https://github.com/esthersjw/esther-design-system) 的改编版本。原作者为 **ESTHER不二（esthersjw）**；具体改动见 [NOTICE.md](NOTICE.md)。

本项目继续采用 [CC BY-NC-SA 4.0](LICENSE)：

- 需保留原作者署名；
- 不可商用；
- 改编版本必须以相同协议分享。
