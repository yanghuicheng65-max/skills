# Skills

我的个人 Agent Skills 仓库，用于保存和维护常用的工作流程与方法。仓库中的 skill 采用通用的 [Agent Skills 格式](https://agentskills.io/specification)；我使用 [CC Switch](https://github.com/farion1231/cc-switch) 管理它们在不同 Agent 中的安装和启用。

## 仓库结构

```text
skills/
├── README.md
├── .gitignore
└── skills/
    └── .gitkeep    # 占位文件；目前还没有 skill
```

每个 skill 将独立存放在 `skills/<skill-name>/` 中，并以 `SKILL.md` 作为入口。需要补充材料时，再在该目录下添加 `references/`、`scripts/` 或 `assets/`。仓库目前没有任何 skill。

## 维护约定

- 一个 skill 解决一类明确的任务；按实际用途命名，避免范围过宽。
- 目录名使用小写字母、数字和连字符，并与 `SKILL.md` 中的 `name` 保持一致。
- `SKILL.md` 的 YAML 文件头至少包含 `name` 和 `description`。`description` 应说明 skill 能做什么，以及什么情况下适合使用。
- 尽量使用不依赖特定 Agent 的表述。确实依赖某个工具或环境时，在对应 skill 中写明条件。
- 将详细资料放进该 skill 自己的目录，使用相对路径引用；不要把密钥、令牌或个人敏感数据提交到仓库。

## 新增 skill

在 `skills/` 下创建以 skill 名称命名的目录，编写 `SKILL.md`，按需加入辅助文件。确认文件符合 [Agent Skills 规范](https://agentskills.io/specification)并在目标 Agent 中试用后，再提交到仓库。第一个 skill 加入后，可以删除 `skills/.gitkeep`。
