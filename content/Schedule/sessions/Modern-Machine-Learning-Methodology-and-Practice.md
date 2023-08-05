---
title: "Modern Machine Learning Methodology and Practice"
summary: "3:30 p.m. — 5:00 p.m., Friday, Aug. 25, 2023"
tags: "s2-3"
weight: 100
---

Friday, Aug. 25, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Modern Machine Learning Methodology and Practice</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 3:30 p.m. — 5:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    Location: 华东师范大学普陀校区 文史楼211
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: Yixuan Qiu, Shanghai University of Finance and Economics
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
            <div class="name-bar">Shiyuan He</div>
            <div class="institute">Renmin University of China</div>
            <div class="title">Title: Channelling Multimodality Through a Unimodalizing Transport: Warp-U Sampler and Stochastic Bridge Sampling</div>
            <div class="abstract">
                <strong>Abstract:</strong> Monte Carlo integration is fundamental in scientific and statistical computation, but requires reliable samples from the target distribution, which presents a substantial challenge in the case of multi-modal distributions. Existing methods often involve time-consuming tuning, and typically lack tailored estimators for efficient use of the samples. To address these issues, this study adapts the Warp-U transformation (Wang et al.; 2022), used in estimation of normalizing constants, into a more extensive multi-modal sampling strategy. The central idea is simple but promising: construct a stochastic map to transport a multi-modal density into a uni-modal one (e.g., Gaussian), and subsequently invert the transport but with new stochasticity injected. For the proposed Warp-U sampler, an unbiased estimation scheme based on two coupled chains is devised, and a stochastic bridge sampling estimator is developed to reduce the computational cost for normalizing constant estimation. Our overall approach requires less tuning and is easier to apply than common alternatives. Theoretically we establish the ergodicity of our sampling algorithm, and that our stochastic bridge sampling estimator has greater (asymptotic) precision per CPU second compared with the Warp-U bridge estimator under practical conditions. The advantages of our approach are demonstrated through simulation studies and an application to exoplanet detection.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Tianyang Hu</div>
            <div class="institute">Huawei Noah's Ark Lab</div>
            <div class="title">Title: Rethinking Self-Supervised Learning From the Perspective of Distance Preserving</div>
            <div class="abstract">
                <strong>Abstract:</strong> Aiming to extract low-dimensional features from data, Self-Supervised Learning (SSL) has garnered considerable empirical success, particularly for image-related tasks. In this talk, we provide a novel understanding of SSL from the perspective of preserving the "distance" between distributions across different dimensions. In essence, SSL aims to match in distribution between the low-dimensional feature distribution and the high-dimensional data distribution. 
            SSL has two primary applications -- discriminative and generative, each corresponding to one of the existing "distance" definitions to address the dimensional mismatch. Specifically, we show that discriminative SSL, e.g., contrastive learning, bears a close relation to the Gromov-Wasserstein distance, which shifts the comparison from marginal distributions to pairwise joint distributions. On the other hand, generative SSL, e.g., autoencoder, is closely related to another type of distance extending traditional ones such as Wasserstein distance and $f$-divergence, to different dimensions by embedding or projection. The newfound perspective facilitates both a better theoretical understanding and methodological guidance for practical improvements.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Ben Dai</div>
            <div class="institute">The Chinese University of Hong Kong</div>
            <div class="title">Title: Inference of Nonlinear Causal Effects with GWAS Summary Data</div>
            <div class="abstract">
                <strong>Abstract:</strong> Large-scale genome-wide association studies (GWAS) have offered an exciting opportunity to discover putative causal genes or risk factors associated with diseases by using SNPs as instrumental variables (IVs). However, conventional approaches assume linear causal relations partly for simplicity and partly for the only availability of GWAS summary data. In this work, we propose a novel model for transcriptome-wide association studies (TWAS) to incorporate nonlinear relationships across IVs, an exposure, and an outcome, which is robust against violations of the valid IV assumptions and permits the use of GWAS summary data. We decouple the estimation of a marginal causal effect and a nonlinear transformation, where the former is estimated via sliced inverse regression and a sparse instrumental variable regression, and the latter is estimated by a ratio-adjusted inverse regression. On this ground, we propose an inferential procedure. An application of the proposed method to the ADNI gene expression data and the IGAP GWAS summary data identifies 18 causal genes associated with Alzheimer's disease, including APOE and TOMM40, in addition to 7 other genes missed by two-stage least squares considering only linear relationships. Our findings suggest that nonlinear modeling is required to unleash the power of IV regression for identifying potentially nonlinear gene-trait associations. Accompanying this paper is our Python library nl-causal that implements the proposed method.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Xiang Li</div>
            <div class="institute">Beijing Yuanling Technology</div>
            <div class="title">Title: 图像生成大模型微调实战</div>
            <div class="abstract">
                <strong>Abstract:</strong> 本报告聚焦于基于图像生成大模型的开源基座模型（主要是Stable Diffusion）进行各种技术手段低成本微调。例如： Prompt Tuning, Text Inversion, Hypernetworks, LoRA 等等手段。以及在图像编辑上，如何更好的控制生成的手段，如 Control-Net, DragGAN 等手段。报告人重点给出了其在更低成本、更高可控性方向上，微调图像大模型的实践经验。
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