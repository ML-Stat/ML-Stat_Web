---
title: "Statistical Foundations for Modern Machine Learning"
summary: "3:30 p.m. — 5:00 p.m., Friday, Aug. 25, 2023"
tags: "s2-2"
weight: 110
---

Friday, Aug. 25, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Statistical Foundations for Modern Machine Learning</span>
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
    Session Chair: Sai Li, Renmin University of China
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
            <div class="name-bar">Lin Liu</div>
            <div class="title">Title: Applying Modern Neural Networks in Statistical Problems: Semiparametrics, Causal Inference, and Differential Equations</div>
            <div class="abstract">
                <strong>Abstract:</strong> In this talk, we will survey some of our recent explorations of modern neural networks in problems spanning semiparametric statistics, causal inference, and forward & inverse problems in differential equations. We will discuss the practical performance, some limited theory, and when the theoretical results fall short of guiding practice. Time permitted, we will discuss some potential directions we are working on to narrow the theory-practice gap.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Qiong Zhang</div>
            <div class="title">Title: Gaussian Mixture Reduction with Composite Transportation Divergence</div>
            <div class="abstract">
                <strong>Abstract:</strong> Gaussian mixtures are widely used as a parametric distribution for approximating smooth density function of various, simplifying downstream inference tasks. They find extensive applications in density estimation, belief propagation, and Bayesian filtering. These applications often utilize finite Gaussian mixtures as initial approximations that are recursively updated. A challenge in these recursions is that the order of the Gaussian mixture increases exponentially, and the inference quickly becomes intractable. To overcome the difficulty, the Gaussian mixture reduction, which approximates a high order Gaussian mixture by one with a lower order, can be used. Although existing clustering-based methods are known for their satisfactory performance and computational efficiency, their convergence properties and optimal targets remain unknown. In this work, we propose a novel optimization-based Gaussian mixture reduction method based on composite transportation divergence (CTD). We develop a majorization-minimization algorithm for numerically computing the reduced Gaussian mixture and establish its theoretical convergence under general conditions. Furthermore, we demonstrate that many existing clustering-based methods are special cases of our approach, effectively bridging the gap between optimization-based and clustering-based techniques. Our unified framework empowers users to select the most appropriate cost function in CTD to achieve superior performance in their specific applications. Through extensive empirical experiments, we demonstrate the efficiency and effectiveness of our proposed method, showcasing its potential in various domains.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Pengkun Yang</div>
            <div class="title">Title: Towards a Mathematical Foundation of Federated Learning: A Statistical Perspective</div>
            <div class="abstract">
                <strong>Abstract:</strong> Federated Learning (FL) is a promising framework that has great potentials in privacy preservation and in lowering the computation load at the cloud. The successful deployment faces many challenges in both theory and practice such as data heterogeneity and client unavailability. In this talk, I will discuss the convergence and statistical efficiency of two widely-adopted FL algorithms: FedAvg and FedProx, from a statistical perspective. Our analysis is based on the standard non-parametric regression in a reproducing kernel Hilbert space. Additionally, we propose the concept of federation gain to quantify the impact of heterogeneity. Time permitted, FL from the perspectives of clustering and robust statistics will be discussed.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Ruijia Wu</div>
            <div class="title">Title: Supervised Topic Modeling: Optimal Estimation and Statistical Inference</div>
            <div class="abstract">
                <strong>Abstract:</strong> With the development of computer technology and the internet, increasingly large amounts of textual data are generated and collected every day. It is a significant challenge to analyze and extract meaningful and actionable information from vast amounts of unstructured textual data. Driven by applications in a wide range of fields, there is an increasing need for developing computationally efficient statistical methods for analyzing a massive amount of textual data with theoretical guarantees. In the presentation, I will discuss supervised topic modeling, which jointly considers a collection of documents and their paired side information. A bias-adjusted algorithm is developed to study the regression coefficients in the supervised topic modeling under the generalized linear model formulation. I will also introduce an approach to constructing valid confidence intervals. Applications of the proposed methods reveal meaningful latent topic structures of textual data. 
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