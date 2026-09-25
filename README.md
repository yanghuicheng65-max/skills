# Skills

我的个人 Agent Skills 仓库，用于集中保存常用技能。我使用 [CC Switch](https://github.com/farion1231/cc-switch) 管理技能在不同 Agent 中的安装与启用。

目前收录 32 个技能，均来自 [Matt Pocock 的 skills 仓库](https://github.com/mattpocock/skills)，来源版本为 [`c55ee46073ed923f86ce59a5eb3b6d895095d1b7`](https://github.com/mattpocock/skills/tree/c55ee46073ed923f86ce59a5eb3b6d895095d1b7)。技能文件及其配套资料按原目录复制，下面的中文简介只用于浏览和挑选。原项目采用 MIT 许可证，许可文本见 [licenses/mattpocock-skills-MIT.txt](licenses/mattpocock-skills-MIT.txt)。

## 目录

```text
skills/
├── README.md
├── licenses/
│   └── mattpocock-skills-MIT.txt
└── skills/
    ├── engineering/     # 工程开发：17 个
    ├── productivity/    # 通用效率：7 个
    └── in-progress/     # 上游仍在开发中的技能：8 个
```

每个技能都有自己的 `SKILL.md`，相关资料与脚本保留在同一个技能目录中。`in-progress` 是上游的目录名称，提醒使用前先查看内容；它们也已收录在本仓库。

## 工程开发

| 技能 | 简介 |
| --- | --- |
| [ask-matt](skills/engineering/ask-matt/SKILL.md) | 根据当前任务，推荐这套技能中合适的工作流程。 |
| [code-review](skills/engineering/code-review/SKILL.md) | 从代码规范和需求符合度两个角度审查改动。 |
| [codebase-design](skills/engineering/codebase-design/SKILL.md) | 设计边界清晰、接口简洁的模块，改进代码组织。 |
| [diagnosing-bugs](skills/engineering/diagnosing-bugs/SKILL.md) | 按复现、定位、验证假设和回归测试的步骤排查故障。 |
| [domain-modeling](skills/engineering/domain-modeling/SKILL.md) | 梳理项目术语、领域模型与架构决策。 |
| [grill-with-docs](skills/engineering/grill-with-docs/SKILL.md) | 深入追问方案，同时整理术语表和决策文档。 |
| [implement](skills/engineering/implement/SKILL.md) | 根据规格或任务实施代码，并结合测试和代码审查。 |
| [improve-codebase-architecture](skills/engineering/improve-codebase-architecture/SKILL.md) | 找出架构改进机会，生成可视化报告并讨论选定方案。 |
| [prototype](skills/engineering/prototype/SKILL.md) | 制作一次性原型，验证设计想法、交互或逻辑。 |
| [research](skills/engineering/research/SKILL.md) | 基于可靠的一手资料调研问题，留下带来源的笔记。 |
| [resolving-merge-conflicts](skills/engineering/resolving-merge-conflicts/SKILL.md) | 根据两侧改动的意图，逐块解决 Git 合并或变基冲突。 |
| [setup-matt-pocock-skills](skills/engineering/setup-matt-pocock-skills/SKILL.md) | 为具体项目配置问题跟踪方式、标签和领域文档布局。 |
| [tdd](skills/engineering/tdd/SKILL.md) | 按测试先行、实现、重构的循环开发功能或修复问题。 |
| [to-spec](skills/engineering/to-spec/SKILL.md) | 将已有讨论整理成规格说明并发布到项目的问题跟踪系统。 |
| [to-tickets](skills/engineering/to-tickets/SKILL.md) | 将方案拆成带依赖关系、可逐步实现的任务。 |
| [triage](skills/engineering/triage/SKILL.md) | 分类并推进 issue 和外部 PR，整理可供 Agent 接手的任务说明。 |
| [wayfinder](skills/engineering/wayfinder/SKILL.md) | 为跨多个会话的大型模糊任务建立决策地图，逐步厘清路径。 |

## 通用效率

| 技能 | 简介 |
| --- | --- |
| [grill-me](skills/productivity/grill-me/SKILL.md) | 通过连续提问，把计划或设计中的关键选择问清楚。 |
| [grilling](skills/productivity/grilling/SKILL.md) | 提供可复用的深度访谈方法，也是多个其他技能的基础。 |
| [handoff](skills/productivity/handoff/SKILL.md) | 将当前对话整理成交接文档，供另一个 Agent 继续工作。 |
| [teach](skills/productivity/teach/SKILL.md) | 在当前工作目录中持续教授一项技能或概念。 |
| [to-questionnaire](skills/productivity/to-questionnaire/SKILL.md) | 把需要他人回答的问题整理成可异步填写的问卷。 |
| [wait-what](skills/productivity/wait-what/SKILL.md) | 当上一条解释没讲清楚时，补足背景并重新说明。 |
| [writing-for-agents](skills/productivity/writing-for-agents/SKILL.md) | 编写供 Agent 使用的技能和项目指令文档。 |

## 开发中

| 技能 | 简介 |
| --- | --- |
| [claude-handoff](skills/in-progress/claude-handoff/SKILL.md) | 将当前对话交给新的后台 Agent 接续执行。 |
| [implement-spec](skills/in-progress/implement-spec/SKILL.md) | 根据已有规格说明实现代码。 |
| [loop-me](skills/in-progress/loop-me/SKILL.md) | 围绕想建立的工作流程，反复追问并澄清需求。 |
| [pr](skills/in-progress/pr/SKILL.md) | 编写 Pull Request 描述。 |
| [retro](skills/in-progress/retro/SKILL.md) | 回顾一次编码会话，总结经验与问题。 |
| [writing-beats](skills/in-progress/writing-beats/SKILL.md) | 将写作素材组织成有顺序的内容段落。 |
| [writing-fragments](skills/in-progress/writing-fragments/SKILL.md) | 从原始素材中提取写作片段，暂不组织结构。 |
| [writing-shape](skills/in-progress/writing-shape/SKILL.md) | 将原始素材逐段塑造成文章。 |

## 使用和维护

- 在 CC Switch 中添加本仓库，然后按需挑选技能。部分技能会调用同仓库中的其他技能，例如 `grill-me` 使用 `grilling`，`implement` 使用 `tdd` 和 `code-review`；选择时一并检查依赖。
- `setup-matt-pocock-skills` 是对**具体项目**执行的一次性配置，不是本仓库的安装步骤。使用依赖问题跟踪系统的工程流程前，先在目标项目中完成配置。
- 新增自己的技能时，放入合适的分类目录，并让目录名与 `SKILL.md` 中的 `name` 一致。每个技能应说明用途、触发条件和必要的环境要求；配套文件放在同一技能目录中。
- 更新上游技能时，核对文件变更，并同步更新本页的简介、数量和来源版本。
