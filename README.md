# daiduo2

科研智能体方向。中国科学院大学 · 他山科学智能社区。

做的东西大多围绕一件事：把判断交给能验证的系统。论文要能被检索和追溯，数值模型要能被求解器跑一遍，证明要由 verifier 判定。

## 在做什么

**科研 MCP 工具链。** 论文检索、事实提取、假设生成三步做成 MCP 服务，Claude Code 这类客户端装上就能调。

**Agent 驱动的地震波数值模拟。** 从已发表的解释图里直接提取速度区模型，输出 SPECFEM2D 能吃的输入，省掉手工描线那一步。

**Verifier-guided 形式化证明。** 对错交给 Lean 判定，诊断信息回传给 solver，多轮迭代到收敛；模型不参与自我评分。

**学术知识观测层。** arXiv 与 OpenAlex 的数据进来，跟踪数学主题的月度热度和演化结构，每次结论都留着可复查的中间产物。

## 技术

Python 为主，Go 和 TypeScript 写工具层。MCP / FastMCP、Claude Agent SDK、SPECFEM2D、Lean 4、PyTorch、BERTopic、React、Vite、D3、GitHub Actions。

## 精选项目

<!-- AUTO:PROJECTS:BEGIN -->
<!-- 本区块由 GitHub Actions 自动生成，请勿手动编辑 -->

### [geoseg](https://github.com/daiduo2/geoseg)

从地震解释图提取速度区模型，输出 SPECFEM2D 可用的输入

`Python` · `specfem2d` · `geophysics` · `seismic`

### [solver-adapter](https://github.com/daiduo2/solver-adapter)

把官方算例转成 canonical JSON，并真实驱动 SPECFEM2D 求解器跑通

`Python` · `specfem2d` · `geophysics` · `solver`

### [generate-hypothesis-mcp](https://github.com/daiduo2/generate-hypothesis-mcp)

检索 → 事实提取 → 假设生成，整条流程封成 MCP 服务

`Python` · `mcp` · `research` · `llm`

### [local-proof-loop](https://github.com/daiduo2/local-proof-loop)

Lean verifier 判定对错、回传诊断，多轮迭代收敛的证明闭环

`Python` · `lean` · `ai4math` · `formal-verification`

### [academic-trend-monitor](https://github.com/daiduo2/academic-trend-monitor)

arXiv + OpenAlex 数据驱动的学术主题趋势仪表盘

`JavaScript` · `arxiv` · `openalex` · `bertopic`

[在线演示](https://daiduo2.github.io/academic-trend-monitor/)

### [academic-evolution-graph](https://github.com/daiduo2/academic-evolution-graph)

数学研究主题演化知识图谱，关系按证据强度分层

`Python` · `knowledge-graph` · `arxiv` · `bertopic`

<!-- AUTO:PROJECTS:END -->

## 效果

**geoseg** 的分割流程，左为原始速度模型，中为粗分割，右为 horizon 精修后的边界。

![原始速度模型、粗分割与 horizon 精修结果三联对比](https://raw.githubusercontent.com/daiduo2/geoseg/main/docs/assets/example1_compare.png)

**academic-evolution-graph** 的图谱浏览界面。节点按子类别着色，边区分已确认 baseline、待复核与 preview 候选。

![学术主题演化知识图谱浏览界面](https://raw.githubusercontent.com/daiduo2/academic-evolution-graph/main/docs/assets/knowledge-graph-demo.png)

## 联系

- 个人主页 —— [aufheben.top](https://aufheben.top)
- 他山科学智能社区 —— [tashan.ac.cn](https://tashan.ac.cn)
