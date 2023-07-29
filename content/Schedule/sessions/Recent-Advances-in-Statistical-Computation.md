---
title: "Recent Advances in Statistical Computation"
summary: "1:30 p.m. — 3:00 p.m., Friday, Aug. 25, 2023"
tags: "s1-1"
---

Friday, Aug. 25, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Recent Advances in Statistical Computation</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 1:30 p.m. — 3:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    location: 华东师范大学中北校区 文史楼201
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Fang Fang, East China Normal University
</div>


________________________________________

<div class="row">
    <div class="left">
        <img src="/images/jialiang.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Jialiang Li
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            A Network Approach to Compute Hypervolume under ROC Manifold for Multi-Class Biomarkers
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            Computation of hypervolume under ROC manifold (HUM) is necessary to evaluate biomarkers for their capability to discriminate among multiple disease types or diagnostic groups. However, the original definition of HUM involves multiple integration and thus a medical investigation for multi-class ROC analysis could suffer from huge computational cost when the formula is implemented naively. We introduce a novel graph-based approach to compute HUM efficiently in this paper. The computational method avoids the time-consuming multiple summation when sample size or the number of categories is large. We conduct extensive simulation studies to demonstrate the improvement of our method over existing R packages. We apply our method to two real biomedical data sets to illustrate its application.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/xuening.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Xuening Zhu
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Distributed Estimation and Inference for Spatial Autoregression Model with Large Scale Networks
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            The rapid growth of online network platforms generates large-scale network data and it poses great challenges for statistical analysis using the spatial autoregression (SAR) model. In this work, we develop a novel distributed estimation and statistical inference framework for the SAR model on a distributed system. We first propose a distributed network least squares approximation (DNLSA) method. This enables us to obtain a one-step estimator by taking a weighted average of local estimators on each worker. Afterwards, a refined two-step estimation is designed to further reduce the estimation bias. For statistical inference, we utilize a random projection method to reduce the expensive communication cost. Theoretically, we show the consistency and asymptotic normality of both the one-step and two-step estimators. In addition, we provide theoretical guarantee of the distributed statistical inference procedure. The theoretical findings and computational advantages are validated by several numerical simulations implemented on the Spark system. Lastly, an experiment on the Yelp dataset further illustrates the usefulness of the proposed methodology.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/xiaozhou.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Xiaozhou Wang
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Some Recent Progress in Quantile Regression Analysis
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            In this talk, we will introduce some research results on quantile regression and composite quantile regression models. The algorithms and theoretical properties are presented. Numerical studies are conducted to demonstrate the performance of the proposed methodologies.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/fangfang.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Fang Fang
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Kolmogorov-Smirnov Learning
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            Kolmogorov-Smirnov (KS) statistic has been widely used in many areas to evaluate the performance of binary classification. However, almost no classification algorithm tries to optimize it directly at the training stage due to the computational and theoretical challenges brought by the special form of KS. In this talk, we will introduce our work about Kolmogorov-Smirnov learning which uses KS as the target function. Several methods will be discussed and their theoretical and empirical results will be presented. 
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