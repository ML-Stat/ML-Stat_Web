---
title: "Machine Learning for Interpretability"
summary: "1:30 p.m. — 3:00 p.m., Saturday, Aug. 26, 2023"
tags: "s4-1"
weight: 180
---

Saturday, Aug. 26, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Machine Learning for Interpretability</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 1:30 p.m. — 3:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    location: 华东师范大学普陀校区 文史楼201
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Zhou Yu, East China Normal University
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
            padding: 20px;
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
            <div class="name-bar">Yundong Tu</div>
            <div class="title">Title: Structurally Grouped Approximate Factor Models</div>
            <div class="abstract">
                <strong>Abstract:</strong> This paper explores the group structure in large dimensional approximate factor models, which portrays homogeneous effects of the common factors on the individuals that fall into the same group. With the initial principal component estimates, we identify the unknown group structure by a combination of the agglomerative hierarchical clustering algorithm and an information criterion. The loadings and factors are then re-estimated conditional on the identified groups. Under some regularity conditions, we establish the consistency of the membership estimator as well as that of the group number estimator obtained from the information criterion. The new estimators under the group structure are shown to achieve efficiency gain compared to those obtained without this information. Numerical simulations and empirical applications demonstrate the nice finite sample performance of our proposed approach when group structure presents.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Xin He</div>
            <div class="title">Title: Efficient learning of Nonparametric Directed Acyclic Graph with Statistical Guarantee</div>
            <div class="abstract">
                <strong>Abstract:</strong> Directed acyclic graph (DAG) models are widely used to represent casual   relations among collected nodes. This paper proposes an efficient and consistent method to learn DAG with a general causal dependence structure, which is in sharp contrast to most existing methods assuming linear dependence of causal relations.  To facilitate DAG learning, the proposed method leverages the concept of topological layer, and connects nonparametric DAG learning with kernel ridge regression in a smooth reproducing kernel Hilbert space (RKHS) and learning gradients by showing that  the topological  layers of a nonparametric DAG can be exactly reconstructed via kernel-based estimation,  and the parent-child relations can be obtained directly by computing the estimated gradient function. The developed algorithm is computationally efficient in the sense that it attempts to solve a convex optimization problem with an analytic solution, and the gradient functions can be directly computed by using the derivative reproducing property in the smooth RKHS. The asymptotic properties of the proposed method are established in terms of exact DAG recovery without requiring any explicit model specification. Its superior performance is also supported by a variety of simulated and a real-life example.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Ziqi Chen</div>
            <div class="title">Title: K-Nearest-Neighbor Local Sampling Based Conditional Independence Testing</div>
            <div class="abstract">
                <strong>Abstract:</strong> Conditional independence (CI) testing is a fundamental task in statistics and machine learning, but its effectiveness is hindered by the challenges posed by high-dimensional conditioning variables and limited data samples. This article introduces a novel testing approach to address these challenges and enhance control of the type I error while achieving high power under alternative hypotheses. The proposed approach incorporates a computationally efficient classifier-based conditional mutual information (CMI) estimator, capable of capturing intricate dependence structures among variables. To approximate a distribution encoding the null hypothesis, a k-nearest-neighbor local sampling strategy is employed. An important advantage of this approach is its ability to operate without assumptions about distribution forms or feature dependencies. Furthermore, it eliminates the need to derive asymptotic null distributions for the estimated CMI and avoids dataset splitting, making it particularly suitable for small datasets. The method presented in this article demonstrates asymptotic control of the type I error and consistency against all alternative hypotheses. Extensive analyses using both synthetic and real data highlight the computational efficiency of the proposed test. Moreover, it outperforms existing state-of-the-art methods in terms of type I and II errors, even in scenarios with high-dimensional conditioning sets. Additionally, the proposed approach exhibits robustness in the presence of heavy-tailed data.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Qixian Zhong</div>
            <div class="title">Title: Neural Networks for Partially Linear Quantile Regression</div>
            <div class="abstract">
                <strong>Abstract:</strong> Deep learning has enjoyed tremendous success in a variety of applications but its application to quantile regression remains scarce. A major advantage of the deep learning approach is its flexibility to model complex data in a more parsimonious way than nonparametric smoothing methods. However, while deep learning brought breakthroughs in prediction, it is not well suited for statistical inference due to its black box nature. In this paper, we leverage the advantages of deep learning and apply it to quantile regression where the goal is to produce interpretable results and perform statistical inference. We achieve this by adopting a semiparametric approach based on the partially linear quantile regression model, where covariates of primary interest for statistical inference are modelled linearly and all other covariates are modelled nonparametrically by means of a deep neural network. In addition to the new methodology, we provide theoretical justification for the proposed model by establishing the root-n consistency and asymptotically normality of the parametric coefficient estimator and the minimax optimal convergence rate of the neural nonparametric function estimator. Across numerical studies, the proposed model empirically produces superior estimates and more accurate predictions than various alternative approaches. 
            </div>
        </div>
    </div>
</body>
</html>

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
