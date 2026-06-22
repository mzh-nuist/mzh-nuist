# 茆子豪 · Zihao Mao

```
数学背景 · 量化研究 · 因子模型 · AI 工作流
```

> *因子方向比显著性更重要。Alpha 不是预测的奖励——是市场约束留下的租金。*

---

### 研究

**A 股多市值层因子研究** — 微盘（13 亿）→ 超大市值（2.7 万亿），跨 6 个市值层系统性检验因子有效性。核心发现：**因子方向随市值系统性翻转**——低 PB、高 ROE 这些教科书逻辑在微盘池中全部反向。沉淀了七层交叉验证方法论，从 t 检验到跨年稳定性，一个因子必须过七关才接受。最终策略落地聚宽：9 因子等权 + 择时，年化 17.25%，Sharpe 0.90，最大回撤 9.4%。全程有项目复盘，失败和修正都记录在案。

🔗 [quant-intern](https://github.com/mzh-nuist/quant-intern) — 9 个研究模块、聚宽实盘代码、方法论反思

**三条路线，同一个结论。** Q7 用 XGBoost + SHAP + Autoencoder 三条路线并行找小微盘盈利股特征，结果发现三条路线 Spearman 平均仅 0.21——互相矛盾。修正过拟合后保留了最重要的干净信号：不看财报，仅凭价格特征就能把 A/D 两类股票分开（AUC 0.886）。

**Alpha 的本质** — [不是预测，是市场约束留下的租金](https://github.com/mzh-nuist/quant-intern/blob/main/alpha_meaning.md)。市场不会因为你聪明就奖励你。市场只会在别人被约束的时候，给你一个收费的机会。错误会被修正，约束会反复出现。

---

### 教训

做这个项目最深的三个体会：

1. **因子方向 > 统计显著性。** 动量因子平均 |t|=3.06，看似漂亮，但 6 年中 3 正 3 负——方向随机。低波动率 |t|=3.28，6 年全部方向一致。只看 p 值的代价是被过拟合的显著性误导。

2. **分类力 ≠ 收益预测力。** XGBoost 区分好公司和烂公司 AUC 0.91，基于分类结果建的四个策略全部亏损。debt_ratio 区分能力最强（d=−0.92），收益预测能力最弱（t=0.16）。"什么是好公司"和"买了能不能赚钱"是两个问题。

3. **AI 是显微镜，不是炼金术。** AI 输出的每一句话必须回查原始数据——多次出现结论方向或数字与实际输出不一致。标题不能由 AI 按"理想结构"预填，必须有实际运行结果支撑。

📋 [完整项目复盘](https://github.com/mzh-nuist/quant-intern/blob/main/%E9%A1%B9%E7%9B%AE%E5%A4%8D%E7%9B%98_%E9%94%99%E8%AF%AF%E4%B8%8E%E6%88%90%E9%95%BF.md)

---

### 项目

| 仓库 | 内容 | 亮点 |
|------|------|------|
| [quant-intern](https://github.com/mzh-nuist/quant-intern) | 微盘因子研究 Q1–Q9、聚宽策略、ETF 轮动对比实验 | 七层交叉验证、方法论复盘 |
| [quant](https://github.com/mzh-nuist/quant) | 双均线 × 多因子选股 × ETF 动量轮动 | CLI + GUI、双数据源 |
| [etf-strategy](https://github.com/mzh-nuist/etf-strategy) | ETF 动量轮动 + PB 估值约束叠加 | 6 步逻辑、估值 overlay 降回撤 |

---

### 技术栈

`Python` `NumPy/Pandas/SciPy` `Statsmodels` `scikit-learn` `XGBoost` `SHAP` `PyTorch` `backtrader` `Matplotlib` `Jupyter` `akshare` `baostock`

---

### 找什么

2029 年毕业，数学本科 + 硕士。在找量化研究 / 交易方向的实习或全职机会。对中型私募、券商金工、期货量化都开放。如果我的研究方向跟你们团队有交集，欢迎联系。

📧 mzh20031020@outlook.com

---

*Mathematics (NUIST) → Graduate (NJNU). Building quant research infrastructure, factor models, and AI workflows. Open to quant research / trading roles — internship or full-time, 2029 grad.*
