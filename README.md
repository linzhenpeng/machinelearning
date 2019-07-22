# machinelearning

机器学习笔记
<br/>
好记性不如烂笔头,多写笔记有利于日后查阅,修改.
<br/>
持续更新....
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/BASE/BASE.ipynb">机器学习相关概念/公式</a>
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/DataGame">比赛</a>
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/BASE/DataVisualization.ipynb">数据可视化</a>
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/LogisticRegression/LogisticRegression.ipynb">逻辑斯谛回归(LR)</a>
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/LogisticRegression/SVM.ipynb">SVM</a>
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/decisionTree/decisionTree.ipynb">决策树</a>
<br />
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/RandomForest/RandomForest.ipynb">随机森林</a>
<br />
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/Adaboost/Adaboost.ipynb">Adaboost</a>
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/GBDT/GBDT.ipynb">GBDT</a>
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/XGBoost/XGBoost.ipynb">XGBoost</a>
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/RecommendationSystem/RecommendationSystem.ipynb">RecommendationSystem</a>
<br/>
<a target="_blank" href="https://github.com/linzhenpeng/machinelearning/blob/master/FM/FM.ipynb">FM</a>
<br/>





机器学习模型总结 

    一、监督：{
    
    1.1 分类算法(线性和非线性)：{
    感知机
    
    KNN
    
    概率{
        朴素贝叶斯（NB）
        Logistic Regression（LR）
        最大熵MEM（与LR同属于对数线性分类模型）
    }
    
    支持向量机(SVM)
    
    决策树(ID3、CART、C4.5)
    
    assembly learning{
        Boosting{
            Gradient Boosting{
                GBDT
                xgboost（传统GBDT以CART作为基分类器，xgboost还支持线性分类器，这个时候xgboost相当于带L1和L2正则化项的逻辑斯蒂回归（分类问题）或者线性回归（回归问题）；xgboost是Gradient Boosting的一种高效系统实现，并不是一种单一算法。）
            }
            AdaBoost
        }   
        Bagging{
            随机森林
        }
        Stacking
    }
    
    ……
    }
    
    1.2 概率图模型：{
        HMM
        MEMM（最大熵马尔科夫）
        CRF
        ……
    }
    
    1.3 回归预测：{
        线性回归
        树回归
        Ridge岭回归
        Lasso回归
        ……
    }
    
    ……  
    }
    
    二、非监督：{
    2.1 聚类：{
        1. 基础聚类
            K—mean
            二分k-mean
            K中值聚类
            GMM聚类
        2. 层次聚类
        3. 密度聚类
        4. 谱聚类()
    }
    
    2.2 主题模型:{
        pLSA
        LDA隐含狄利克雷分析
    }
    
    2.3 关联分析：{
        Apriori算法
        FP-growth算法
    }
    
    2.4 降维：{
        PCA算法
        SVD算法
        LDA线性判别分析
        LLE局部线性嵌入
    }
    
    2.5 异常检测：
    ……
    }
    
    三、半监督学习
    
    四、迁移学习




