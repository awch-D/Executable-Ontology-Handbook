# Executable Ontology Handbook · 可执行本体工程手册

> A practical Chinese handbook on executable enterprise Ontology — from semantic objects to governed actions, writeback, decision lineage, and AI agents.

> [!IMPORTANT]
> 本项目是独立社区教学项目，与 Palantir Technologies 无隶属、合作或官方授权关系。Palantir、Foundry、AIP 等名称及商标归其权利人所有。

## 简介

企业真正需要的不只是“让 AI 看懂数据”，而是让人和 AI 在同一套业务语义、逻辑、权限与行动模型上安全协作。

本仓库是一份零依赖、单文件 HTML 中文教学手册，围绕 Palantir 所代表的企业级可执行 Ontology 工程范式，系统解释如何把分散的数据、规则、模型、业务操作与安全治理统一为可查询、可计算、可执行、可审计的运营系统。

## 核心定义

```text
可执行本体 = 业务对象与关系 + 计算与规则 + 受控行动 + 动态安全与审计
```

它不仅回答“世界里有什么”，还回答：

- 对象之间如何关联
- 哪些逻辑可以计算或推演
- 谁可以执行哪些动作
- 动作如何安全写回业务系统
- 每次决策如何留下完整血缘

## 特性

- 12 章完整中文教学体系
- Data、Logic、Action、Security 四位一体模型
- Object、Property、Link、Interface、Function、Action 等核心术语
- Language、Engine、Toolchain 三层系统架构
- 数据库、知识图谱、语义层、数字孪生与 BPM 横向对比
- 关键物料断供的端到端供应链案例
- AI Agent 授权阶梯与安全接入方法
- 最小闭环落地路线、成熟度模型和上线检查清单
- 目录搜索、滚动高亮、交互式标签、自测题和打印 PDF
- 单文件、零构建、完全响应式、无远程 UI 依赖

## 章节目录

| # | 章节 | 核心内容 |
|---|---|---|
| 01 | Ontology 到底是什么 | 经典定义与企业级工程定义 |
| 02 | 为什么企业需要它 | 从数据孤岛到运营决策闭环 |
| 03 | 四位一体决策模型 | Data / Logic / Action / Security |
| 04 | 语义元素与动力元素 | 对象、关系、接口、函数与行动 |
| 05 | Ontology System 架构 | Language / Engine / Toolchain |
| 06 | 与相似概念的区别 | Schema、知识图谱、语义层、数字孪生、BPM |
| 07 | 完整供应链案例 | 缺料事件、推演、审批、写回与学习 |
| 08 | AI Agent 接入 | 工具、权限、审计与人机协同 |
| 09 | 如何落地建设 | 从高价值决策反推最小闭环 |
| 10 | 常见误区 | 七类典型反模式 |
| 11 | 成熟度与验收 | L0—L5 教学模型与证据标准 |
| 12 | 术语、自测与资料 | 术语表、自测题和一手来源 |

## 本地查看

无需安装依赖，直接打开：

```bash
open index.html        # macOS
# xdg-open index.html  # Linux
# start index.html     # Windows
```

也可以使用任意静态文件服务器预览。

## GitHub Pages

仓库已包含 `.github/workflows/pages.yml`。推送到 `main` 后，在 GitHub 仓库设置中将 Pages 的 Source 设为 **GitHub Actions**，后续推送会自动部署。

## 技术实现

- HTML5
- 原生 CSS：变量、Grid、Flexbox、响应式与打印样式
- 原生 JavaScript：目录搜索、滚动联动、标签切换与自测评分
- 内嵌 SVG favicon
- 无 Node.js、包管理器或构建步骤

## 项目结构

```text
Executable-Ontology-Handbook/
├── .github/workflows/pages.yml
├── .gitignore
├── index.html
├── LICENSE
└── README.md
```

## 贡献

欢迎提交 Issue 或 Pull Request：修正概念解释时请附一手来源；新增章节前先讨论信息结构；保持单文件与零依赖原则，不引入远程 UI 资源。

## 核心参考

- [Palantir · The Ontology system](https://www.palantir.com/docs/foundry/architecture-center/ontology-system/)
- [Palantir · Ontology overview](https://www.palantir.com/docs/foundry/ontology/overview/)
- [Palantir · Why create an Ontology?](https://www.palantir.com/docs/foundry/ontology/why-ontology/)
- [Palantir · Action types](https://www.palantir.com/docs/foundry/action-types/overview/)
- [Thomas R. Gruber · A Translation Approach to Portable Ontology Specifications](https://tomgruber.org/writing/ontolingua-kaj-1993/)

## 协议

本项目以 [MIT License](LICENSE) 开源。引用的第三方文档、商标与产品名称版权归各自权利人所有。
