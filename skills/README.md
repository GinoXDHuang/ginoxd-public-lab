# Skills

这里收录可直接安装使用的 Agent Skills。

## 已发布

| Skill | 用途 | 安装 |
| --- | --- | --- |
| [`product-genesis`](./product-genesis/) | 通过结构化共创对话，把模糊产品想法推进到锁定的产品共识和项目宪法。 | `npx skills add GinoXDHuang/ginoxd-public-lab --skill product-genesis -g` |

## 安装说明

推荐使用 [skills](https://www.npmjs.com/package/skills) CLI：

```bash
npx skills add GinoXDHuang/ginoxd-public-lab --skill product-genesis -g
```

如需安装到当前项目，去掉 `-g`。

如果你的 Agent 暂不支持 `skills` CLI，可以手动复制对应目录到 Agent 的 skills 目录，例如：

```bash
mkdir -p ~/.codex/skills
cp -R skills/product-genesis ~/.codex/skills/
```
