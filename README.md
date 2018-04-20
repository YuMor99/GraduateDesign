# GraduateDesign

1. Simple EDA.ipynb - 数据探索与可视化
2. naive-XGB.ipynb - 提取基础特征 + 基础模型训练
- Public LB: 0.31619
- Private LB: 0.32125
3. mixed-XGB.ipynb - 集成三个模型：
- 1st model - 处理错误数据 + 提取时间特征 + 俄罗斯房价随季度的变动
- 2nd model - 处理类别特征
- 3rd model - naive-XGB
- Public LB：0.31050
- Private LB：0.31660
4. master-XGB.ipynb - 集成三个模型：
- 1st model - 预测每平方米的价格 + 针对“个人资产”和“投资财产”分别训练模型
- 2st model - 预测总价格
- 3rd model - mixed-XGB
- Public LB：0.31026
- Private LB：0.31431
