# CS146S · 现代软件开发者

斯坦福大学 **The Modern Software Developer** 的中文图解学习书，按 **Fall 2026** 官网课纲分成 10 章。从看懂一次工具调用开始，用同一个本地任务板走完规范、测试、评审、安全、后台执行和团队运营。第 10 周按官网预告编写，截至 2026 年 11 月 26 日，12 月的两节课尚未开讲。 [课程官网](https://themodernsoftware.dev/) · [Stanford Bulletin](https://bulletin.stanford.edu/courses/cs-146s)

![学习路线从单个编程代理走向团队开发系统](Chapters/ch10/image/course-map.svg)

## 课程目录

| 章节 | 主题 | 动手完成 |
| --- | --- | --- |
| [01 · 拆开一个编程代理](Chapters/ch01/README.md) | LLM、工具调用与代理循环 | 离线跑通工具调用，比较成功与提前耗尽预算 |
| [02 · 上下文工程与 MCP](Chapters/ch02/README.md) | RePPIT、规格驱动、MCP 工具设计 | 写出状态筛选规格及只读工具契约 |
| [03 · Agent Skills 与命令行](Chapters/ch03/README.md) | SKILL.md、渐进加载、CLI | 把任务板检查流程做成可复用 Skill |
| [04 · 定制代理和仓库](Chapters/ch04/README.md) | 仓库指令、Hooks、角色分工 | 为实现和评审设置共同约束及检查入口 |
| [05 · 让代码库适合代理协作](Chapters/ch05/README.md) | 仓库入口、确定性验证、就绪审计 | 从干净检出复跑并修复一个协作障碍 |
| [06 · 用代理辅助代码评审](Chapters/ch06/README.md) | 证据链、分层评审、人工复核 | 针对一个打印顺序回归写出可验证评审意见 |
| [07 · 给开发代理划安全边界](Chapters/ch07/README.md) | SAST、SCA、秘密扫描、权限与信任边界 | 做一次只读权限和日志脱敏检查 |
| [08 · 后台代理与异步开发](Chapters/ch08/README.md) | 任务状态、工作树、重试与交接 | 模拟重复投递、并行冲突和陈旧任务 |
| [09 · 把开发流程做成软件工厂](Chapters/ch09/README.md) | 交付状态机、回滚、遥测和评估 | 在桌面演练中用发布证据和健康信号做决定 |
| [10 · AI 原生团队与未来](Chapters/ch10/README.md) | MCP 门户、模型网关、成本和工程判断 | 为团队设计试点并完成结课演练 |

从[前言](Chapters/PREFACE.md)了解实验项目和读法，或直接运行[第 1 章的 Python 实验](Chapters/ch01/README.md#3-离线跑完第一圈)。

## 课程资料

- **Fall 2026 主线**　官网打开 **Syllabus** 查看逐周主题、阅读材料和课件。部分课件需要课程权限。 [2026 课程官网](https://themodernsoftware.dev/)
- **公开课堂文字记录**　第 1、2 周有关于代理结构、上下文和 MCP 的文字记录。 [9 月 24 日](https://themodernsoftware.dev/materials/9-24-26-transcript.txt) · [9 月 29 日](https://themodernsoftware.dev/materials/9-29-26-transcript.txt) · [10 月 1 日](https://themodernsoftware.dev/materials/10-1-26-transcript.txt)
- **官方作业与往年课纲**　以各自版本的课程页面为准核对周次。书中的 Taskboard 是自学用的独立练习。 [课程作业仓库](https://github.com/mihail911/modern-software-dev-assignments) · [Fall 2025 归档](https://themodernsoftware.dev/fall2025)
