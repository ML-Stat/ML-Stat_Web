---
title: "Statistical Prediction and Machine Learning"
summary: "1:30 p.m. — 3:00 p.m., Saturday, Aug. 26, 2023"
tags: "s4-4"
weight: 19
---

Saturday, Aug. 26, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Statistical Prediction and Machine Learning</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 1:30 p.m. — 3:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    location: 华东师范大学中北校区 文史楼215
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Deyu Meng, Xian Jiaotong University
</div>


________________________________________

<div class="row">
    <div class="left">
        <img src="/images/zhiji.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Zhiji Yang
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Deep Multi-Class Support Vector Network with Probabilistic Calibration
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            The traditional support vector machine (SVM) is a well-known supervised learning method for binary classification, especially on small sample data. However, SVM has some limitations in prediction accuracy and adaptability for complex data such as sequential text data and structural image data. When solving multi-classification problem, traditional SVM needs to apply one-vs-one or one-vs-rest strategy. The computational cost of these strategies grows exponentially as the number of data categories increases. To improve the classification accuracy and convenience of the original SVM for multi-classification task, we propose a deep multi-class support vector network (DMSVN). DMSVN can take advantage of the excellent feature extraction methods of neural networks for high dimensional data. It also avoids generating binary classifiers multiple times to determine the sample class in the multi-classification problem. DMSVN has better interpretation than traditional neural networks. Besides, an auxiliary convolutional neural network is constructed to implement probabilistic calibration, which allows the model prediction to be closer to the true value.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/xianli.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Xianli Pan
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            针对稀疏模型的安全筛选算法的相关研究
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            安全筛选系列算法利用稀疏优化模型最优解中存在大量0分量的特点，在求解模型前准确找出解中0分量位置，并由此降低数据规模，加速模型求解运算。我们主要针对当前安全筛选算法在筛选有效性、安全性上存在的问题，提出若干改进方案，进行误差纠正以及进一步提高模型求解大规模问题的效率。
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/xinyu.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Xinyu Chen
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Optimal Weighted Random Forests
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            The random forest (RF) algorithm has become a very popular prediction method for its great flexibility and promising accuracy. In RF, it is conventional to put equal weights on all the base learners (trees) to aggregate their predictions. However, the predictive performances of different trees within the forest can be very different due to the randomization of the embedded bootstrap sampling and feature selection. In this paper, we focus on RF for regression and propose two optimal weighting algorithms, namely the 1 Step Optimal Weighted RF (1step-WRFopt) and 2 Steps Optimal Weighted RF (2steps-WRFopt), that combine the base learners through the weights determined by weight choice criteria. Under some regularity conditions, we show that these algorithms are asymptotically optimal in the sense that the resulting squared loss and risk are asymptotically identical to those of the infeasible but best possible model averaging estimator. Numerical studies conducted on real-world data sets indicate that these algorithms outperform the equal-weight forest and two other weighted RFs proposed in existing literature in most cases.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/shijin.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Shijin Gong
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
           Towards Optimal Neural Networks: The Role of Sample Splitting in Hyperparameter Selection
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            While artificial neural networks have demonstrated exceptional practical success in a variety of domains, investigations into their theoretical characteristics, such as their approximation power, statistical properties, and generalization performance, have made significant strides. In this paper, we construct a novel theory for understanding the effectiveness of neural networks by discovering the mystery underlying a common practice during neural network model construction: sample splitting. Our theory demonstrates that, the optimal hyperparameters derived from sample splitting can enable a neural network model that asymptotically minimizes the prediction risk. We conduct extensive experiments across different application scenarios and network architectures, and the results manifest our theory's effectiveness.
        </div>
    </div>
</div>

<style>

.tip {
    height: 30px;
    line-height: 30px;
}

.icon {
    width: 15px;
}

.row {
    padding: 10px; 
    height: auto; 
    border-bottom-width: 2px; 
    border-style: solid; 
    border-color: #E4E7ED; 
    padding-bottom: 20px; 
    padding-top: 20px;
    display: flex; 
    text-align: justify;
}

.left {
    min-width: 150px !important;
    text-align: center;
}

.avatar {
    width: 120px;
    height: 160px;
    max-width: 100%;
    border-radius: 10px;
}

.right {
    margin-left: 10px; 
    max-width: 80%;
}


.font-small {
    /* font-size: 16px; */
}

.font-bold {
    font-weight: bold;
}
</style>
