# MetaInFlow

MetaInFlow 是一个面向企业 AI 落地的 AI Agent / Skill 工程组织。

我们关注的不是“展示一个模型能做什么”，而是把业务场景、知识资产、工作流程和工程工具组织成可配置、可验证、可持续迭代的 AI 系统。

当前公开仓库主要围绕三类能力展开：

- **企业 AI 场景发现**：帮助企业识别、排序和规划 AI 应用场景。
- **Skill / Agent 工程化**：把可复用的判断流程、执行流程和数字分身结构沉淀成 Skill。
- **本地工具与工作台**：提供面向具体工作流的 CLI 和本地自动化工具。

## Public Product Matrix

这里只展示 MetaInFlow 当前公开仓库。私有客户项目、内部交付材料、私有知识库和凭证相关内容不在这里列出。

| 产品 / 模块 | Public repo | 定位 |
| --- | --- | --- |
| ReplicateMe.skill | [MetaInFLow/ReplicateMe.skill](https://github.com/MetaInFLow/ReplicateMe.skill) | 构建 AnthonyHF-style 数字分身 Skill 仓库，组织 identity、PSP/person model、memory、integrations 和安全边界。 |
| Enterprise AI Scenario Map Skill | [MetaInFLow/Enterprise-ai-scenario-map-skill](https://github.com/MetaInFLow/Enterprise-ai-scenario-map-skill) | 面向企业自动生成 AI 应用场景地图报告，支持场景发现、优先级判断和落地路径规划。 |
| MetaInFlow Skills | [MetaInFLow/metainflow-skills](https://github.com/MetaInFLow/metainflow-skills) | MetaInFlow 的 Skill 集合，用于沉淀可复用 AI Agent 工作流。 |
| MetaInFlow Studio CLI | [MetaInFLow/metainflow-studio-cli](https://github.com/MetaInFLow/metainflow-studio-cli) | 面向本地工作流和工具工作台的 CLI 项目。 |

## How We Build

MetaInFlow 的工程原则：

- 先定义真实业务场景，再选择模型、工具和自动化方式。
- 把一次性交付沉淀成可复用 Skill、脚本、模板和验证门禁。
- 对公开材料、私有记忆、客户资料和系统凭证做清晰边界隔离。
- 每个 AI 工作流都应有输入配置、产物定义、完成度检查和安全规则。

## Public Boundary

公开仓库只放可公开的产品、工具和通用方法说明。

不会在公开仓库中提交：

- 客户私有资料、合同、会议原文或内部交付内容。
- 私有 wiki、个人长期记忆正文或未经授权的训练材料。
- API key、token、cookie、refresh token、私钥或其他凭证。

For public collaboration, start from the repositories listed above.
