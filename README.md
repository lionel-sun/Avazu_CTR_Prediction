# Avazu CTR Prediction
- [Kaggle Link](https://www.kaggle.com/c/avazu-ctr-prediction)


## 1数据预处理
通过chunksize将文件读入，根据时间筛选选27-30日的数据（从测试集）合并成一个文件然后保存到硬盘。
清理内存，根据导入缩减后的数据集。

将训练集和测试集合并到一起进行特征工程

## 2模型预测
使用lightgbm

结果可以做到很好
