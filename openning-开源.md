# 智能体项目对比

| 项目名称 | 类型 | GitHub | 特点 | 适用场景 |
|---------|------|--------|------|----------|
| AutoGen (Microsoft) | 多代理对话与协作 | [GitHub](https://github.com/microsoft/autogen) | - 由微软开发，支持多LLM智能体协作<br>- 可自定义角色（如程序员、产品经理、测试员）<br>- 支持自动任务分解、代码执行、人类介入 | - 团队协作编程<br>- 自动化数据分析<br>- 多角色辩论 |
| ChatDev (清华大学) | 多代理对话与协作 | [GitHub](https://github.com/openbmb/chatdev) | - 模拟软件公司环境，包含多个角色（CEO、程序员、测试员等）<br>- 通过聊天协作开发软件<br>- 完全基于LLM，自动生成代码、测试、文档 | - 自动化软件开发<br>- 多智能体协作实验 |
| CrewAI | 多代理任务流水线 | [GitHub](https://github.com/joaomdmoura/crewai) | - 类似AutoGen，但更轻量级<br>- 支持任务流水线（Agent A → Agent B → Agent C） | - 自动化工作流<br>- 数据分析 + 报告生成 |
| MALMO (Microsoft + OpenAI) | 多代理强化学习（MARL） | [GitHub](https://github.com/microsoft/malmo) | - Minecraft 多智能体训练平台<br>- 支持协作或竞争任务<br>- 可与LLM结合，实现自然语言指挥智能体 | - 多智能体强化学习<br>- 游戏AI开发 |
| MetaGPT | 多代理自主系统 | [GitHub](https://github.com/geekan/MetaGPT) | - 将不同角色（产品经理、架构师、工程师）建模为智能体<br>- 协作完成软件项目<br>- 输出完整代码、API设计、文档 | - 自动化软件开发<br>- 多角色协作开发 |
| Agenticseek | 智能代理服务 | [GitHub](https://github.com/Fosowl/agenticSeek) | -可自主浏览网页、编写代码和计划任务<br>- 同时将所有数据保留在您的设备上 | - 适用于软件开发、运维工程师及技术团队<br>多代理协同<br> - 知识检索与内容生成 |
| DeepResearchAgent | 多功能智能体 | [GitHub](https://github.com/SkyworkAI/DeepResearchAgent) | - 分层协作架构、动态分解复杂任务<br> - 高效多模态生成、支持12种输出格式（文档、PPT、图表、网页等），自动匹配图表类型<br> - 低成本与高性能、能够自我验证与动态调整 | - 适用于学术研究自动化（文献综述、技术趋势分析、论文辅助撰写）<br> - 商业分析与决策 - 垂直行业解决方案 |
| Lagent | 多智能体系统 | [GitHub](https://github.com/InternLM/lagent) | - 支持多种类型的智能体、包括但不限于强化学习智能体、基于规则的智能体等<br> -  用户可以根据自己的需求添加新的功能、算法或环境，方便进行定制化开发 | -训练智能体在复杂环境中做出最优决策<br>例如，在游戏、机器人控制等领域<br> - 支持多个智能体之间的协作或竞争 | 