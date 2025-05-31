  # -predict
  房价预测项目<br>
  项目概述<br>
  本项目旨在通过机器学习算法预测房价。项目使用了多种机器学习模型，包括线性回归、随机森林回归、梯度提升回归、K近邻回归、决策树回归、LightGBM以及卷积神经网络（CNN），并对模型进行了评估和比较。<br>
  
  主要功能
  数据预处理：
  加载数据集
  创建新特征（如房龄、是否翻新、生活密度、地理位置评分）
  处理偏斜特征（对目标变量和部分特征进行对数转换）
  特征选择
  数据集拆分为训练集和测试集
  模型训练与评估：
  使用多种回归模型进行训练
  评估模型性能（RMSE、R²、MAE、MSE）
  超参数调优（使用GridSearchCV）
  可解释性分析：
  使用SHAP值进行模型可解释性分析
  数据可视化：
  绘制特征重要性图
  绘制特征影响分布图
  绘制单样本预测解释图
  绘制相关系数热力图
  绘制价格与邮政编码的散点图
  使用的库
  numpy：用于数值计算
  pandas：用于数据处理和分析
  matplotlib.pyplot：用于数据可视化
  seaborn：用于增强数据可视化效果
  lightgbm：用于训练LightGBM模型
  shap：用于模型可解释性分析
  sklearn：包含多种机器学习算法和工具（如数据预处理、模型训练、评估、超参数调优）
  tensorflow.keras：用于构建和训练卷积神经网络（CNN）模型
  数据集
  数据集名称：kc_house_data.csv
  数据集来源：未明确说明，但通常为公开房价数据集
  数据集内容：包含房屋的各种特征（如卧室数、浴室数、居住面积、房龄等）和对应的房价
  模型
  线性回归 (LinearRegression)
  随机森林回归 (RandomForestRegressor)
  梯度提升回归 (GradientBoostingRegressor)
  K近邻回归 (KNeighborsRegressor)
  决策树回归 (DecisionTreeRegressor)
  LightGBM (lgb.train)
  卷积神经网络（CNN） (Sequential with Conv1D, MaxPooling1D, Dense layers)
  评估指标
  RMSE（均方根误差）：衡量预测值与真实值之间的平均误差
  R²（决定系数）：衡量模型对数据的拟合程度
  MAE（平均绝对误差）：预测值与真实值之间绝对误差的平均值
  MSE（均方误差）：预测值与真实值之间误差的平方的平均值
  项目结构
  数据加载与预处理：
  加载数据集
  创建新特征
  处理偏斜特征
  特征选择
  数据集拆分
  模型训练与评估：
  训练多种回归模型
  评估模型性能
  超参数调优
  可解释性分析：
  使用SHAP值分析模型特征重要性
  绘制特征重要性图和特征影响分布图
  数据可视化：
  绘制相关系数热力图
  绘制价格与邮政编码的散点图
  绘制单样本预测解释图
  使用说明
  环境准备：
  安装所需的Python库（如numpy、pandas、matplotlib、seaborn、lightgbm、shap、sklearn、tensorflow等）
  运行代码：
  加载数据集
  运行数据预处理代码
  运行模型训练与评估代码
  查看模型性能和可解释性分析结果
  结果分析：
  根据评估指标比较不同模型的性能
  根据SHAP值分析特征重要性
  根据可视化结果理解数据特征和模型预测结果
