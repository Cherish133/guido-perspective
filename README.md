# guido-perspective

> 用 Guido van Rossum 的视角，重新思考你的代码。

## 是什么

guido-perspective 是一个基于深度调研的 AI Skill，模仿 Python 之父 Guido van Rossum 的思维框架和表达方式。

不是翻译，不是摘要，是用他的心智模型去分析代码设计、编程语言选择和工程决策。

## 核心心智模型

| 模型 | 一句话 |
|------|--------|
| 可读性是代码的灵魂 | 代码是给人看的，顺便给机器执行 |
| 简洁胜于聪明 | 你用三行 Python 解决的事，用 C 写三百行不算本事 |
| 一种做法，最好只有一种 | 反对 TMTOWTDI，偏好标准化 |
| 实用主义优先于纯粹主义 | 语言是工具，不是宗教 |
| 扁平优于嵌套 | 过深的嵌套是思维混乱的外化 |

## 使用方式

在支持 OpenClaw Skill 的环境里，触发词：

- 「Guido 模式」
- 「Python之父视角」
- 「Guido会怎么看」
- 「用Guido的方式思考」

Skill 会先问确认，然后进入角色。说完「退出」恢复正常对话。

## 免责声明

Guido 的信息截止到 2025 年 10 月（Python 3.14 发布时）。3.14 之后的版本变化，他会诚实承认不确定——不会编造，会让你帮忙确认。

## 快速演示

**问**：「同事写了个很丑的临时方案，但解决了线上问题，你怎么看？」

**Guido**：

> dirty hack 这个事，我说实话。
> 代码丑，我看着也不舒服。但你得承认，线上问题解决了，这才是底线。
> dirty hack 最大的问题不是丑，是它会留下来变成"历史遗留代码"。
> 先用着，但记下来——这是临时的，以后有机会重构干净。

## 版本

当前版本：**v1.0.6**

| 版本 | 变化 |
|------|------|
| v1.0.1 | 初始版本 |
| v1.0.2 | 添加激活确认，修复格式冲突 |
| v1.0.3 | 身份卡更新，GIL描述修正 |
| v1.0.4 | 消除内部矛盾，清理重复工作流 |
| v1.0.5 | 补全 USER.md，description 精简 |
| v1.0.6 | 8个实测用例全部通过，表达DNA补充 |

详细变更记录见 [REMADE.md](REMADE.md)。

## 文件结构

```
guido-perspective/
├── SKILL.md       # 核心：心智模型、回答规则、知识边界
├── SOUL.md        # 灵魂：核心准则、说话禁忌、表达风格
├── IDENTITY.md    # 人物基本资料
├── AGENTS.md      # workspace 配置
├── USER.md        # 用户信息占位
├── _meta.json     # 版本元数据
├── REMADE.md      # 变更历史
└── README.md      # 本文件
```

## 调研来源

- [Python之父Guido van Rossum专题访谈 - CSDN (2009)](https://blog.csdn.net/phphot/article/details/3777882)
- [Guido van Rossum探讨Python:从创世之初到未来 - CSDN (2023)](https://blog.csdn.net/JieLun_C/article/details/133291986)
- [The Zen of Python (PEP 20)](https://peps.python.org/pep-0020/)
- [Python 3.14 官方文档](https://docs.python.org/zh-tw/3.14/whatsnew/3.14.html)
