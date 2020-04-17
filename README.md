# CNN_GRU-Regression
This project use CNN+GRU in tensorflow1.x/python to implement regression about time_series.The main content is to predict the wind power at the current time based on the wind speed and wind power data at the historical time。if you want this code for academic, please contact me qq 2919218574
此代码是用来做风功率时间序列预测的，利用过去时刻的风速与风功率数据为输入来预测当前时刻的风功率，文件采用tensorflow1.x编写，如果你需要的话，可以联系我qq2919218574，有偿，想白嫖的不要来了哈
1，mlp结果

![image](https://github.com/fish-kong/CNN_GRU-Regression/blob/master/功率预测/mlp_train.png)
![image](https://github.com/fish-kong/CNN_GRU-Regression/blob/master/功率预测/mlp_test.png)

2，gru结果

![image](https://github.com/fish-kong/CNN_GRU-Regression/blob/master/功率预测/gru_train.png)
![image](https://github.com/fish-kong/CNN_GRU-Regression/blob/master/功率预测/gru_test.png)

3，cnn_gru结果
![image](https://github.com/fish-kong/CNN_GRU-Regression/blob/master/功率预测/cnngru_loss.png)
![image](https://github.com/fish-kong/CNN_GRU-Regression/blob/master/功率预测/cnngru_train.png)
![image](https://github.com/fish-kong/CNN_GRU-Regression/blob/master/功率预测/cnngru_test.png)

4,对比
![image](https://github.com/fish-kong/CNN_GRU-Regression/blob/master/功率预测/compare.png)
