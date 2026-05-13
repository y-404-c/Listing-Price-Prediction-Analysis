# Listing-Price-Prediction-Analysis
共享经济房源价格预测与影响因素分析

## 📌 项目简介
基于西雅图 **3,800+** 条真实房源数据，构建 **XGBoost 回归模型** 进行房价预测，并通过特征重要性分析识别定价核心驱动因子，为房东和平台提供数据驱动的定价策略建议。

## ✨ 核心亮点
- 🤖 **多模型对比**：对比线性回归、随机森林、XGBoost 三种算法
- 📈 **高精度预测**：XGBoost 模型 R² 达 **0.61**，MAE 仅 **$34.55**
- 🔍 **特征重要性**：精准识别卧室数量、房型、地段为定价三大核心因子
- 🖼️ **四合一可视化**：价格分布、相关性热力图、容纳人数趋势、模型对比

## 🛠️ 技术栈
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Scikit-learn` `XGBoost`

## 📂 项目结构
```

├── Airbnb_Price_Analysis.ipynb   # 完整分析代码
├── airbnb_analysis.png           # 四合一分析图表
├── feature_importance.png        # 特征重要性排名图
├── model_results.csv             # 模型评估结果
└── README.md

```

## 📈 核心成果
| 分析模块 | 关键发现 |
|---------|---------|
| **模型预测** | XGBoost R² = **0.614**，MAE = **$34.55**，RMSE = **$55.98** |
| **特征重要性 TOP 3** | `bedrooms`(21.2%)、`room_type`(15.3%)、`Downtown`(5.7%) |
| **定价建议** | 卧室数量是定价头号驱动因子，市中心地段溢价明显 |

## 🚀 如何使用
1. 下载数据集：`https://www.kaggle.com/datasets/airbnb/seattle/data`
2. 将 `listings.csv` 文件路径替换为本地路径
3. 运行 `Airbnb_Price_Analysis.ipynb`

## 📬 联系方式
如有疑问或建议，欢迎联系。
