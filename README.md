<div align="center">

# Drehabwen · DeepRehab

**运动康复 × 生物医学工程 × AI**<br>
Building explainable, longitudinal AI infrastructure for rehabilitation medicine.

</div>

## 我在做什么

我关注运动康复与医疗 AI 的交汇：把动作观察、功能评估、生理信号、临床记录和家庭随访，组织成能够持续追踪、复核和改进的证据。

```text
采集与筛查 → RehabID 时间轴 → 专业人员复核 → 康复计划
      ↑                                        ↓
      └──────── 家庭执行 ← 患者端 ← 报告与随访 ────────┘
                         ↓
                 Galen 科研分析与成文
```

我的长期问题是：如何让康复从一次性评估，变成连续、可计算、可解释、能支持下一步决策的过程。

## 项目地图

| 层级 | 项目 | 作用 |
| --- | --- | --- |
| 康复师工作台 | [Rehab](https://github.com/Drehabwen/Rehab) | 接诊、体态/ROM 评估、报告、数据与前后对比 |
| 患者端 | [RehabGPT-](https://github.com/Drehabwen/RehabGPT-) | 家庭任务、训练打卡、结果查看与持续陪伴 |
| 现场筛查 | [RehabScreenLab](https://github.com/Drehabwen/RehabScreenLab) | 姿态、深蹲、Adams 筛查与跨协议证据 |
| 科研工作台 | [Galen](https://github.com/Drehabwen/Galen) | 检索、证据提取、数据分析、写作与科研闭环 |
| 指标实验层 | [rehab-motion-lab](https://github.com/Drehabwen/rehab-motion-lab) | 关节角度、对称性指标与可复现计算 |

这些项目不是彼此孤立的应用，而是围绕同一条链路协作：

```text
动作/量表/生理数据 → RehabID → 工作台复核 → 患者执行 → 复查比较
                                  ↘ Galen：证据、研究与报告
```

## 代表项目

### [Rehab · 康复师工作台](https://github.com/Drehabwen/Rehab)

面向康复师的评估与随访工作台，包含体态分析、ROM 评估、语音接诊、报告中心、数据中心和前后对比。重点是把多个评估插件放回同一个患者和时间轴中。

技术：React、TypeScript、Vite、FastAPI、SQLite、MediaPipe、Zustand。

### [RehabGPT- · 小柱患者端](https://github.com/Drehabwen/RehabGPT-)

连接诊室与家庭的患者/家长端助手：承接康复师制定的任务，支持训练打卡、结果查看和持续对话，让康复计划真正回到日常执行。

技术：React、TypeScript、Vite、Node.js、FastAPI、SQLite、WebSocket。

### [RehabScreenLab · 现场康复筛查](https://github.com/Drehabwen/RehabScreenLab)

面向现场筛查的 Web/Android 系统，支持静态姿态、深蹲和 Adams 前屈测试，并将采集质量、计算指标和原始证据整理成可复核报告。

技术：React、TypeScript、Vite、Capacitor、FastAPI、MediaPipe。

### [Galen · 康复科研闭环工作台](https://github.com/Drehabwen/Galen)

面向康复科研团队的执行型工作台：将任务拆解为计划、检索、证据提取、数据分析、写作和审核节点，并保留来源、执行过程与项目记忆。

技术：Rust/Tauri、科研 Agent、PubMed 检索、证据链、可复现工作流。

### [rehab-motion-lab · 动作指标实验层](https://github.com/Drehabwen/rehab-motion-lab)

围绕关节角度、姿态对称性和风险分带建立可测试、可比较、可复现的计算原语，为筛查端和工作台提供指标基础。

## 研究与验证

- **运动疲劳与传感器基线审计**：使用直接观测的 Borg RPE 和受试者留一法，检验哪些疲劳信号可以在线部署，避免时序信息泄漏。
- **FMS Auto-Scorer**：基于公开康复骨架数据探索功能性动作筛查自动评分，包含数据隔离、基线模型、实验协议和论文图表。
- **Clinical-Agent-Eval-Lab**：关注康复 Agent 的证据覆盖、不确定性表达和专业人员复核流程。

## 项目演进

```text
rehabAIfms（手机端深蹲反馈原型）
        → 动作指标与可复现计算
        → RehabScreenLab（现场筛查）
        → Rehab（康复师工作台）+ RehabGPT-（患者端）
        → RehabID + Galen（跨场景数据与科研闭环）
```

早期原型保留为成长轨迹；当前开发集中在可复用的数据协议、真实工作流和纵向验证。

## 我正在验证的问题

- 动作和生理指标如何形成稳定的个体基线？
- 筛查结果怎样成为可复核的证据，而不是一个孤立分数？
- 家庭训练如何被记录、反馈，并回流到下一次专业评估？
- 科研 Agent 怎样同时做到直接执行、来源透明和结果可复现？

## 工作原则

- **Evidence before answers.** 先建立证据，再形成结论。
- **Real workflows over demos.** 软件要经得起真实工作流，而不只是演示。
- **Research and product feed each other.** 指标、评测和使用反馈相互校正。

更多实验项目与历史原型见我的 [Repositories](https://github.com/Drehabwen?tab=repositories)。
