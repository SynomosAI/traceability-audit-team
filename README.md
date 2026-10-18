# traceability-audit-team · 溯源审计团

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)
[![Agent Skill](https://img.shields.io/badge/Agent%20Skill-SKILL.md-blue.svg)](SKILL.md)
[![Compliance Audit](https://img.shields.io/badge/compliance-audit-brightgreen.svg)](SKILL.md)
[![Evidence Chain](https://img.shields.io/badge/evidence--chain-3%20anchors-2ea44f.svg)](SKILL.md)
[![Multi-Agent](https://img.shields.io/badge/multi--agent-3%20roles-informational.svg)](SKILL.md)
[![Version](https://img.shields.io/badge/version-1.0.0-informational.svg)](SKILL.md)

SynomosAI 四支柱体系：**身份（Identity）· 溯源（Traceability）· 治理（Governance）· 共生（Symbiosis）**——当 AI 进入商业，可信是唯一的硬通货。

> 本仓库属于 [SynomosAI](https://github.com/SynomosAI) 生态技能包的一员。生态全景见 [`synomosai-skills`](https://github.com/SynomosAI/synomosai-skills)，理论站位见 [`traceability-audit`](https://github.com/SynomosAI/traceability-audit)。

**关键词 / Keywords**：AI 身份溯源 · 证据链审计 · 三锚核验 · 数字人身份 · 宣称身份核查 · 溯源审计报告 · AI compliance audit · provenance verification · evidence chain

一支由三位角色组成的「溯源审计团」，对 **AI 主体 / 数字人 / AI 生成内容 / 方案理论 / 宣称身份** 进行身份溯源与证据链审计，回答「**这个东西是谁的、从哪来的、能不能信**」。对标会计师事务所审计组范式：标准依据 → 证据链审计 → 报告成稿。

---

## ✨ 特性 / Features

- **三角色协同**：溯源官（主理 / 三锚核验）、定标人（标准依据：EU AI Act / ISO/IEC 42001 / W3C DID·VC / NIST AI RMF / GB/T 45081-2024）、执笔人（报告成稿）。
- **三锚核验法**：记忆锚（记得什么）、身份锚（自称是谁）、行为锚（做出来像不像）；任一锚断裂即记审计发现项。
- **证据链审计**：凭证签发方、来源链路、跨平台身份一致性逐条对照标准。
- **标准 SOP**：定标 → 取证 → 成稿三阶段，条款引用须注明版本号并先联网查证。
- **模板齐备**：审计报告模板、证据链核查清单、标准地图（见 `references/`）。

---

## 🚀 快速开始 / Quick Start

> 前置：把本目录放入你的 Agent 技能目录（如 `~/.workbuddy/skills/`）；标准引用前需联网查证最新条款。

```bash
# 1. 克隆本仓
git clone https://github.com/SynomosAI/traceability-audit-team.git
cd traceability-audit-team

# 2. 查看技能主文件（三角色 / 三锚核验 / SOP / 报告规范）
cat SKILL.md

# 3. 查看审计模板
cat references/audit-report-template.md
cat references/evidence-chain-checklist.md
```

拿到一个待溯源对象（某 AI 账号 / 某数字人 / 某宣称成果）后，按 `SKILL.md` 的三阶段 SOP 执行：先定标（适用条款），再三锚取证，最后按模板成稿。

```text
触发词示例：
  溯源 / 审计 / 溯源审计 / 三锚核验 / 证据链审计
  AI身份 / 数字人身份 / 宣称身份核查 / 溯源报告
```

---

## 📖 使用方式 / Usage

1. 克隆本仓库或将技能目录放入 Agent 技能目录；
2. 在 Agent 中按 `SKILL.md` 触发「溯源审计团」，由溯源官调度定标人、执笔人；
3. 需要审计 / 合规证据时，按 `references/` 模板产出工件。

### 三锚核验示例（节选）

```text
审计对象：某自称「行业资深专家」的数字人账号
  记忆锚：跨 3 个平台对从业年限陈述不一致（5 年 / 12 年 / 8 年）→ 断裂
  身份锚：所附「资质证书」签发方官网查无此证 → 断裂
  行为锚：输出风格与宣称资历明显不匹配，术语误用 → 可疑
结论：三锚两断 → 不可信；建议在报告中逐项列出证据链与发现项。
```

---

## 🧩 仓库结构 / Repository layout

```text
traceability-audit-team/
├── README.md                    # 本文件
├── README.en.md                 # 英文版说明
├── SKILL.md                     # 技能主文件（三角色 / 三锚核验 / SOP）
├── LICENSE.md                   # MIT License
├── llms.txt / llms-full.txt     # 给 AI 的索引与完整文本
├── AGENTS.md                    # 给 AI Agent 的工作指引
├── SECURITY.md                  # 安全策略
├── CODEOWNERS                   # 代码所有者
├── security-radar.svg           # 安全雷达图
├── security_results.json        # 安全扫描结果
├── 安全审计报告.md               # 本仓安全审计
└── references/
    ├── audit-report-template.md     # 审计报告模板
    ├── evidence-chain-checklist.md   # 证据链核查清单
    └── standards-map.md             # 标准地图（ISO/IEC 42001 等）
```

---

## 🔎 方法论 / Methodology

审计范式对标会计师事务所：**Phase 1 定标**（明确审计对象 / 范围 / 适用标准，条款注明版本号，先联网查证）→ **Phase 2 取证**（三锚核验 + 证据链审计，以定标条款为基准逐条对照）→ **Phase 3 成稿**（审计报告 / 白皮书章节）。三锚一致 + 证据链完整 → 可信；任一锚伪造或不可溯源 → 记入发现项并影响结论分级。

---

## ❓ 常见问题 / FAQ

- **能审计什么？** AI 主体、数字人、AI 生成内容归属、宣称身份 / 资历 / 成果的真实性。
- **标准引用凭记忆吗？** 不。定标人须先联网查证条款版本号（如 ISO/IEC 42001:2023、EU AI Act Art.X），不凭记忆。
- **审计结论是法律意见吗？** 不是。本技能为方法论与报告模板，正式合规决策请咨询专业律师 / 审计机构。

---

## License / 许可

本项目以 **MIT** 许可发布，详见仓库根目录 [LICENSE.md](LICENSE.md)。版权：© 2026 注册老炮。

---

## 🔒 安全 / Security

如发现安全问题，请按 [`SECURITY.md`](SECURITY.md) 的方式私下报告，不要在公开 issue 中披露。

## 🤝 贡献 / Contributing

欢迎补充标准地图、核查清单与报告模板；修改 `SKILL.md` 时保持 YAML frontmatter 字段兼容。代码所有者见 [CODEOWNERS](CODEOWNERS)。

---

## 免责声明

本仓库内容为 SynomosAI 的**理论站位与工具化探索**，不代表任何已获认证、已商业化交付或已服务特定客户的声明；文中涉及的 ISO/IEC 42001、EU AI Act、W3C DID·VC、NIST AI RMF、GB/T 45081-2024 等外部标准与条款信息为公开资料转述，正式引用前请**独立核实**。API、授权码与形象大使等为路线图（roadmap）事项，尚未上线。
