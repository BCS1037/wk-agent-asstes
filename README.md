# wk-agent-asstes

这里收录我在科研、开发和日常工作中发现的 MCP、Skill 及相关项目。每个项目提供简要介绍和原始仓库链接，方便查阅、学习与交流。

首批从 **CST Studio Suite 自动化仿真** 开始，后续逐步扩展到 HFSS、COMSOL、科研工具和其他 AI 工作流。

## 目录

- [电磁仿真：CST Studio Suite](#电磁仿真cst-studio-suite)
- [收录说明](#收录说明)

## 电磁仿真：CST Studio Suite

| 名称 | 类型 | 简介 | GitHub 仓库 |
| --- | --- | --- | --- |
| **cst-studio-mcp** | MCP | 基于 Python 的 CST MCP Server，提供 180 余种工具，覆盖工程管理、参数化建模、材料与端口设置、求解器控制、S 参数和远场结果读取，以及报告生成；部分操作支持生成离线 VBA。适合构建较完整的 CST 自动化工作流。 | [ismailakdag/cst-studio-mcp](https://github.com/ismailakdag/cst-studio-mcp) |
| **cst-mcp** | MCP | 轻量级 CST MCP Server，通过 Node.js、PowerShell 和 Windows COM 控制 CST，提供 9 个核心工具，可打开和保存工程、执行 VBA 宏、修改参数、重建模型及启动求解器。适合从已有宏脚本开始接入 AI。 | [RFer-Dreaming/cst-mcp](https://github.com/RFer-Dreaming/cst-mcp) |
| **cst-studio-orchestrator-mcp** | MCP | 面向 CST 的综合自动化编排项目，提供 177 个工具。除三维电磁建模、求解和结果提取外，还支持 CST Design Studio 原理图操作，包括 RLC 元件、端口与网络连接，可用于探索场路联合仿真。 | [guardianer9-debug/cst-studio-orchestrator-mcp](https://github.com/guardianer9-debug/cst-studio-orchestrator-mcp) |
| **CST-MCP-Server** | MCP · 开发中 | 面向 AI Agent 的 CST 自动化研究项目，以「建模 → 仿真 → 分析 → 迭代」为目标，规划几何建模、求解器控制、S 参数导出及自动错误诊断等能力。仓库中的主要 MCP 工具仍处于开发路线阶段。 | [DENGFEIYANG/CST-MCP-Server](https://github.com/DENGFEIYANG/CST-MCP-Server) |
| **cst2026-skill-mcp** | Skill + MCP | CST 自动化知识库：提供可安装的 Python 自动化 Skill、配套 MCP、中文领域指南、宏索引、官方文档索引，以及 Codex、Claude 和 Cursor 的配置示例。Skill 用于组织流程与规范，MCP 用于提供参考资料查询及工具接口。 | [jame-ri/cst2026-skill-mcp](https://github.com/jame-ri/cst2026-skill-mcp) |

## 收录说明

- **MCP**：通过标准化工具接口，使 AI Agent 能够调用外部软件或服务。
- **Skill**：将特定任务所需的知识、步骤、规范和脚本组织为可复用的能力包。
- 本仓库用于**收藏与整理**第三方工具，项目功能以各原始仓库文档为准，不代表全部功能均已由我独立实测。
- 使用涉及 CST 的工具前，请检查相应项目的系统、CST 版本、许可证及本地配置要求；运行 AI 生成的脚本时，建议先备份工程并在测试项目中验证。
- 如发现链接失效、介绍有误，或有合适的项目希望推荐，欢迎通过 Issue 或 Pull Request 交流。

---

更多干货，请移步「维客笔记」微信公众号
