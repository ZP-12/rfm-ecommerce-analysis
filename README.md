# 电商用户行为分析与 RFM 价值分层

## 项目简介
基于英国在线零售数据集（Online Retail II），使用 Python 完成用户价值分析，通过 RFM 模型与 K-means 聚类识别高价值客群，输出可落地的运营策略。

## 技术栈
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- 分析方法：RFM 模型、K-means 聚类、描述性统计

## 核心结论
- 将用户划分为 4 类价值群体（高价值 / 潜力 / 普通 / 流失风险）
- 高价值用户占比约 0.3%，贡献 GMV 达 18.6%
- 提出差异化运营策略建议

## 文件说明
- `analysis.ipynb`：完整分析代码与可视化
- `rfm_analysis.png`：分析结果图表
- 原始数据：UCI Online Retail II（https://archive.ics.uci.edu/dataset/502/online+retail+ii）

## 如何运行
1. 安装依赖：`pip install pandas numpy matplotlib seaborn scikit-learn openpyxl`
2. 下载数据集并放入同级目录
3. 打开 `analysis.ipynb` 依次运行即可
