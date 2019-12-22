# lstm-stock-predict
Using LSTM to forecast stock return  
本代码实现的是lstm神经网络对多特征、时间序列数据的预测（比如股票收益率预测、污水处理量预测、负荷预测）。  
我使用的是中国政府从2005-2019年的国债收益率的月度数据（label），以及同时期的其他五个特征(feature)。(guozhai.xlsx)  
在导入数据后，我首先处理原始数据，处理为lstm神经网络的输入的格式。之后，我利用tensorflow和keras搭建lstm神经网络，接着输出训练集测试集误差。  
除了输出测试集上的MSE和RMSE等衡量指标，我们还输出了测试集上的涨跌预测准确率，这一点对于股票价格的预测尤为重要。  
几乎所有的超参数都是可以被直接修改的。  

This code achieve the prediction of multiple features and time series data by LSTM neural network (such as stock yield prediction, sewage treatment capacity prediction, load prediction).  
I use the monthly data of Chinese government bond yields from 2005 to 2019, as well as five other features of the same period.(guozhai.xlsx)  
After importing the data, I first process the original data into the input format of the LSTM neural network. After that, I use tensorflow and keras to build the LSTM neural network, and then output the training set test set error.  
In addition to measuring indicators such as MSE and RMSE on the test set, we also output the forecast accuracy of ups and downs on the test set, which is particularly important for the prediction of stock prices.  
Almost all the super parameters can be modified directly.  
