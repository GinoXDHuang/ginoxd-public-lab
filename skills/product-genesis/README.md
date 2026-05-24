# Product Genesis Skill

`product-genesis` 是一个中文 Agent Skill，用来把早期产品想法从"模糊灵感"推进到"可以交给工程阶段执行的锁定共识"。

它不是普通头脑风暴模板。它要求 Agent 扮演会挑战、会追问、会指出盲区的产品共创者，并在讨论过程中维护两类产物：

- **产品共识文档**：记录定位、边界、原则、架构决策、开放问题和版本历史。
- **项目宪法**：把产品共识转成开发阶段可执行的协作规则、进度坐标系和权威文档锚点。

## 适合什么时候用

- 你有一个新产品、Agent、工具或工作流想法，但还没想清楚定位。
- 你想在开发前先锁定产品原则、边界和架构决策。
- 你希望 Agent 不只是整理你的话，而是主动压力测试、补盲区、提出反面意见。
- 你需要把多轮讨论沉淀成一份后续工程团队可以接手的文档。

## 不适合什么时候用

- 需求已经明确，只需要写代码、改页面或修 bug。
- 只需要普通 PRD、会议纪要、摘要或营销文案。
- 只是想快速列功能清单，不准备做产品定位和原则讨论。

## 一键安装

使用 [skills](https://www.npmjs.com/package/skills) CLI：

```bash
npx skills add GinoXDHuang/ginoxd-public-lab --skill product-genesis -g
```

如果你想安装到当前项目而不是全局环境，去掉 `-g`：

```bash
npx skills add GinoXDHuang/ginoxd-public-lab --skill product-genesis
```

安装时 CLI 会询问要同步到哪些 Agent。如果你希望跳过交互并安装到所有支持的 Agent，可以使用：

```bash
npx skills add GinoXDHuang/ginoxd-public-lab --skill product-genesis -g --agent '*' -y
```

## 手动安装

也可以直接复制 skill 目录：

```bash
git clone https://github.com/GinoXDHuang/ginoxd-public-lab.git
mkdir -p ~/.codex/skills
cp -R ginoxd-public-lab/skills/product-genesis ~/.codex/skills/
```

Claude Code 用户可以复制到：

```bash
mkdir -p ~/.claude/skills
cp -R ginoxd-public-lab/skills/product-genesis ~/.claude/skills/
```

## 触发方式

安装后，直接用自然语言发起即可，例如：

```text
我想做一个给独立开发者用的需求澄清 Agent，我们先做产品共创。
```

```text
我有个工具想法还很模糊，先别写代码，帮我把产品哲学、边界和项目宪法锁下来。
```

```text
我们来头脑风暴一个 Agent 产品，但你不要只总结，要主动挑战我的假设。
```

## 文件结构

```text
product-genesis/
├── README.md
└── SKILL.md
```

`SKILL.md` 是 Agent 实际加载的 skill 文件；`README.md` 是给人看的安装和使用说明。

## 授权

本 skill 跟随仓库主授权：Creative Commons Attribution 4.0 International License。
