# Titanic 生存预测分析 (Kaggle)

这是一个基于 Kaggle 经典入门赛 "Titanic - Machine Learning from Disaster" 的完整数据分析与机器学习流水线项目。

## 📖 项目概述
本项目通过探索性数据分析 (EDA)、数据清洗、特征工程，结合随机森林算法 (Random Forest)，对泰坦尼克号乘客的生存概率进行预测。

## 📊 核心发现
- **性别是生存的最关键因素**：女性生存率高达 74%，男性仅 18%。
- **舱位影响巨大**：头等舱生存率超 63%，三等舱不足 24%。
- **算法准确率**：随机森林模型在测试集上达到了 **82.12%** 的预测准确率。

## 📂 项目结构
- `Titanic_EDA.ipynb`：包含完整的数据探索、可视化、模型训练及评估的 Jupyter Notebook。
- `submission.csv`：AI 生成的预测结果文件。
- `train.csv`：原始训练数据集。

## 🚀 如何运行
```bash
python3 -m venv venv
source venv/bin/activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook