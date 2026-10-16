# Policy Grounded Theory · 政策文本扎根理论 Skill

面向政策文本质性研究的可复用工作流，支持条款编码、持续比较、理论抽样、备忘录、制度与执行双源比较及饱和度评估。

## 安装

下载本仓库，将其内容放入你的 skill 目录下的 `policy-grounded-theory/` 文件夹。确保 `SKILL.md`、`references/` 和 `evals/` 保持相对位置。

Codex 的常用目录为 `~/.codex/skills/policy-grounded-theory/`。其他支持 `SKILL.md` 的工具请使用各自的 skill 安装位置。无需 Python 包或额外的通用扎根理论 skill。

## 使用

在支持显式调用的工具中输入 `$policy-grounded-theory`，并提供研究问题、政策文本及已有分析状态。例如：

> 使用 $policy-grounded-theory 对以下政策条款进行试编码。请保留原文与条款锚点，区分原文证据、分析判断和待讨论问题，最后给出下一轮理论抽样建议。

方法取向、敏感性概念和保存位置均可由研究者指定。本工具不预置研究结论，也不保证仅凭 AI 编码即可达到理论饱和。

## 文件

- `SKILL.md`：入口、证据规则与迭代流程。
- `references/coding-workflow.md`：编码、抽样、跨源比较与饱和度操作细节。
- `references/output-templates.md`：可选择使用的中文记录模板。
- `references/source-skill-notes.md`：借鉴来源与改造范围。
- `evals/evals.json`：人工评估用例；未宣称完成行为评估。

## 来源与许可

借鉴来源及改造说明见 [来源说明](references/source-skill-notes.md)。本仓库原创贡献按 [MIT License](LICENSE) 提供；上游作品的许可仍归各自声明管辖。
