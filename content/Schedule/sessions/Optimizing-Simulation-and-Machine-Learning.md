---
title: "Optimizing Simulation and Machine Learning"
summary: "3:30 p.m. — 5:00 p.m., Saturday, Aug. 26, 2023"
tags: "s5-2"
weight: 210
---

Saturday, Aug. 26, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Optimizing Simulation and Machine Learning</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 3:30 p.m. — 5:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    location: 华东师范大学普陀校区 文史楼203
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Yijie Peng, Peking University
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
            <div class="name-bar">Haidong Li</div>
            <div class="title">Title: Efficient Bandwidth Selection for Kernel Density Estimation</div>
            <div class="abstract">
                <strong>Abstract:</strong> We consider bandwidth selection for kernel density estimation. The performance of kernel density estimator heavily relies on the quality of the bandwidth. In this study, we propose an efficient plug-in kernel density estimator which first perturbs the bandwidth to estimate the optimal bandwidth, followed by applying a kernel density estimator with the estimated optimal bandwidth. The proposed method utilizes the zeroth-order information of kernel function and has a faster convergence rate than other plug-in methods in existing literature. Simulation results demonstrate superior finite sample performance and robustness of the proposed method.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Liang Ding</div>
            <div class="title">Title: Kernel Multi-Grid: Accelerate Back-Fitting via Intrinsic Sparsity of Matern Kernels</div>
            <div class="abstract">
                <strong>Abstract:</strong> Backfitting is an iterative method widely used for training general additive models, with applications in various domains including LASSO, Bayesian inference, and neural networks. However, the convergence behavior in terms of its iteration number remains unknown. This study establishes a novel connection between backfitting and the finite-difference method within the framework of Gaussian processes. Leveraging this connection, we prove that backfitting necessitates a minimum of O(n log n) iterations to converge, where n is the data size. In spired by algebraic multigrid in finite difference, we modify backfitting by adding a sparse regression step in each iteration. This simple modification can be computed in O(n) time and significantly reduces the required iteration to O(log n).
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Kun Zhang</div>
            <div class="title">Title: Simulating a Confidence Interval for Conditional Value-at-Risk</div>
            <div class="abstract">
                <strong>Abstract:</strong> Evaluation of portfolio loss often requires time-consuming simulation, making the measurement of portfolio risk computationally challenging. In this paper, we construct lower and upper bounds for a widely used risk measure, the so-called conditional Value-at-Risk (CVaR), by exploiting its structural properties. These bounds serve as useful complements to the plug-in estimates in the literature, by providing information on the magnitudes of their biases. By leveraging existing methods for approximating portfolio loss function, we propose efficient estimators for the proposed lower and upper bounds. Moreover, we establish two confidence intervals for the two bounds. Combine them leading to a confidence interval for CVaR. Numerical results suggest that this confidence interval works quite well.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Lei Lei</div>
            <div class="title">Title: Estimating Confidence Intervals and Regions for Quantiles by Monte Carlo Simulation</div>
            <div class="abstract">
                <strong>Abstract:</strong> We propose methods based on batching, sectioning, and generalized likelihood ratios (GLRs) for computing confidence intervals (CIs) and confidence regions (CRs) for quantiles in finite-horizon and steady-state simulations. We establish the uniform consistency of the GLR estimators and the asymptotic validity of the respective CIs and CRs for quantiles. We also establish the asymptotic validity of CIs and CRs for quantiles by batching and sectioning methods for both finite-horizon and steady-state simulations. Numerical experiments demonstrate the validity of the aforementioned methods as the coverage rates of the CIs and CRs approach the target levels for appropriately large sample sizes.
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
