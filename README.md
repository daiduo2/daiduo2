# 👋 你好，我是 daiduo2

<p align="center">
  <a href="https://aufheben.top"><img src="https://img.shields.io/badge/Personal%20Site-aufheben.top-2E8B57?style=flat-square" alt="个人主页" /></a>
  <a href="https://tashan.ac.cn"><img src="https://img.shields.io/badge/Tashan%20Community-tashan.ac.cn-4ECDC4?style=flat-square" alt="他山科学智能社区" /></a>
</p>

**中国科学院大学 · 他山科学智能社区 · 科研智能体方向**

把科研流程里的判断题交给能验证的系统：论文要能被检索和追溯，模型要能被求解器跑一遍，证明要由 verifier 判定。

## 🧭 在做什么

- **科研 MCP 工具链** —— 把论文检索、事实提取、假设生成封成 MCP 服务，Claude Code 这类客户端可以直接调用
- **Agent 驱动的地震波数值模拟** —— 从已发表的解释图直接提取速度区模型，产出 SPECFEM2D 可用的输入，不用手工描线
- **Verifier-guided 形式化证明** —— 用 Lean 的诊断反馈驱动多轮收敛，对错由 verifier 判定，而不是模型自己说
- **学术知识观测层** —— 用 arXiv / OpenAlex 追踪数学主题的月度热度与演化结构，让结论可以被复查

## 🛠 技术栈

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,go,ts,js,react,docker,bash,git,linux" alt="Tech Stack" />
</p>

## 🌟 精选项目

<!-- AUTO:PROJECTS:BEGIN -->
<!-- 本区块由 GitHub Actions 自动生成，请勿手动编辑 -->

