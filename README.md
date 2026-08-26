<div align="center">

# Drehabwen · DeepRehab

**让康复医学拥有可记录、可解释、可协作的 AI 基础设施。**  
**Building explainable, collaborative AI infrastructure for rehabilitation medicine.**

</div>

## 我在做什么 | What I Build

我关注康复医学与医疗 AI 的交汇：把一次性的运动观察、体格检查、临床记录和家庭随访，转化为能够被追踪、复核、解释和继续改进的系统。

I build rehabilitation AI systems that turn motion observations, clinical assessments, records, and follow-up into traceable and reviewable evidence.

```text
screening
  → structured evidence
  → clinician review
  → rehabilitation plan
  → family execution
  → follow-up and evaluation
```

AI 不替代医生。它应该帮助临床团队更稳定地获取信息、呈现证据、管理不确定性，并把康复计划真正延续到家庭和复查中。

## 当前主线 | Current Focus

| 层级 | 项目 | 作用 |
| --- | --- | --- |
| 临床工作台 | [QingYueRehabWorkbench](https://github.com/Drehabwen/QingYueRehabWorkbench) | 筛查接入、患者确认、多模态评估、报告与随访闭环 |
| 现场筛查 | [RehabScreenLab](https://github.com/Drehabwen/RehabScreenLab) | 姿态、深蹲和 Adams 筛查及跨协议证据 |
| 指标底座 | [rehab-motion-lab](https://github.com/Drehabwen/rehab-motion-lab) | 关节角度、对称性指标和可复现计算样例 |
| 可信评测 | [Clinical-Agent-Eval-Lab](https://github.com/Drehabwen/Clinical-Agent-Eval-Lab) | 临床 Agent 的证据、边界和系统评测 |

这些项目围绕同一条产品与研究链路工作，而不是彼此孤立的应用：

```text
rehab-motion-lab
        ↓
RehabScreenLab → QingYueRehabWorkbench
        ↓                 ↓
筛查证据          临床审核、报告与随访
        └── Clinical-Agent-Eval-Lab
```

## 项目起点 | Origin

[rehabAIfms](https://github.com/Drehabwen/rehabAIfms) 是我在 GitHub 上公开的第一个康复 AI 原型，始于 2025 年 9 月。它用 Expo、TensorFlow.js 姿态估计和关节角度计算探索手机端深蹲实时反馈。

它现在作为历史原型保留，不再承担主产品开发；但其中“动作如何变成可解释反馈”的问题，后来演化成 rehab-motion-lab、RehabScreenLab 和 QingYueRehabWorkbench。

## 重点项目 | Featured Work

### [QingYueRehabWorkbench](https://github.com/Drehabwen/QingYueRehabWorkbench)

青跃康复工作台是当前产品主线。它连接早筛接入、患者身份、多模态康复评估、报告就绪度、家庭任务和复查流程，并明确保留临床人工审核边界。

### [RehabScreenLab](https://github.com/Drehabwen/RehabScreenLab)

面向现场康复筛查的 Web 与 Android 系统。重点不是给出一个孤立分数，而是让采集质量、计算指标和原始证据能够对应，并进入后续康复工作流。

### [rehab-motion-lab](https://github.com/Drehabwen/rehab-motion-lab)

产品背后的动作指标实验层：关节角度、姿态对称性、风险分带与可解释证据原语。目标是让关键计算可以被测试、比较和复现。

### [Clinical-Agent-Eval-Lab](https://github.com/Drehabwen/Clinical-Agent-Eval-Lab)

面向临床与康复 Agent 的系统评测实验室，关注证据覆盖、不确定性表达、护栏和临床审核边界。

## 长期研究 | Long-term Exploration

### [Galen](https://github.com/Drehabwen/Galen)

Rust/Tauri 医学科研工作台，探索文献检索、论文阅读、引用管理、多模型路由和可复现科研 Agent 工作流。它是独立的长期研究方向，不取代康复产品主线。

## 工作原则 | Working Principles

- **Evidence before answers.** 先有证据，再有结论。
- **Clinicians stay in the loop.** AI 增强临床判断，不绕开临床判断。
- **Products must survive real workflows.** 工具必须经得起真实流程，而不只是一段演示。
- **Privacy is part of the architecture.** 患者数据保护不是发布前补上的功能。
- **Research and product should feed each other.** 指标、评测和真实使用反馈应互相校正。

## 当前验证问题 | Questions I Am Testing

- 动作评估怎样达到足够稳定的重测一致性？
- 筛查结果如何成为可复核的证据，而不是黑箱分数？
- 医疗 Agent 应怎样呈现证据、不确定性和责任边界？
- 家庭随访怎样同时做到可量化、可执行且有人味？

## 联系与协作 | Collaboration

欢迎围绕康复筛查、运动评估、临床工作流、医疗 Agent 评测与真实场景验证交流。具体项目状态、运行方式和医学边界请以各仓库 README 为准。
