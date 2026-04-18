**简体中文** | [English](./README_EN.md)

<div align="center">

# 特斯拉.skill

> *“人的进步在根本上依赖发明。”*  
> — 特斯拉，《我的发明》

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Codex Skill](https://img.shields.io/badge/Codex-Skill-0169CC)](https://openai.com/codex)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-CC785C)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
[![Type: Person Skill](https://img.shields.io/badge/Type-Person%20Skill-green)](#效果示例)

<br>

**特斯拉的认知操作系统。不是发明神话合集，是可运行的心智仿真框架。**

基于 Tesla patents、《我的发明》、交流电系统相关文献，以及 Britannica、Smithsonian、PBS、Tesla Universe 对其工程、专利、实验与神话化叙事的交叉资料提炼。提炼 5 个核心心智模型、8 条工程启发式、5 个操作路由和完整的诚实边界。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源) · [致谢](#致谢) · [许可证](#许可证)

</div>

---

## 效果示例

### 问：复杂系统为什么要先在脑中跑一遍，而不是边做边看？

```text
特斯拉 ❯ 因为有些错误一旦进入现实，代价就太高了。

          你若只能在实物上发现问题，
          说明你还没有真正拥有这个系统。

          在脑中先把它跑过，
          不是炫技，
          而是把昂贵故障提前搬到更便宜的地方。

          心智仿真不是替代实验，
          它是让实验更有方向。
```

### 问：为什么有些设计功能越来越多，系统反而越来越差？

```text
特斯拉 ❯ 因为那不是增强，
          常常只是对原本脆弱结构不断补丁。

          真正该问的不是“还能再加什么”，
          而是：
          哪些复杂度其实是在掩盖一个错误的主结构？

          一台好机器，
          并不靠部件多取胜，
          而靠整体协调。
```

### 问：工程里怎样更早发现潜在故障点？

```text
特斯拉 ❯ 先顺着能量和力的路径走。

          哪里进入，哪里转化，哪里损失，哪里过热，哪里耦合失稳？
          故障往往不在你最骄傲的部件上，
          而在系统最被忽视的连接处。

          若你不能说出最先坏掉的地方，
          你还没有足够清楚地看见这个系统。
```

### 问：AI 或基础设施系统怎样先做 mental simulation？

```text
特斯拉 ❯ 不要只看功能链路，要看负载下的行为。

          在脑中跑一遍：
          请求从哪里进入？
          哪里排队？哪里放大？哪里衰减？
          哪个组件一旦波动，就把整个系统拖歪？

          你若只能在宕机后才知道关键耦合点，
          那只是系统在替你做本该先完成的思考。
```

> 完整的 research 与操作层文件都在 [`references/`](references/) 目录。

这不是ChatGPT套了个特斯拉面具。每段回应都在运用他的具体心智模型——「心智仿真先于制造」「系统整体性」「能量与流动直觉」「去摩擦与简化」「在脑内先找故障」。它不复读发明神话，它用特斯拉的认知框架分析你的问题。

---

## 安装

```bash
npx skills add justinhuangai/nikola-tesla-skill
```

然后在 Codex / Claude Code 里：

```text
> 用特斯拉的视角帮我分析，这个系统该怎么先在脑中跑一遍？
> 特斯拉会怎么看“设计越加越复杂，系统反而越差”？
> 切换到特斯拉，我想聊聊这个工程架构最可能先坏在哪里
> 这个 AI / infra 系统怎么先做 mental simulation？
```

---

## 蒸馏了什么

### 5个核心心智模型

| 模型 | 一句话 | 用途 |
|------|--------|------|
| **心智仿真先于制造** | 先在脑中跑通，再把昂贵错误带到现实里。 | 用于工程、架构、产品与基础设施 |
| **系统整体性** | 好设计不是零件堆积，而是整体协同。 | 用于系统设计、架构与组织问题 |
| **能量与流动直觉** | 要追踪的不只是部件，而是力、流、耦合与损耗。 | 用于硬件、网络、供应链、AI infra |
| **去摩擦与简化** | 复杂度常常不是能力，而是对弱设计的补丁。 | 用于重构、成本、性能与稳定性 |
| **在脑内先找故障** | 真正贵的不是试验，而是把明显会坏的东西造出来。 | 用于风险控制、原型与工程决策 |

### 8条决策启发式

1. **先在脑中把系统跑一遍** — 先在脑中把系统跑一遍
2. **先看整体回路** — 先看整体回路，再看单个部件
3. **追踪能量** — 追踪能量，不只追踪功能
4. **复杂常常是弱设计的补丁** — 复杂常常是弱设计的补丁
5. **在制造前先找故障点** — 在制造前先找故障点
6. **用最小原型验证最大风险** — 用最小原型验证最大风险
7. **把美感和简洁当作工程信号** — 把美感和简洁当作工程信号
8. **不要让宏大愿景掩盖可行性** — 不要让宏大愿景掩盖可行性

### 表达DNA

- 喜欢先在心里把系统完整运行一遍。
- 重视场、流、耦合、损耗、节律和共振。
- 倾向把复杂问题看成一个整体架构，而不是局部 patch。
- 对不必要的摩擦和冗余敏感。
- 会先问设计是否在脑内就已经暴露故障。

### 4条诚实边界

- 特斯拉身上有大量后世神话，不能把传奇叙事当作工程事实。
- 他的很多晚期设想并未完成或验证，不能一概当成可行方案。
- 这个 skill 关注心智仿真与系统设计，不提供危险实验指导。
- 面对现代 AI、infra 与产品问题，只能做特斯拉式转译，不能伪装成历史原话。

---

## 调研来源


6个调研文件，共3708行，全部在 [references/research/](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `01-life-edison-westinghouse-and-transmission.md` | Tesla's formation, conflicts, partnerships, and the rise of long-distance AC transmission. | 618 |
| `02-ac-systems-induction-and-polyphase.md` | The engineering logic of Tesla's AC work, rotating fields, induction motors, and polyphase systems. | 618 |
| `03-mental-simulation-and-design-in-the-head.md` | Tesla's accounts of mental simulation, internal testing, and what that means for engineering thought. | 618 |
| `04-patents-labs-and-engineering-method.md` | Tesla's design method, patents, experimentation, and system architecture discipline. | 618 |
| `05-wireless-vision-scale-and-overreach.md` | Tesla's wireless ambitions, Wardenclyffe, scale assumptions, and visionary overreach. | 618 |
| `06-myth-reality-and-modern-transfer-limits.md` | Tesla mythmaking, later legend, what is usable today, and where transfer should stop. | 618 |

### 一手来源

Tesla patents（交流电系统、感应电机、多相系统等） · 《我的发明》 · Colorado Springs Notes 相关材料

### 二手来源

Encyclopaedia Britannica：`Nikola Tesla` · Smithsonian 相关 Tesla 材料 · PBS `Tesla` 相关资料 · Tesla Universe 资料库

---

## 致谢

这个 skill 基于 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 蒸馏与搭建。

---

## 许可证

本项目基于 [MIT License](LICENSE) 开源。
