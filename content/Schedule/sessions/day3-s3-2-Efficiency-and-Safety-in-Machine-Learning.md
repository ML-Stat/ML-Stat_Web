---
title: "Session 3: Efficiency and Safety in Machine Learning"
summary: "10:30 a.m. — 12:00 p.m., Saturday, Aug. 26, 2023"
tags: "s3-2"
---

Saturday, Aug. 26, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Efficiency and Safety in Machine Learning</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 10:30 a.m. — 12:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    location: 华东师范大学中北校区 文史楼203
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Pengkun Yang, Tsinghua University
</div>


________________________________________

<div class="row">
    <div class="left">
        <img src="/images/lingqing.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Qing Ling
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Byzantine-Robust Distributed Online Learning: Taming Adversarial Participants in an Adversarial Environment
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            In this talk, we consider distributed online learning under Byzantine attacks. The performance of an online learning algorithm is often characterized by (adversarial) regret, which evaluates the quality of one-step-ahead decision-making when an environment provides adversarial losses, and a sublinear bound is preferred. But we prove that, even with a class of state-of-the-art robust aggregation rules, in an adversarial environment and in the presence of Byzantine participants, distributed online gradient descent can only achieve a linear adversarial regret bound, which is tight. This is the inevitable consequence of Byzantine attacks, even though we can control the constant of the linear adversarial regret to a reasonable level. Interestingly, when the environment is not fully adversarial so that the losses of the honest participants are i.i.d. (independent and identically distributed), we show that sublinear stochastic regret, in contrast to the aforementioned adversarial regret, is possible. We develop a Byzantine-robust distributed online momentum algorithm to attain such a sublinear stochastic regret bound. Extensive numerical experiments corroborate our theoretical analysis.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/wulei.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Lei Wu
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Theoretical Analysis of Inductive Biases in Deep Convolutional Networks
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            In this talk, we'll discuss the inductive biases of deep convolutional neural networks (CNNs), which are believed to be vital drivers behind CNNs' exceptional performance on vision-like tasks. Specifically, we'll analyze the universality of CNNs and show that achieving it requires only a depth of $O(\log d)$, where $d$ is the input dimension. Additionally, we'll demonstrate that CNNs can efficiently capture long-range sparse correlations with only $O(\log^2d)$ samples. These are achieved through a novel combination of increased network depth and the utilization of multi-channeling and down-sampling. We'll also explore the inductive biases of weight sharing and locality through the lens of symmetry by introducing locally-connected networks (LCNs), which can be viewed as CNNs without weight sharing. We'll compare the performance of CNNs, LCNs, and fully-connected networks (FCNs) on a simple regression task and highlight the cruciality of weight sharing and the importance of locality. Our findings demonstrate that weight sharing and locality break different symmetries in the learning process, leading to provable separations between the two biases.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/zhiqin.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Zhi-Qin John Xu 
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Dropout Facilitate Condensation in Deep Learning
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            It is important to understand how the popular regularization method dropout helps neural network training find a good generalization solution. In this work, we theoretically derive the implicit regularization and find that, trained with dropout, input weights of hidden neurons would tend to condense on isolated orientations. This work points out the distinct characteristics of dropout compared with stochastic gradient descent.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/jingzhao.png" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Jingzhao Zhang
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Two Phases of Scaling Laws for Nearest Neighbor Classifiers
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            A scaling law refers to the observation that the test performance of a model improves as the number of training data increases. A fast scaling law implies that one can solve machine learning problems by simply boosting the data and the model sizes. Yet, in many cases, the benefit of adding more data can be negligible. In this work, we study the rate of scaling laws of nearest neighbor classifiers. We show that a scaling law can have two phases: in the first phase, the generalization error depends polynomially on the data dimension and decreases fast; whereas in the second phase, the error depends exponentially on the data dimension and decreases slowly. Our analysis highlights the complexity of the data distribution in determining the generalization error. When the data distributes benignly, our result suggests that nearest neighbor classifier can achieve a generalization error that depends polynomially, instead of exponentially, on the data dimension.
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