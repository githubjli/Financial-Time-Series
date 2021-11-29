# Financial-Time-Series
Financial-Time-Series
```
1 Financial-Prediction-Methods——金融时间序列预测方法
    1.1 Financial-Prediction-CNN（卷积神经网络）
    1.2 Financial-Prediction-LSTM（长短期记忆神经网络）
    1.3 Financial-Prediction-Random-Forest（随机森林）
    1.4 Financial-Prediction-ARMA（自回归滑动平均模型）
2 Financial-Time-Similarity——金融时间序列相似度计算
    2.1 pearson_correlation_coefficient（皮尔逊相关系数）
    2.2 dynamic_time_wrapping（动态时间规整）
    2.3 cosine similarity（余弦相似度）
3 Finance-Time-Others——金融时间序列（其他）
    3.1 calc_variance.py（计算特征方差）
    3.2 confuse_matrix.py（绘制混淆矩阵）
    3.3 corr.py（特征间相关性）
    3.4 result_bar.py（绘制预测模型性能——柱状图）
    3.5 result_plot.py（绘制预测模型性能——折线图）
    3.6 similarity_time_series.py（相似金融时间序列绘制）
    3.7 evaluation.py（计算分类的评价指标）
    3.8 normalization.py（窗口数据归一化）
    3.9 download.py（股票数据下载）
    3.10 roc.py（roc曲线绘制）
    3.11 confusion_matrix.py（混淆矩阵绘制）
    3.12 kalmanfilter.py（卡尔曼滤波）  

```

# mac安装Jupyter
```
1. mac自带python2.7，需要的环境python3 --命令提示有忽略
   # curl https://bootstrap.pypa.io/get-pip.py | python3
2. 先安装pip和ipython --命令提示有忽略
   # sudo easy_install pip
   # sudo pip install ipython
3. ipython-notebook已经整合，python3安装命令
   # pip3 install --user jupyter
4. Jupyter使用
   # python3.7 -m IPython notebook
   或者
   # python3 -m IPython notebook
5. 浏览器中会弹出notebook窗口
   http://localhost:8889/tree
6. Jupyter Notebook 添加目录插件
   # pip3 install jupyter_contrib_nbextensions
   配置
   # jupyter-contrib nbextension install --user --skip-running-check
```

# Mac下Anaconda的安装和使用
```
1. 官网下载安装包
   https://www.anaconda.com/products/individual#macos
2. 命令行安装
   $ bash ~/Downloads/Anaconda3-5.3.1-MacOSX-x86_64.sh
3. 重启终端使新加的环境变量生效
   $ source ~/.bash_profile
4. 常用命令
   查看conda版本
   $ conda --version
   更新conda版本
   $ conda update conda
   查看都安装了那些依赖库
   $ conda list
   创建新的python环境
   $ conda create --name myenv
   并且还可以指定python的版本
   $ conda create -n myenv python=3.7
   $ conda create -n myenv python=3
   创建新环境并指定包含的库
   $ conda create -n myenv scipy
   并且还可以指定库的版本
   $ conda create -n myenv scipy=0.15.0
   复制环境
   $ conda create --name myclone --clone myenv
   查看是不是复制成功了
   $ conda info --envs
   激活、进入某个环境
   $ source activate myenv
   退出环境
   $ source deactivate
   删除环境
   $ conda remove --name myenv --all
   查看当前的环境列表
   $ conda info --envs or $ conda env list
   查看某个环境下安装的库
   $ conda list -n myenv
   查找包
   $ conda search XXX
   安装包
   $ conda install XXX
   更新包
   $ conda update XXX
   删除包
   $ conda remove XXX
   安装到指定环境
   $ conda install -n myenv XXX
5. conda 换源：
    https://mirror.tuna.tsinghua.edu.cn/help/anaconda/
    https://www.jianshu.com/p/042fd657e2d4
    https://www.cnblogs.com/yikemogutou/p/11396045.html
6. conda 环境管理：
    https://www.jianshu.com/p/d2e15200ee9b
7. 安装数据相关包
   $ conda install pandas
   $ conda install keras
   $ conda install scikit-learn
   $ pip3 install tushare
   $ brew install ta-lib
   $ pip3 install Ta-Lib
   $ pip3 install mpl_finance
   $ pip3 install scikit-plot
   $ pip3 install jqdatasdk
   $ pip3 install dtaidistance
   $ pip3 install statsmodels
```   