<table width="100%" style="table-layout: fixed;">
<tr>
<td align="center" width="50%" style="padding: 15px; border: 1px solid #30363d; border-radius: 6px; margin: 5px; background-color: #0d1117;"><h3><a href="https://github.com/daiduo2/geoseg" style="color: #58a6ff; text-decoration: none;">geoseg</a></h3><p style="color: #8b949e; font-size: 14px; margin: 10px 0;">从地震解释图自动提取速度区模型，产出 SPECFEM2D 可用的输入</p><div style="margin: 10px 0;"><img src="https://skillicons.dev/icons?i=python" alt="Python" /></div><div style="margin: 10px 0;"><img src="https://img.shields.io/github/stars/daiduo2/geoseg?style=flat-square&logo=github" alt="Stars" /> <img src="https://img.shields.io/github/forks/daiduo2/geoseg?style=flat-square&logo=github" alt="Forks" /></div></td>
<td align="center" width="50%" style="padding: 15px; border: 1px solid #30363d; border-radius: 6px; margin: 5px; background-color: #0d1117;"><h3><a href="https://github.com/daiduo2/solver-adapter" style="color: #58a6ff; text-decoration: none;">solver-adapter</a></h3><p style="color: #8b949e; font-size: 14px; margin: 10px 0;">把 SPECFEM2D 官方算例转成 canonical JSON，并真实驱动求解器跑通</p><div style="margin: 10px 0;"><img src="https://skillicons.dev/icons?i=python" alt="Python" /></div><div style="margin: 10px 0;"><img src="https://img.shields.io/github/stars/daiduo2/solver-adapter?style=flat-square&logo=github" alt="Stars" /> <img src="https://img.shields.io/github/forks/daiduo2/solver-adapter?style=flat-square&logo=github" alt="Forks" /></div></td>
</tr>
<tr>
<td align="center" width="50%" style="padding: 15px; border: 1px solid #30363d; border-radius: 6px; margin: 5px; background-color: #0d1117;"><h3><a href="https://github.com/daiduo2/generate-hypothesis-mcp" style="color: #58a6ff; text-decoration: none;">generate-hypothesis-mcp</a></h3><p style="color: #8b949e; font-size: 14px; margin: 10px 0;">基于 MCP 的论文生成工具：检索 → 事实提取 → 研究假设生成</p><div style="margin: 10px 0;"><img src="https://skillicons.dev/icons?i=python" alt="Python" /></div><div style="margin: 10px 0;"><img src="https://img.shields.io/github/stars/daiduo2/generate-hypothesis-mcp?style=flat-square&logo=github" alt="Stars" /> <img src="https://img.shields.io/github/forks/daiduo2/generate-hypothesis-mcp?style=flat-square&logo=github" alt="Forks" /></div></td>
<td align="center" width="50%" style="padding: 15px; border: 1px solid #30363d; border-radius: 6px; margin: 5px; background-color: #0d1117;"><h3><a href="https://github.com/daiduo2/local-proof-loop" style="color: #58a6ff; text-decoration: none;">local-proof-loop</a></h3><p style="color: #8b949e; font-size: 14px; margin: 10px 0;">verifier-guided 多轮 Lean 证明闭环，由 Lean 判定对错并回传诊断</p><div style="margin: 10px 0;"><img src="https://skillicons.dev/icons?i=python" alt="Python" /></div><div style="margin: 10px 0;"><img src="https://img.shields.io/github/stars/daiduo2/local-proof-loop?style=flat-square&logo=github" alt="Stars" /> <img src="https://img.shields.io/github/forks/daiduo2/local-proof-loop?style=flat-square&logo=github" alt="Forks" /></div></td>
</tr>
<tr>
<td align="center" width="50%" style="padding: 15px; border: 1px solid #30363d; border-radius: 6px; margin: 5px; background-color: #0d1117;"><h3><a href="https://github.com/daiduo2/academic-trend-monitor" style="color: #58a6ff; text-decoration: none;">academic-trend-monitor</a></h3><p style="color: #8b949e; font-size: 14px; margin: 10px 0;">arXiv + OpenAlex 学术趋势仪表盘，追踪主题月度热度与结构</p><div style="margin: 10px 0;"><img src="https://skillicons.dev/icons?i=js" alt="JavaScript" /></div><div style="margin: 10px 0;"><img src="https://img.shields.io/github/stars/daiduo2/academic-trend-monitor?style=flat-square&logo=github" alt="Stars" /> <img src="https://img.shields.io/github/forks/daiduo2/academic-trend-monitor?style=flat-square&logo=github" alt="Forks" /></div><div style="margin-top: 10px;"><a href="https://daiduo2.github.io/academic-trend-monitor/" target="_blank" style="color: #58a6ff;">🔗 在线 Demo</a></div></td>
<td align="center" width="50%" style="padding: 15px; border: 1px solid #30363d; border-radius: 6px; margin: 5px; background-color: #0d1117;"><h3><a href="https://github.com/daiduo2/academic-evolution-graph" style="color: #58a6ff; text-decoration: none;">academic-evolution-graph</a></h3><p style="color: #8b949e; font-size: 14px; margin: 10px 0;">数学研究主题演化知识图谱，关系按 confirmed / bridge / preview 分层</p><div style="margin: 10px 0;"><img src="https://skillicons.dev/icons?i=python" alt="Python" /></div><div style="margin: 10px 0;"><img src="https://img.shields.io/github/stars/daiduo2/academic-evolution-graph?style=flat-square&logo=github" alt="Stars" /> <img src="https://img.shields.io/github/forks/daiduo2/academic-evolution-graph?style=flat-square&logo=github" alt="Forks" /></div></td>
</tr>
</table>

<!-- AUTO:PROJECTS:END -->

## 🖼 效果

**geoseg** —— 左：原始速度模型；中：粗分割；右：horizon 精修后的边界

<p align="center">
  <img src="https://raw.githubusercontent.com/daiduo2/geoseg/main/docs/assets/example1_compare.png" alt="原始速度模型、粗分割与 horizon 精修结果三联对比" width="100%" style="max-width: 900px;" />
</p>

**academic-evolution-graph** —— 节点按子类别着色，边区分已确认 baseline / 待复核 / preview 候选

<p align="center">
  <img src="https://raw.githubusercontent.com/daiduo2/academic-evolution-graph/main/docs/assets/knowledge-graph-demo.png" alt="学术主题演化知识图谱浏览界面" width="100%" style="max-width: 900px;" />
</p>

## 🌐 连接

- 个人主页 —— [aufheben.top](https://aufheben.top)
- 他山科学智能社区 —— [tashan.ac.cn](https://tashan.ac.cn)

---

<p align="center">
  <sub>🌱 让每一步科研操作都留下可复查的痕迹</sub>
</p>
