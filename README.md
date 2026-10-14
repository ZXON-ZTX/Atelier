# Atelier · 网页与幻灯片设计

显示名称：**Atelier**。技能标识与目录名保持 `atelier`，显式调用为 `$atelier`。

用尽量少的沟通，制作完整、较为美观、方便继续修改的前端界面和演示文稿。
以 **90% 置信度意图门** 为核心：先读已有资产，六轴加权达到门槛才开始
最终设计；低于门槛每轮只问一个关键问题。明确委托则公开假设后直接做。

## 能力

- 网页：落地页、官网、作品集、产品页和后台界面，以及现有前端的美化。
- 幻灯片：路演、汇报、课件、发布会和学术演示。
- 设计参考：12 种网页风格、10 种网页布局、12 种幻灯片风格与多种页型。
- 90% 意图门：用途/场景、受众、风格、视觉锚点、布局/结构和参考六轴加权。
- 同品牌、同系列和修改稿保持一致；探索方案时才主动提供不同方向。
- 用户要求 PPT / PowerPoint / PPTX 时默认交付可编辑 PPTX。
  明确要求 HTML 或浏览器演示时采用 HTML。
- 质量检查以可读、可用和完整为主，审美微调适度，准确说明未验证项。

这是指令型 skill，生成 PPTX、预览网页、渲染页面等能力取决于宿主实际可用的工具。

## 安装

### 从 GitHub 安装

Codex / Windows PowerShell：

```powershell
git clone https://github.com/ZXON-ZTX/Atelier.git "$env:USERPROFILE\.agents\skills\atelier"
```

Codex / macOS 或 Linux：

```bash
git clone https://github.com/ZXON-ZTX/Atelier.git ~/.agents/skills/atelier
```

已有同名安装时先备份，再选择更新方式，避免覆盖本地修改。

### 从 ZIP 安装

在 [Releases](https://github.com/ZXON-ZTX/Atelier/releases) 下载 `Atelier.zip`。

新版 ZIP 包含顶层 `atelier/` 文件夹。解压后复制整个文件夹：

| 宿主 | 用户级目录 | 项目级目录 |
|---|---|---|
| Codex | `~/.agents/skills/atelier/` | `.agents/skills/atelier/` |
| Claude Code | `~/.claude/skills/atelier/` | `.claude/skills/atelier/` |
| DeepSeek Harness / 其他宿主 | 按宿主文档选择 skills 目录 | 按宿主文档 |

如果已经安装同名 skill，先备份再更新；不要创建第二个同名副本。
确认 `SKILL.md` 位于 `atelier/` 第一层，刷新技能列表或开启下一轮会话后使用。
旧版 ZIP 没有顶层目录时，先创建 atelier 文件夹，再将内容解压进去。

## 使用

可以直接描述任务，也可以显式指定 `$atelier`：

- “做一个 AI 会议助手落地页，面向企业团队，深绿米白、杂志风，直接做。”
- “做 10 页产品介绍 PPT，面向投资人，要可编辑 PPTX，内容基于附件，风格你定。”
- “沿用上次字体与配色，美化这份季度汇报，保留原数据。”
- “给我看两三个风格预览，我选一个。”
- “只调整这页的排版，不改内容。”

流程：读现有资料 → 90% 置信度意图门 → 设计确认单 → 制作 → 检查 → 交付。
不重复问已明确的交付类型；达到门槛后不额外等待一次形式批准。
置信度按六轴证据计算，表示设计意图确认程度，不是统计正确率。
用户明确委托时写“按用户委托通过”，说明重要假设；缺少必须引用的事实
数据或原文件时说明缺口，不靠评分或委托代替材料。

入口：[SKILL.md](SKILL.md)。详细用法：[使用说明.md](使用说明.md)。

## 灵感来源（致谢）

网页侧：[Nutlope/hallmark](https://github.com/Nutlope/hallmark) ·
[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) ·
[nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) ·
[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) · impeccable

幻灯片侧：[op7418/guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) ·
[zarazhangrui/frontend-slides](https://github.com/zarazhangrui/frontend-slides) ·
[chuspeeism/dashi-ppt-skill](https://github.com/chuspeeism/dashi-ppt-skill) ·
[crazyykhllc-bit/CyberPPT](https://github.com/crazyykhllc-bit/CyberPPT) ·
[Gabberflast/academic-pptx-skill](https://github.com/Gabberflast/academic-pptx-skill) ·
[likaku/Mck-ppt-design-skill](https://github.com/likaku/Mck-ppt-design-skill)

本项目按原包声明采用 [MIT License](LICENSE)。
