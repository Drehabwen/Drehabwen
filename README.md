<div align="center">

# Drehabwen

**让康复医学拥有可记录、可解释、可协作的 AI 基础设施。**  
**Building explainable, collaborative AI infrastructure for rehabilitation medicine.**

</div>

---

## 我在做什么 | What I Build

我关注的是康复医学与医疗 AI 的交汇处：把一次性的体格检查、运动观察、语音记录、科研证据和家庭随访，转化为可以被追踪、复核、解释和继续迭代的系统。

I work at the intersection of rehabilitation medicine and medical AI: turning physical examination, motion observation, clinical voice, research evidence, and family follow-up into systems that can be tracked, reviewed, explained, and improved.

The current work centers on **DeepRehab / Drehab**: motion assessment, clinical voice structuring, medical agent workflows, and practical products for rehabilitation screening, pediatric spine-health follow-up, and medical research.

---

## 长期愿景 | North Star

医学 AI 不应该只是更会聊天的界面。它应该帮助临床团队和家庭更清楚地看见问题、更稳定地执行计划、更可靠地积累证据。

Medical AI should not be only a better chat interface. It should help clinicians and families see problems more clearly, execute care plans more consistently, and accumulate evidence more reliably.

```text
screening data
-> structured evidence
-> clinical reasoning support
-> family-side execution
-> research feedback
-> reproducible AI workflows
```

```text
筛查数据
-> 结构化证据
-> 临床推理支持
-> 家庭侧执行
-> 科研反馈
-> 可复现 AI 工作流
```

---

## 技术地图 | Technical Map

| Layer 层级 | Direction 方向 | Representative Projects 代表项目 |
| --- | --- | --- |
| Technical Labs 技术实验层 | Motion metrics, clinical voice, medical agent guardrails | [rehab-motion-lab](https://github.com/Drehabwen/rehab-motion-lab), [clinical-voice-pipeline](https://github.com/Drehabwen/clinical-voice-pipeline), [medical-agent-workflow-lab](https://github.com/Drehabwen/medical-agent-workflow-lab) |
| Product Systems 产品系统层 | Rehabilitation screening, family follow-up, medical research workbench | [RehabScreenLab](https://github.com/Drehabwen/RehabScreenLab), [RehabGPT-](https://github.com/Drehabwen/RehabGPT-), [Galen](https://github.com/Drehabwen/Galen), [RehabHub](https://github.com/Drehabwen/RehabHub) |
| Workflow Tools 工作流工具层 | AI video production, paper processing, Codex skills, reproducible pipelines | [ai-video-production-pipeline](https://github.com/Drehabwen/ai-video-production-pipeline), [Openrehab-vibepaper-read](https://github.com/Drehabwen/Openrehab-vibepaper-read) |

---

## 重点项目 | Featured Work

### [Galen](https://github.com/Drehabwen/Galen)

Rust/Tauri medical research workbench with multi-model routing, PubMed/MeSH retrieval, citation formatting, and agent-runtime infrastructure.

一个面向医学科研的 Rust/Tauri 工作台：多模型路由、PubMed/MeSH 检索、引用格式化和 agent runtime 基础设施。它更像是我对“医学研究工作流应该如何被 AI 重构”的一次长期实验。

### [RehabScreenLab](https://github.com/Drehabwen/RehabScreenLab)

Field rehabilitation screening system for posture symmetry, squat assessment, Adams testing, and cross-protocol reports.

面向现场康复筛查的系统：姿态对称性、深蹲评估、Adams 前屈测试和跨协议报告。它承载的是一个更朴素的目标：让康复评估从经验观察，变成可以复核的证据链。

### [rehab-motion-lab](https://github.com/Drehabwen/rehab-motion-lab)

Rehabilitation motion metrics, joint angles, symmetry indices, and screening evidence primitives.

康复运动指标实验室：关节角度、对称性指数、筛查证据原语。它是产品背后的技术底座。

### [clinical-voice-pipeline](https://github.com/Drehabwen/clinical-voice-pipeline)

Clinical dictation structuring: transcript normalization, section detection, and export-ready records.

临床语音结构化管线：转录归一化、段落识别、可导出的病历记录。目标是让临床表达从“说过了”变成“可使用”。

### [medical-agent-workflow-lab](https://github.com/Drehabwen/medical-agent-workflow-lab)

Auditable medical AI agent workflows with evidence packets, guardrail checks, and clinician-review boundaries.

可审计的医学 AI agent 工作流：证据包、护栏检查、临床审核边界。重点不是让模型替医生做决定，而是让模型的每一步更可查。

---

## 我相信什么 | Working Principles

- **Evidence before answers.** 先有证据，再有结论。
- **Clinicians stay in the loop.** AI 应该增强临床判断，而不是绕开临床判断。
- **Products must survive real workflows.** 工具必须经得起真实工作流，而不只是演示视频。
- **Families are part of rehabilitation.** 康复不是一次评估，而是长期执行和反馈。
- **Research and product should feed each other.** 科研与产品不应割裂，证据应该回到系统里。

---

## 正在探索 | Current Questions

- How can motion assessment become reliable enough for routine rehabilitation screening?  
  运动评估如何变得足够可靠，以进入常规康复筛查？

- How can clinical voice be transformed into structured, reviewable records?  
  临床语音如何变成结构化、可复核的记录？

- How should medical agents expose evidence, uncertainty, and responsibility boundaries?  
  医学 agent 应该如何呈现证据、不确定性和责任边界？

- How can family-side rehabilitation follow-up become measurable and humane?  
  家庭侧康复随访如何同时做到可量化和有人味？

---

## 方向 | Direction

我希望做出的不是一个又一个孤立应用，而是一组能连接临床、家庭、科研与 AI 工作流的基础设施。

I am not trying to build isolated apps. I am trying to build infrastructure that connects clinical practice, family-side care, medical research, and reproducible AI workflows.

The goal is not to replace clinicians. The goal is to help people capture better information, make better decisions, follow through on plans, and communicate with more clarity.

目标不是替代医生，而是帮助人们更好地记录信息、形成判断、执行计划，并更清楚地沟通。
