# Costa-Rican-Household-Poverty-Level-Prediction
First kaggle competition 
This is my first kaggle competition, like other player in kaggle I chose to start with a playground. In this project I finished totally on my own, 
I learn something really intersting. And this time, I learned about machine learning more systematically.
## [Data cleaning](https://github.com/xinchen201795/Costa-Rican-Household-Poverty-Level-Prediction/blob/master/1%23data_clean.ipynb)
apply lambda to fill the na
## [Feature Engineering](https://github.com/xinchen201795/Costa-Rican-Household-Poverty-Level-Prediction/blob/master/2.features_importance.ipynb)
1. 基于树模型的feature importance计算
2. pca不能使用在这里，pca不能被运用在类别的变量上（pca是非监督性学习）
3. 在有label的情况下，ida优于pca
## [Model Applying](https://github.com/xinchen201795/Costa-Rican-Household-Poverty-Level-Prediction/blob/master/3.answer.ipynb)
1. 交叉验证，即不放回的取出n个样本，尽可能减小样本偏差
2. kfold尝试失败，可能是电脑跑不动【手动捂脸
3， 在比赛中，似乎简单的运用不同的model没有办法很大程度的提升准确率，还需要费功夫在feature engineering上
