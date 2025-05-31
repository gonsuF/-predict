  # -predict
  房价预测项目<br>
  项目概述<br>
  本项目旨在通过机器学习算法预测房价。项目使用了多种机器学习模型，包括线性回归、随机森林回归、梯度提升回归、K近邻回归、决策树回归、LightGBM以及卷积神经网络（CNN），并对模型进行了评估和比较。<br>
  
  主要功能<br>
  数据预处理：<br>
  加载数据集<br>
  创建新特征（如房龄、是否翻新、生活密度、地理位置评分）<br>
  处理偏斜特征（对目标变量和部分特征进行对数转换）<br>
  特征选择<br>
  数据集拆分为训练集和测试集<br>
  模型训练与评估：<br>
  使用多种回归模型进行训练<br>
  评估模型性能（RMSE、R²、MAE、MSE）<br>
  超参数调优（使用GridSearchCV）<br>
  可解释性分析：<br>
  使用SHAP值进行模型可解释性分析<br>
  数据可视化：<br>
  绘制特征重要性图<br>
  绘制特征影响分布图<br>
  绘制单样本预测解释图<br>
  绘制相关系数热力图<br>
  绘制价格与邮政编码的散点图<br>
  使用的库<br>
  numpy：用于数值计算<br>
  pandas：用于数据处理和分析<br>
  matplotlib.pyplot：用于数据可视化<br>
  seaborn：用于增强数据可视化效果<br>
  lightgbm：用于训练LightGBM模型<br>
  shap：用于模型可解释性分析<br>
  sklearn：包含多种机器学习算法和工具（如数据预处理、模型训练、评估、超参数调优）<br>
  tensorflow.keras：用于构建和训练卷积神经网络（CNN）模型<br>
  数据集<br>
  数据集名称：kc_house_data.csv<br>
  数据集来源：未明确说明，但通常为公开房价数据集<br>
  数据集内容：包含房屋的各种特征（如卧室数、浴室数、居住面积、房龄等）和对应的房价<br>
  模型<br>
  线性回归 (LinearRegression)<br>
  随机森林回归 (RandomForestRegressor)<br>
  梯度提升回归 (GradientBoostingRegressor)<br>
  K近邻回归 (KNeighborsRegressor)<br>
  决策树回归 (DecisionTreeRegressor)<br>
  LightGBM (lgb.train)<br>
  卷积神经网络（CNN） (Sequential with Conv1D, MaxPooling1D, Dense layers)<br>
  评估指标<br>
  RMSE（均方根误差）：衡量预测值与真实值之间的平均误差<br>
  R²（决定系数）：衡量模型对数据的拟合程度<br>
  MAE（平均绝对误差）：预测值与真实值之间绝对误差的平均值<br>
  MSE（均方误差）：预测值与真实值之间误差的平方的平均值<br>
  项目结构<br>
  数据加载与预处理：<br>
  加载数据集<br>
  创建新特征<br>
  处理偏斜特征<br>
  特征选择<br>
  数据集拆分<br>
  模型训练与评估：<br>
  训练多种回归模型<br>
  评估模型性能<br>
  超参数调优<br>
  可解释性分析：<br>
  使用SHAP值分析模型特征重要性<br>
  绘制特征重要性图和特征影响分布图<br>
  数据可视化：<br>
  绘制相关系数热力图<br>
  绘制价格与邮政编码的散点图<br>
  绘制单样本预测解释图<br>
  使用说明<br>
  环境准备：<br>
  安装所需的Python库（如numpy、pandas、matplotlib、seaborn、lightgbm、shap、sklearn、tensorflow等）<br>
  运行代码：<br>
  加载数据集<br>
  运行数据预处理代码<br>
  运行模型训练与评估代码<br>
  查看模型性能和可解释性分析结果<br>
  结果分析：<br>
  根据评估指标比较不同模型的性能<br>
  根据SHAP值分析特征重要性<br>
  根据可视化结果理解数据特征和模型预测结果<br>
