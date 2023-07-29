---
title: "Session 1: Recent Advances in High-dimensional and Large-scale Inference"
summary: "1:30 p.m. — 3:00 p.m., Friday, Aug. 25, 2023"
tags: "s1-2"
---

Friday, Aug. 25, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Recent Advances in High-dimensional and Large-scale Inference</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 1:30 p.m. — 3:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    location: 华东师范大学中北校区 文史楼203
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Yin Xia, Fudan University
</div>


________________________________________

<div class="row">
    <div class="left">
        <img src="/images/xiaojun.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Xiaojun Mao
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Distributed Semi-Supervised Sparse Statistical Inference
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            This paper is devoted to studying the semi-supervised sparse statistical inference in a distributed setup. An efficient multi-round distributed debiased estimator, which integrates both labeled and unlabeled data, is developed. We will show that the additional unlabeled data helps to improve the statistical rate of each round of iteration. Our approach offers tailored debiasing methods for $M$-estimation and generalized linear model according to the specific form of the loss function. Our method also applies to a non-smooth loss like absolute deviation loss. Furthermore, our algorithm is computationally efficient since it requires only one estimation of a high-dimensional inverse covariance matrix.  We demonstrate the effectiveness of our method by presenting simulation studies and real data applications that highlight the benefits of incorporating unlabeled data.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/liubin.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Bin Liu
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Change Point Detection for High-Dimensional Linear Models: A General Tail-Adaptive Approach
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            We study the change point detection problem for high-dimensional linear regression models. In this work, we propose a novel tail-adaptive approach for simultaneous change point testing and estimation. The method is built on a new loss function which is a weighted combination between the composite quantile and least squared losses, allowing us to borrow information of the possible change points from both the conditional mean and quantiles. For the change point testing, based on the adjusted L2-norm aggregation of a weighted score CUSUM process, we pro-pose a family of individual testing statistics with different weights to account for the unknown tail structures. Through a combination of the individual tests, a tail-adaptive test is further constructed that is powerful for sparse alternatives of regression coefficients’ changes under various tail structures. For the change point estimation, a family of argmax-based individual estimators is proposed once a change point is detected. In theory, for both individual and tail-adaptive tests, bootstrap procedures are proposed to approximate their limiting null distributions. Under some mild conditions, we justify the validity of the new tests in terms of size and power under the high-dimensional setup. The corresponding change point estimators are shown to be rate optimal up to a logarithm factor.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/bowen.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Bowen Gang
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Ranking and Selection in Large-Scale Inference of Heteroscedastic Units
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            The allocation of limited resources to a large number of potential candidates presents a pervasive challenge. In the context of ranking and selecting top candidates from heteroscedastic units, conventional methods often result in over-representations of subpopulations, and this issue is further exacerbated in large-scale settings where thousands of candidates are considered simultaneously. To address this challenge, we propose a new multiple comparison framework that incorporates a modified power notion to prioritize the selection of important effects and employs a novel ranking metric to assess the relative importance of units. We develop both oracle and data-driven algorithms, and demonstrate their effectiveness in controlling the error rates and achieving optimality. We evaluate the numerical performance of our proposed method using simulated and real data. The results show that our framework enables a more balanced selection of effects that are both statistically significant and practically important, and results in an objective and relevant ranking scheme that is well-suited to practical scenarios.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/feiyu.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Feiyu Jiang
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            High-Dimensional Dynamic Pricing under Non-Stationarity: Learning and Earning with Change-Point Detection
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            We consider a high-dimensional dynamic pricing problem under non-stationarity, where a firm sells products to T sequentially arriving consumers that behave according to an unknown demand model with potential changes at unknown times. The demand model is assumed to be a high-dimensional generalized linear model (GLM), allowing for a feature vector in R^d that encodes products and consumer information. To achieve optimal revenue (i.e., least regret), the firm needs to learn and exploit the unknown GLMs while monitoring for potential change-points. To tackle such a problem, we first design a novel penalized likelihood based online change-point detection algorithm for high-dimensional GLMs, which is the first algorithm in the change-point literature that achieves optimal minimax localization error rate for high-dimensional GLMs. A change-point detection assisted dynamic pricing (CPDP) policy is further proposed and achieves a near-optimal regret of order O(slog(Td)\sqrt{MT}), where s is the sparsity level and M is the number of change-points. This regret is accompanied with a minimax lower bound, demonstrating the optimality of CPDP (up to logarithmic factors). In particular, the optimality with respect to M is seen for the first time in the dynamic pricing literature, and is achieved via a novel accelerated exploration mechanism. Extensive simulation experiments and a real data application on online lending illustrate the efficiency of the proposed policy and the importance and practical value of handling non-stationarity in dynamic pricing.
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