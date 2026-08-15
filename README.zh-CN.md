# Austrian Judgment Protocol

**面向创始人、CEO、CTO 的生产级判断框架——奥地利学派六大可执行协议，由 AI agent 作为判断参谋调用。**

![License](https://img.shields.io/github/license/gootf/austrian-judgment-protocol)
![Release](https://img.shields.io/github/v/release/gootf/austrian-judgment-protocol)
![Stars](https://img.shields.io/github/stars/gootf/austrian-judgment-protocol)

大多数商业框架回答"如何规划"。这套回答更难的问题：**谁来判断、何时、依据什么**——在投入资本、回应竞对、下放决策、押注新市场之前。

它不是知识库，是判断协议：理论被压缩为可执行决策程序、反模式和证据坐标；84 条 claim 全部可溯源到 9 本原著。完整链条是：**人类决策者做判断 → AI 作为判断参谋加载协议 → 输出结构化检查、反模式审计、证据坐标**。

## 目标客户

| 你是谁 | 你的决策 | 协议做什么 |
|---|---|---|
| **创始人** | 机会是真是假？需求是否存在？现在投入还是分期投入？ | 需求侧三阶段检验；资本家的三重判断；分期投入 + 预定义 kill criteria |
| **CEO** | 竞对响应、战略评审、目标设定、组织设计 | 先诊断再行动；战略内核检查；不对称审计；拒绝目标谬误 |
| **CTO / 技术负责人** | 技术债 vs 功能速度、向团队或 agent 授权、架构 vs 业务探索 | 判断权分类（原创 vs 派生）；知识分布；能力边界检查 |
| **AI agent 开发者** | 把判断能力嵌入 agent 工作流 | 可执行决策程序 + 反模式 + 可溯源证据坐标——不是自由文本式建议 |

## 它解决什么

| 处境 | 常见做法（以及陷阱） | 协议做法 |
|---|---|---|
| 销售下滑 | 归因于市场波动 | 先做弱信号检查（K04/KX03） |
| 竞对推出免费版 | 立即全面跟进 | 诊断真实威胁，从自身不对称回应（R01/R04） |
| 新业务、投入之前 | 全押，或永远"再多要些数据" | 三阶段需求检验；分期投入、预先定义 kill criteria（P003, UX01） |
| 技术很强的团队创新停滞 | 招更多专家 | Einstellung 审计：单一知识反而**降低**创新能力（P006/P007） |
| "这事该谁定？" | 按头衔，或嗓门最大的人 | 原创 vs 派生判断分类（FK02） |
| 总部报表总是失真 | 更多仪表盘、更多汇总 | 信息反过滤：采样原始现场（HX01） |

## 为什么是它

1. **不是又一个规划框架。** SWOT、OKR、波特回答"如何规划"，前提是判断已经给定。这套把判断本身作为对象：谁持有它、依据什么证据、它如何失败。
2. **不是读书笔记。** 理论压缩为可执行程序和反模式。84 条 claim 全部可溯源到 9 本原著（Kirzner、Mises、Hayek、Taleb、O'Driscoll & Rizzo、Rumelt、Foss & Klein、Packard、Christensen），并标注证据等级——`high` = 直接出自作者原文，`medium` = 框架推理。
3. **是一条判断链，不是工具箱。** 六个协议构成完整判断链：机会发现 → 需求验证 → 战略诊断 → 知识分布 → 判断权分配 → 不确定性设计。单独使用任何一个都不完整——这是设计，不是缺陷。
4. **生产级。** 版本化（v1.0.0）、claim 账本可机检、依赖交叉可追踪、每个协议明确范围与已知缺口。

## 怎么用

直接使用者是 **AI agent**（Hermes 技能格式）：你描述场景，agent 路由到对应协议，返回结构化检查、反模式审计和证据坐标。

- **安装**：将 `SKILL.md` 作为技能加载；六个协议在 `references/protocols/`
- **带场景提问**："分析这个竞对威胁"、"这事该下放决策吗"、"评估这个商业机会"——路由表在 SKILL.md
- **带主题提问**：`alertness` / `case probability` / `strategy kernel` / `man on the spot` / `original judgment` / `three-stage process`

## 快速开始

```bash
# 1. 获取 skill
git clone https://github.com/gootf/austrian-judgment-protocol.git
# 2. 把 SKILL.md + references/ 复制到你的 agent 技能目录
#    （如 ~/.claude/skills/austrian-judgment-protocol/ 或你所用 agent 的等价目录）
```

然后向 agent 提问——三种路由方式：

| 你问 | 你得到 |
|---|---|
| "竞对刚推出免费版，分析这个威胁。" | strategy-diagnosis：症状 vs 挑战、内核检查、不对称审计（R01/R04） |
| "现在该为新项目投入资本吗？" | consumer-sovereignty：三阶段需求检验、分期投入 + kill criteria（P003, UX01） |
| "这个决策能下放给团队吗？" | hayek-knowledge-problem：时间地点知识？可聚合？下放 + 协调（HX01） |

## 它刻意不做什么

- **不预测。** case probability 不可计算（Mises）；当未来是独特事件时，向你兜售预测的人卖的是叙事谬误（Taleb）。
- **不替代人类判断。** 原创判断不可外包（Foss & Klein）。框架的自我边界写在不确定性协议里：**AI 处理 puzzle，mystery 留给人类决策者**。
- **不是法律、财务或投资建议。**

## 结构

```
SKILL.md       伞形入口：路由表 + 用法
claims.yaml    84 条 claim，逐条可溯源（作者、书名、证据等级）
references/    协议 ×6 · 术语表 · 模式 ×10 · 速查表
```

## 来源

Kirzner · Mises · Taleb（×2）· O'Driscoll & Rizzo · Rumelt · Hayek · Foss & Klein · Packard · Christensen

## 许可

MIT License — 见 [LICENSE](LICENSE)。
