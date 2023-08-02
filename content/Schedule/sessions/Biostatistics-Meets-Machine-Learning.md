---
title: "Biostatistics Meets Machine Learning"
summary: "3:30 p.m. — 5:00 p.m., Friday, Aug. 25, 2023"
tags: "s2-4"
weight: 90
---

Friday, Aug. 25, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Biostatistics Meets Machine Learning</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 3:30 p.m. — 5:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    location: 华东师范大学普陀校区 文史楼215
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Tao Hu, Capital Normal University
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
            <div class="name-bar">Shuwei Li</div>
            <div class="institute">Guangzhou University</div>
            <div class="title">Title: Factor-Augmented Transformation Models for Interval-Censored Failure Time Data</div>
            <div class="abstract">
                <strong>Abstract:</strong> Interval-censored failure time data frequently arise in various scientific studies where each subject experiences periodical examinations for the occurrence of the failure event of interest, and the failure time is only known to lie in a specific time interval. In addition, collected data may include multiple observed variables with a certain degree of correlation, leading to severe multicollinearity issues. This study proposes a factor-augmented transformation model to analyze interval-censored failure time data while reducing model dimensionality and avoiding multicollinearity elicited by multiple correlated covariates.We provide a joint modeling framework by comprising a factor analysis model to group multiple observed variables into a few latent factors and a class of semiparametric transformation models with the augmented factors to examine their and other covariate effects on the failure event. Furthermore, we propose a nonparametric maximum likelihood estimation approach and develop a computationally stable and reliable expectation-maximization algorithm for its implementation. We establish the asymptotic properties of the proposed estimators and conduct simulation studies to assess the empirical performance of the proposed method. An application to the Alzheimer's Disease Neuroimaging Initiative study is provided. An R package  ICTransCFA is also available for practitioners. 
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Baosheng Liang</div>
            <div class="institute">Peking University</div>
            <div class="title">Title: An Accumulative Delta-Radiomics Model Based on Cone-Beam CT for the Prediction of Radiation Pneumonitis in Thoracic Cancer Patients Treated with Radiotherapy</div>
            <div class="abstract">
                <strong>Abstract:</strong> This work aims to construct a cone-beam CT-based delta radiomics nomogram for individualized prediction of radiation pneumonitis (RP) in thoracic cancer patients treated with radiotherapy. Weekly CBCT images of 92 thoracic cancer patients treated with image-guided-radiotherapy were retrospectively included for this study. Images before the first treatment and the 1st, 2nd, 3rd week thereafter were collected. Novel accumulative CBCT delta-radiomics features (Delta-RFaccu) was proposed to stack the temporal changes of lung tissues over the treatment course. Significance tests of difference were performed to screen delta-radiomics features before the principal component analysis (PCA). The first principal component was taken as the signature of the corresponding Delta-RFi. The predicting performance of signature was evaluated and compared by univariate Logistic regression. Finally, a multivariate Logistic regression model for RP prediction was constructed by incorporating the best Delta-RFi signature and important dosimetric predictors. Calibration curves and decision curves showed accurate prediction and satisfactory clinical performance of the proposed comprehensive model. 
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Tao Sun</div>
            <div class="institute">Renmin University of China</div>
            <div class="title">Title: Neural Network on Interval Censored Data with Application to the Prediction of Alzheimer’s Disease</div>
            <div class="abstract">
                <strong>Abstract:</strong> Alzheimer's disease (AD) is a progressive and polygenic disorder that affects millions of individuals each year. Given that there have been few effective treatments yet for AD, it is highly desirable to develop an accurate model to predict the full disease progression profile based on an individual's genetic characteristics for early prevention and clinical management. This work uses data composed of all four phases of the Alzheimer's Disease Neuroimaging Initiative (ADNI) study, including 1740 individuals with 8 million genetic variants. We tackle several challenges in this data, characterized by large-scale genetic data, interval-censored outcome due to intermittent assessments, and left truncation in one study phase (ADNIGO). Specifically, we first develop a semiparametric transformation model on interval-censored and left-truncated data and estimate parameters through a sieve approach. Then we propose a computationally efficient generalized score test to identify variants associated with AD progression. Next, we implement a novel neural network on interval-censored data (NN-IC) to construct a prediction model using top variants identified from the genome-wide test. Comprehensive simulation studies show that the NN-IC outperforms several existing methods in terms of prediction accuracy. Finally, we apply the NN-IC to the full ADNI data and successfully identify subgroups with differential progression risk profiles.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Da Xu</div>
            <div class="institute">Northeast Normal University</div>
            <div class="title">Title: Regression Analysis of Misclassified Current Status Data with Informative Observation Times </div>
            <div class="abstract">
                <strong>Abstract:</strong> Misclassified current status data arises if each study subject can only be observed once and the observation status is determined by a diagnostic test with imperfect sensitivity and specificity. For the situation, another issue that may occur is that the observation time may be correlated with the interested failure time, which is often referred to as informative censoring or observation times. It is well-known that in the presence of informative censoring, the analysis that ignores it could yield biased or even misleading results. In this paper, the authors consider such data and propose a frailty-based inference procedure. In particular, an EM algorithm based on Poisson latent variables is developed and the asymptotic properties of the resulting estimators are established. The numerical results show that the proposed method works well in practice and an application to a set of real data is provided. 
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