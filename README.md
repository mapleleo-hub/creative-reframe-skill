# creative-reframe

判断方向、评估方案、重述问题用的 Agent Skill。

创意产出的多数失败不在执行，在判断：方向选错、方案被否之后改了题、问题越做越复杂、评审嫌太素就去加东西。这个技能只管这些判断点，不管怎么写、怎么排版、怎么交付。

## 它管什么

| 阶段 | 用不用 |
|---|---|
| 定方向、评估方案、被否之后 | 用 |
| 补课（查领域的硬要求） | 不用 |
| 交付（按清单逐项完成） | 不用 |

主文件 `SKILL.md` 按决策点组织，命中信号就查表，不从头读到尾。

## 四份参考

| 文件 | 内容 |
|---|---|
| `references/method-index.md` | 形态分析法、TRIZ、公理化设计等，按需查 |
| `references/design-science-map.md` | 设计研究六条主线，信号表都不匹配时读 |
| `references/topic-selection.md` | 选题：题内矛盾、稀缺性、物象转译、双锁匹配 |
| `references/cases.md` | 对照实验案例与版本对比数据 |

## 安装

```bash
npx skills add mapleleo-hub/creative-reframe-skill --all
```

手动安装：把 `skills/creative-reframe` 整个目录放进你的 agent 技能目录。

## 用法

不需要显式调用。描述里列的触发场景命中时会自动读取，也可以直接说「用 creative-reframe 看这个方案」。

## 版本

当前公开版对应开发版的 v6（261 行）。本地开发版另有 v7，删掉了四块收束并允许推荐改约束，尚未回测充分，暂不公开。

## 来源

自研，方法索引部分引用 Zwicky 1967、Altshuller、Suh 2001、Schön 1983、Simon 1969、Rittel 等公开文献，案例数据来自本机四轮对话对照实验。

## 许可

MIT，见 `LICENSE`。
