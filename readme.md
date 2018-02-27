放在前面，更新说明：
(TODO) ipynb脚本需要添加必要的解释和说明，最好能够完成笔记和代码相结合。
> 更新代码，能在python2 和python3 运行  
> 章节更改为ipynb，用来更好显示运行结果，方便查看。并在后期用来更好转换为pdf、html等格式，同时也添加更为详细的解释
> 原所有py文件修改，完善放置[code](code)文件夹下面，数据单独放在[data](data)文件夹下  
> readme.md 分章节下面，笔记增添 [LSJU机器学习笔记](https://github.com/zlotus/notes-LSJU-machine-learning)  
> （TODO） 增添吴恩达机器学习课程python代码  

`Github` 加载 `.ipynb` 的速度较慢，建议在[这里](http://nbviewer.jupyter.org/github/Peterchenyijie/MachineLearningZeroToALL/blob/master/readme.ipynb)中查看该项目。

requirement：
* scikit-learn >=0.19  
 
[![MIT license](https://img.shields.io/dub/l/vibe-d.svg)](https://github.com/PeterChenYijie/MachineLearningZeroToALL/blob/master/LICENSE)

机器学习算法Python实现
=========


## ipynb 学习目录
* [0 Basic Concept|基础概念](0-BasicConcept)
    * [概率论](0-BasicConcept/note/probability_theory.ipynb)
* [1 Linear Regression|线性回归](1-LinearRegression)
    * 1.1 [线性回归笔记](1-LinearRegression/note)
        * 1.1.1 [LSJU笔记-监督学习应用](1-LinearRegression/note/LSJU_chapter02.ipynb)
        * 1.1.2 [LSJU笔记-线性模型概率解释、局部加权回归](1-LinearRegression/note/LSJU-chapter03_01.ipynb)
        * 1.1.3 [LSJU笔记-一般线性模型](1-LinearRegression/note/LSJU_chapter04.ipynb)
        * 1.1.3 [笔记](1-LinearRegression/note/NOTE-linear_regression.ipynb)
    * 1.2 [线性回归的实现](1-LinearRegression/LinearRegression.ipynb)
    * 1.3 [使用sklearn 线性回归](1-LinearRegression/LinearRegression_sklearn.ipynb)
    * 1.4 [Mxnet 实现线性回归](1-LinearRegression/linear_regression_mxnet.ipynb)
* [2 Logistic Regression|逻辑回归](2-LogisticRegression)
    * 2.1 [逻辑回归笔记](2-LogisticRegression/note/)
        * 2.1.1 [LSJU笔记-分类问题、逻辑回归](2-LogisticRegression/note/LSJU-chapter03_2.ipynb)
        * 2.1.2 [逻辑回归笔记](2-LogisticRegression/note/NOTE-logistic_regression.ipynb)
    * 2.2 [逻辑回归的实现](2-LogisticRegression/LogisticRegression.ipynb)
    * 2.3 [使用sklearn 逻辑回归](2-LogisticRegression/LogisticRegression_scikit-learn.ipynb)
    * 2.4 [逻辑回归识别手写数字](2-LogisticRegression/LogisticRegression_OneVsAll.ipynb)
    * 2.5 [使用sklearn 逻辑回归识别手写数字](2-LogisticRegression/LogisticRegression_OneVsAll_scikit-learn.ipynb)
* [3 Neural Network|神经网络](3-NeuralNetwok)
    * 3.1 [神经网络笔记](3-NeuralNetwok/note/NOTE-neural_network.md)
    * 3.2 [神经网络识别手写数字](3-NeuralNetwok/NeuralNetwork.ipynb)
* [4 SVM|支持向量机](4-SVM)
    * 4.1 [SVM笔记](4-SVM/NOTE-SVM.md)
    * 4.2 [SVM实现]
    * 4.3 [使用sklearn SVM](4-SVM/SVM_scikit-learn.ipynb)
* [5 K-Means|聚类](5-K-Means)
    * 5.1 [K-Mean 聚类笔记](5-K-Means/LSJU----NOTE-K-Means.ipynb)
    * 5.2 [K-Mean的实现](5-K-Means/K-Means.ipynb)
    * 5.3 [使用sklearn K-Means](5-K-Means/K-Means-sklearn.ipynb)
* [6 PCA|主成分分析](6-PCA)
    * 6.1 [PCA笔记](6-PCA/note/LSJU----NOTE-PCA.ipynb)
    * 6.2 [PCA的实现](6-PCA/PCA.ipynb)
    * 6.3 [使用sklearn PCA](6-PCA/PCA_sklearn.ipynb)
* [7 Anomaly Detection|异常检测](7-AnomalyDetection)
    * 7.1 [异常检测笔记](7-AnomalyDetection/note/NOTE-anomaly_detection.md)
    * 7.2 [异常检测实现](7-AnomalyDetection/AnomalyDetection.ipynb)
* [8 HMM|隐马尔可夫模型](8-HMM)
    * 8.1 [马尔科夫决策过程](8-HMM/note/LSJU-HMM.ipynb)其他参考 [这里](8-HMM/note/sn06.ipynb)
* [9 NaiveBayer|朴素贝叶斯](9-NaiveBayer)
    * 9.1 [笔记](9-NaiveBayer/note)
        * 9.1.1 [LSJU-生成学习算法、高斯判别分布、朴素贝叶斯算法](9-NaiveBayer/note/LSJU-chapter05.ipynb)
