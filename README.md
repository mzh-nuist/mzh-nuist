# 茆子豪 · Zihao Mao

**数学背景 · AI 产品 · Agent 评测 · AI 应用开发**

南京信息工程大学数学本科，南京师范大学数学硕士在读，预计 2029 年毕业。

我在做 AI 工具实测、模型评测网站和 Agent 应用项目。喜欢从一个具体问题开始，把需求拆清楚，借助 AI 编程工具做出原型，再检查它能否完成任务、交付的结果能否使用。

目前寻找 **AI 产品、Agent 应用开发、模型评测方向的实习机会**。

[个人主页](https://zhufeng-lab.pages.dev) · [模型评测站](https://modeltest.cc) · [X / 逐风03](https://x.com/03AIer) · [邮件联系](mailto:mzh20031020@outlook.com)

## 正在做的项目

### 逐风 AI 模型评测站

[打开 modeltest.cc](https://modeltest.cc)

从题目设计、模型调用、评分规则到网页展示，主导产品设计，并借助 AI 编程工具推进实现与核验。

- **评测体验：**围绕同题回答、逐项判分和原始证据组织页面。第一期已展示 5 个型号的 8 项任务答卷，并提供匿名作品选择与模型揭晓交互。
- **采集流程：**构建 Python 运行器，适配 OpenAI-compatible 与 Anthropic Messages SSE，支持多轮历史、超时与中断留存、预算预留和脱敏导出；两类协议均有本机模拟验证。
- **产品交付：**使用 JavaScript 前端和 Cloudflare Pages / D1 展示结果、记录访问统计，保留模型回答、评分依据和异常状态。

新一期题面与评分规则已准备，尚待实测。不同版本的题目、答卷与分数分别保留；本站成绩只说明对应任务的表现。

### SafeFlow：银行 Agent 安全执行项目

团队项目，负责项目协调，并推进转账与审计模块的实现和交接。

- 将转账需求拆解为确认、执行、原单查询与异常恢复，整理 PRD、接口约定、业务样例和验收清单。
- 推进 Rust 模拟转账的防重复执行与原号查询，参与 PostgreSQL 审计接收器开发，覆盖事件去重、事务提交后回执及读写权限分离。
- 汇总技术文档、安全自评与演示材料，跟踪模块接入、共同版本与联验缺口。

当前使用模拟账户和资金，真实 LLM、客户权限及共同流程仍有接入与验收工作。[公开项目说明](https://github.com/zw-wz718/safeflow-demo)

### AI 工具实测与产品反馈

[查看实测文章与项目记录](https://zhufeng-lab.pages.dev/research/ai-tool-reviews/)

把 AI 工具放进文件整理、笔记协作、视频转写和 AI 编程等任务，记录完成过程、失败原因和使用条件。

- 已发布 Obsidian、WorkBuddy、ZCode、DeepSeek、Video Script 五篇实测文章。
- 在 [ZCode 实测](https://x.com/03AIer/status/2095111988733211053)中，用第三方模型接入任务检查 Agent 的计划、工具执行与故障恢复，核对 46 次模型请求、52 次工具调用及最终交付状态。
- 结合会话记录、命令输出和成果回读，区分任务理解、配置、工具与账户条件等问题，形成可追溯的测试记录与产品反馈。

## 技术与工作方式

| 方向 | 已有实践 |
| --- | --- |
| 数据与编程 | Python、Pandas、NumPy；数据处理、实验分析与采集脚本 |
| 应用实现 | JavaScript / Node.js、HTTP / SSE、SQL、Cloudflare；用于评测站及相关项目 |
| AI 工作流 | Codex、Claude Code、ZCode；需求澄清、任务拆分、原型实现、测试与结果核验 |
| 产品与协作 | PRD、接口约定、场景测试、评分规则、异常用例与交付文档 |
| 数学基础 | 数学本科与硕士训练，统计分析、实验设计和结果解释 |

我主导需求、方案选择和验收，代码实现中使用 AI 编程工具。项目里会保留已完成、待验证与尚未接入的边界，也记录失败和修正。

## 想参与什么

希望参与能接触真实需求、推进原型上线并持续迭代的团队，重点关注：

- **AI 产品：**任务流程、需求拆解、工具体验、用户反馈与效果评估。
- **Agent 应用开发：**工作流原型、模型与工具接入、异常恢复、功能实现与交付。
- **模型与 Agent 评测：**场景设计、参考答案、评分标准、问题归因和回归验证。

欢迎带着具体任务、产品问题或实习机会来交流。除项目之外，我也在 X 记录数学学习、美股、Web3 和日常。

## 联系我

- 邮箱：[mzh20031020@outlook.com](mailto:mzh20031020@outlook.com)
- 个人主页：[逐风 Lab](https://zhufeng-lab.pages.dev)
- X：[@03AIer](https://x.com/03AIer)
- 在线作品：[modeltest.cc](https://modeltest.cc)

---

Mathematics at NUIST → Master's student at NJNU, expected graduation in 2029.

Building AI evaluation tools and Agent application prototypes with AI-assisted development. Open to internships in AI product, Agent applications, and evaluation.
