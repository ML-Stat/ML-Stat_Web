---
title: "Recent Developments on High-Dimensional Statistical Learning"
summary: "10:30 a.m. — 12:00 p.m., Saturday, Aug. 26, 2023"
tags: "s3-4"
weight: 135
---

Saturday, Aug. 26, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Recent Developments on High-Dimensional Statistical Learning</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 10:30 a.m. — 12:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    Location: 华东师范大学普陀校区 文史楼215
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Yong He, Shandong University
</div>


________________________________________

<html>
<head>
    <title>Customizing Personal Large-Scale Language Model</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            /* padding: 20px; */
            background-color: #f5f5f5;
        }
        .row {
            display: flex;
            justify-content: center;
        }
        .container {
            max-width: 800px;
            background-color: #ffffff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            margin: 10px;
        }
        .name-bar {
            font-size: 24px;
            font-weight: bold;
            color: #333;
            margin-bottom: 10px;
        }
        .institute {
            font-size: 18px;
            color: #333;
            margin-bottom: 10px;
        }
        .title {
            font-size: 20px;
            text-decoration: underline;
            margin-bottom: 10px;
        }
        .abstract {
            font-size: 20px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="row">
        <div class="container">
            <div class="name-bar">Yong He</div>
            <div class="institute">Shandong University</div>
            <div class="title">Title: The Role of Fine-Tuning: Transfer Learning for High-Dimensional M-Estimators with Decomposable Regularizers</div>
            <div class="abstract">
                <strong>Abstract:</strong> Transfer learning algorithms have been developed in various applicational contexts while only a few of them offer statistical guarantees in high-dimensions. Among these work, the differences between the target and sources, a.k.a. the contrasts, are typically modeled as, or at least close to, vectors with certain low-dimensional structure (e.g., sparsity), resulting in a separate debiasing step after a preceding pooling estimation procedure. Under such intuitive yet powerful framework, additional homogeneity conditions on Hessian matrices of the population loss functions are often imposed to preserve the delicate low-dimensional structure of the contrasts during pooling, which is either unrealistic in practice or easily destroyed by basic data transformation such as standardization. In this article, under the general M-estimators framework with decomposable regularizers, we highlight the role of fine-tuning underneath the conspicuous gain of the debiasing step in transfer learning. Namely, we find it is possible to enhance estimation accuracy by fine-tuning a primal estimator sufficiently close to the true target one. Our theory suggests slightly enlarging the pooling regularization strength when either the contrast's low-dimensional structure or the homogeneity of Hessian matrices is violated. Traditional linear regression and generalized low-rank trace regression in high-dimensions are discussed as two specific examples under our framework. When the informative source datasets are unknown, a novel truncated-penalized algorithm is proposed to directly output the primal estimator by simultaneously selecting the useful sources and its oracle property is proved. Extensive numerical experiments are conducted to validate the theoretical assertions. A case study on the air quality regulation in China by transfer learning is also provided for illustration.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Long Yu</div>
            <div class="institute">Shanghai University of Finance and Economics</div>
            <div class="title">Title: Matrix Quantile Factor Model</div>
            <div class="abstract">
                <strong>Abstract:</strong> This paper introduces a matrix quantile factor model for matrix-valued data with a low-rank structure. We estimate the row and column factor spaces via minimizing the empirical check loss function over all panels. We show the estimates converge at rate 1/min{(p_1p_2)^0.5, (p_1T)^0.5, (p_2T)^0.5}  in average Frobenius norm, where p_1, p_2, T are the row dimensionality, column dimensionality and length of the matrix sequence. This rate is faster than that of the quantile estimates via ``flattening" the matrix model into a large vector model. Smoothed estimates are given and their central limit theorems are derived under some mild condition. We provide three consistent criteria to determine the pair of row and column factor numbers. Extensive simulation studies and an empirical study justify our theory.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Zhe Li</div>
            <div class="institute">Fudan University</div>
            <div class="title">Title: Consistent Selection of the Number of Groups in Panel Models via Sample-Splitting</div>
            <div class="abstract">
                <strong>Abstract:</strong> Group number selection is a key question for group panel data modelling. In this work, we develop a cross validation method to tackle this problem. Specifically, we split the panel data into a training dataset and a testing dataset on the time span. We first use the training dataset to estimate the parameters and group memberships. Then we apply the fitted model to the testing dataset and then the group number is estimated by minimizing certain loss function values on the testing dataset. We design the loss functions for panel data models either with or without fixed effects. The proposed method has two advantages. First, the method is totally data-driven thus no further tuning parameters are involved. Second, the method can be flexibly applied to a wide range of panel data models. Theoretically, we establish the estimation consistency by taking advantage of the optimization property of the estimation algorithm. Experiments on a variety of synthetic and empirical datasets are carried out to further illustrate the advantages of the proposed method.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Yang Zhou</div>
            <div class="institute">Beijing Normal University</div>
            <div class="title">Title: Covariance Test for Discretely Observed Functional Data  </div>
            <div class="abstract">
                <strong>Abstract:</strong> In this paper, covariance test is studied for discretely observed functional data with noise. A projection-based test statistic is constructed with growing number of estimated eigenfunctions, which has the asymptotic Chi-squared distribution facilitated by advancing the perturbation bounds of estimated eigenfunctions. The theoretic analysis reveals a connection among the permissible truncation level, the sampling frequency and the sample size. Some numerical studies are investigated.
            </div>
        </div>
    </div>
</body>
</html>

<style>

.tip{}

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