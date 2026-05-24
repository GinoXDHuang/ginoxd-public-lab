# Ginoxd Public Lab

这里是 Gino 公开沉淀和分享 Agent Skill 的轻量仓库。

当前阶段只放已经可以直接安装使用的内容，不提前创建还没有内容的分类目录。

## 快速开始

当前第一个正式发布条目是 [`product-genesis`](./skills/product-genesis/)：一个用于产品共创的中文 Agent Skill。它会引导 Agent 从专家工作流还原、产品哲学提炼、架构决策，到产出产品共识文档和项目宪法。

使用 [skills](https://www.npmjs.com/package/skills) CLI 全局安装：

```bash
npx skills add GinoXDHuang/ginoxd-public-lab --skill product-genesis -g
```

安装到当前项目：

```bash
npx skills add GinoXDHuang/ginoxd-public-lab --skill product-genesis
```

## 已发布内容

| 类型 | 名称 | 适合场景 |
| --- | --- | --- |
| Skill | [`product-genesis`](./skills/product-genesis/) | 在动手开发前，把模糊产品想法推进到锁定的产品共识、设计原则和项目宪法。 |

## 内容标准

每个正式发布的条目，尽量说明：

- 它解决什么问题
- 什么时候适合使用
- 什么时候不适合使用
- 具体怎么使用
- 必要时给出输入或输出示例
- 如有参考来源，保留署名和来源说明

## 授权

除非另有说明，本仓库中的文字材料采用 Creative Commons Attribution 4.0 International License 授权。

你可以分享、改编和使用这些材料，包括商业用途，但需要保留适当署名。
