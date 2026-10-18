# AGENTS.md — 给 AI Agent 的工作指引

本文件面向自动化 AI Agent。人类读者请看 [README.md](README.md)。

## 这个仓库是什么

`traceability-audit-team` 是一个 **多 Agent Skill 发布包**，核心资产是 `SKILL.md`（三角色分工 + 三锚核验法 + 标准 SOP）。把本目录放入 Agent 技能目录，即可获得「对 AI 主体 / 数字人 / 宣称身份做溯源审计」能力。

## 可用的工作命令

```bash
cat SKILL.md                                  # 三角色 / 三锚核验 / SOP 全文
cat references/audit-report-template.md        # 审计报告模板
cat references/evidence-chain-checklist.md     # 证据链核查清单
cat references/standards-map.md               # 标准地图
```

前置依赖：无运行时依赖（纯文档 / 模板型技能）；标准引用前需联网查证最新条款。

## 约定（Do）

- 修改 `SKILL.md` 时保持 YAML frontmatter 字段兼容（`name` / `version` / `license` / `author` 等）。
- 引用任何法规 / 标准条款时，必须注明版本号并先联网查证，不凭记忆。
- 三锚核验必须产出证据链清单；证据不足标「无法判定」，不硬下结论。

## 禁止（Don't）

- 不要改动 `LICENSE.md` 的版权主体（© 2026 注册老炮），也不要改 `SKILL.md` 的 `author` 字段。
- 不要在审计报告中把本技能结论表述为法律意见或专业审计意见。
- 不要在仓库内提交任何密钥、令牌或真实个人身份信息。
- 不要声称本技能「已认证 / 已商用交付」。

## 边界

本技能专注**身份溯源与证据链审计**；不覆盖内容安全审查、不覆盖财务审计、不替代律师 / 专业审计机构的正式意见。
