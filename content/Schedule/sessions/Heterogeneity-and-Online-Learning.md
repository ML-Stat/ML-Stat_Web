---
title: "Heterogeneity and Online Learning"
summary: "10:30 a.m. — 12:00 p.m., Saturday, Aug. 26, 2023"
tags: "s3-1"
weight: 150
---

Saturday, Aug. 26, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Heterogeneity and Online Learning</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 10:30 a.m. — 12:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    location: 华东师范大学普陀校区 文史楼201
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Xiaojun Mao, Shanghai Jiao Tong University
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
            <div class="name-bar">Yifan Cui</div>
            <div class="institute">Zhejiang University</div>
            <div class="title">Title: Proximal Causal Learning of Heterogeneous Treatment Effects</div>
            <div class="abstract">
                <strong>Abstract:</strong> Efficiently and flexibly estimating treatment effect heterogeneity is an important task in a wide variety of settings ranging from medicine to marketing, and there are a considerable number of promising conditional average treatment effect estimators currently available. These, however, typically rely on the assumption that the measured covariates are enough to justify conditional exchangeability. We propose the P-learner, motivated by the R- and DR-learner, a tailored two-stage loss function for learning heterogeneous treatment effects in settings where exchangeability given observed covariates is an implausible assumption, and we wish to rely on proxy variables for causal inference. Our proposed estimator can be implemented by off-the-shelf loss-minimizing machine learning methods, which in the case of kernel regression satisfies an oracle bound on the estimated error as long as the nuisance components are estimated reasonably well.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Sai Li</div>
            <div class="institute">Renmin University of China</div>
            <div class="title">Title: Learning Invariant Representations for Algorithmic Fairness and Domain Generalization with Minimax Optimality</div>
            <div class="abstract">
                <strong>Abstract:</strong> Machine learning methods often assume that the test data have the same distribution as the training data. However, this assumption may not hold due to multiple levels of heterogeneity. In this work, we address the problem of fair and generalizable machine learning in unseen environments. we first propose a training environment-based oracle, FAIRM, which has desirable fairness and domain generalization properties in unseen environments under a diversity-type of conditions. We then adapt the FAIRM framework to linear models and consider two classes of invariant representations: invariant features and invariant subspaces. We develop efficient algorithms for these models and provide finite sample guarantees. We evaluate our method on Color-MNIST data and a census income data set based on high-dimensional linear models and show that it outperforms ERM and Maxmin estimators.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Yaowu Liu</div>
            <div class="institute">Southwest University of Finance and Economics</div>
            <div class="title">Title: Ensemble Methods for Testing a Global Null</div>
            <div class="abstract">
                <strong>Abstract:</strong> Testing a global null is a canonical problem in statistics and has a wide range of applications. In view of the fact that no uniformly most powerful test exists, prior and/or domain knowledge are commonly used to focus on a certain class of alternatives to improve the testing power. However, it is generally challenging to develop tests that are particularly powerful against a certain class of alternatives. In this paper, motivated by the success of ensemble learning methods for prediction or classification, we propose an ensemble framework for testing that mimics the spirit of random forests to deal with the challenges. Our ensemble testing framework aggregates a collection of weak base tests to form a final ensemble test that maintains strong and robust power. We apply the framework to four problems about global testing in different classes of alternatives arising from Whole Genome Sequencing (WGS) association studies. Specific ensemble tests are proposed for each of these problems, and their theoretical optimality is established in terms of Bahadur efficiency. Extensive simulations and an analysis of a real WGS dataset are conducted to demonstrate the type I error control and/or power gain of the proposed ensemble tests. 
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Dong XIA</div>
            <div class="institute">Hong Kong University</div>
            <div class="title">Title: Online Tensor Learning: Computational and Statistical Trade-Offs, Adaptivity and Optimal Regret </div>
            <div class="abstract">
                <strong>Abstract:</strong> Large tensor learning algorithms are usually computationally expensive and require storing an exceedingly large amount of data. In this paper, we propose a unified online Riemannian gradient descent (oRGrad) algorithm for tensor learning, which is computationally fast, consumes much less memory, and can deal with sequentially arrived data and make timely prediction. The algorithm is applicable to both linear and generalized linear models. We observe an intriguing trade-off between the computational convergence rate and statistical rate of oRGrad. Increasing the step size accelerates computational convergence but leads to larger statistical error, whereas a smaller step size yields smaller statistical error at the expense of slower computational convergence. If the time horizon T is known, oRGrad achieves statistical optimality by choosing an appropriate fixed step size. Besides the aforementioned benefits, we discover that noisy tensor completion is particularly blessed by online algorithms in that it avoids the trimming procedure and guarantees sharp entry-wise statistical error, which is usually deemed technically challenging for offline methods. Online algorithms render powerful martingale tools applicable for theoretical analysis. The regret of oRGrad is investigated and a fascinating trilemma concerning the computational convergence rate, statistical error, and regret is observed. By choosing an appropriate constant step size, oRGrad achieves an O(T^1/2) regret. We then introduce the adaptive-oRGrad algorithm, which can achieve the optimal O(log T ) regret by adaptively selecting the step sizes, regardless of whether the time horizon is known or unknown. The adaptive-oRGrad algorithm can also attain statistically optimal error without knowing the horizon. Comprehensive numerical simulation results corroborate our theoretical findings.
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