# Loan Default Prediction - Logic Classification

逻辑分类项目，基于机器学习方法预测贷款违约风险。

## 环境配置

### 依赖

- Python 3.8+
- Jupyter Notebook / JupyterLab

### 安装

```bash
pip install -r requirements.txt
```

## 使用方式

```bash
jupyter notebook Logic.ipynb
```

或使用 VS Code 直接打开 `Logic.ipynb` 运行。

## 项目结构

```
logic/
├── Logic.ipynb      # 主 Notebook：数据处理、模型训练与评估
├── utils.py         # 工具函数
├── data/            # CSV 数据集
│   ├── train_sub.csv
│   ├── val_sub.csv
│   └── test_sub.csv
└── figures/         # 训练过程可视化图表
```

## 数据

- `train_sub.csv` — 训练集
- `val_sub.csv` — 验证集
- `test_sub.csv` — 测试集
