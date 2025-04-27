# Project of Machine Leaning

1. 数据来源

   [Kaggle-Company Bankruptcy Prediction](https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction/data)

2. 参考文献

​	[Financial ratios and corporate governance indicators in bankruptcy prediction: A comprehensive study](https://www.sciencedirect.com/science/article/pii/S0377221716000412)

1. 已完成工作：
   1. 使用随机森林分类器计算特征重要性，用特征重要性作为筛选特征的指标
   2. 使用各特征和目标变量之间的互信息作为筛选特征的指标
   3. 利用特征之间的相关性进行进一步筛选
   4. 用筛选完的特征(这里选择了互信息和相关性作为指标)进行分类训练，方法有随机森林分类和逻辑斯蒂回归，预测准确度较高。
2. 未来工作的想法：
   1. 原始数据方面：数据存在类别不平衡问题，可探究采样方法对准确性的影响；
   2. 特征选择方面：使用更多特征选择的方法(类似向前选择 、向后选择等等)，对比特征选择前后的模型表现；
   3. 模型方面：可以比较几种模型的表现结果。或者使用神经网络看看神经网络的层数、映射维度对模型表现的影响；
   4. 评估指标方面：可以考虑ROC曲线，感觉更直观全面一些 
   5. 可视化方面：对于结果的可视化呈现，还没啥想法，感觉SVM可以尝试二维呈现，其他需要根据每个人的内容挑自己认为合适的 
   6. 解释性方面：可以参考相关文献，对一些特征重要性的原因进行解释（感觉写不了啥 ，不是重点）。
   7. 应用性探究：尝试找现有可行数据（会很麻烦）看看模型的适用性怎么样。
3. 注意：
   1. 数据标签名前面基本都有一个空格，要小心。