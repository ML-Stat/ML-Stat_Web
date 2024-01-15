---
title: "Trustworthy Machine Learning"
summary: "3:30 p.m. — 5:00 p.m., Friday, Aug. 25, 2023"
tags: "s2-1"
weight: 120
---

Friday, Aug. 25, 2023
------


<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/icon/yanjiang.png" />
    Session: <span class="font-bold" style="font-size:120%">Trustworthy Machine Learning</span>
</div>

<div class="tip">
    <img class="icon" src="/icon/shizhong.png" />
    Time: 3:30 p.m. — 5:00 p.m.
</div>
<div class="tip">
    <img class="icon" src="/icon/didian.png" />
    Location: 华东师范大学普陀校区 文史楼201
</div>


<div class="tip">
    <img class="icon" src="/icon/lingdao.png" />
    Session Chair: <a href="http://xiangyuchang.github.io/" target="_blank">Xiangyu Chang, Xi'an Jiaotong University</a>
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
            <div class="name-bar">Xiangyu Chang</div>
            <div class="institute">Xi'an Jiaotong University</div>
            <div class="title">Title: 2D-Shapley: A Framework for Fragmented Data Valuation</div>
            <div class="abstract">
                <strong>Abstract:</strong> Data valuation---quantifying the contribution of individual data sources to certain predictive behaviors of a model---is of great importance to enhancing the transparency of machine learning and designing incentive systems for data sharing. Existing work has focused on evaluatindg data sources with the shared feature or sample space. How to evaluate fragmented data sources of which each only contains partial features and samples remains an open question. We start by presenting a method to calculate the counterfactual of removing a fragment from the aggregated data matrix. Based on the counterfactual calculation, we further propose 2D-Shapley, a theoretical framework for fragmented data valuation that uniquely satisfies some appealing axioms in the fragmented data context. 2D-Shapley empowers a range of new use cases, such as selecting useful data fragments, providing interpretation for sample-wise data values, and fine-grained data issue diagnosis.
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Xiao Guo</div>
            <div class="institute">Northwest University</div>
            <div class="title">Title: Privacy-Preserving Community Detection for Locally Distributed Multiple Networks</div>
            <div class="abstract">
                <strong>Abstract:</strong> Modern network analysis often involves multi-layer network data in which the nodes are aligned, but the edges on different layers come from various sources (e.g., hospitals, companies, and banks). The multi-layer stochastic block model (SBM) has been popularly used for analyzing this type of network data. In the literature, different estimation and clustering methods have been proposed for multi-layer SBMs based on the assumption that the networks are collected and preserved centrally. However, in practice, the networks are commonly stored and analyzed in a local and distributed fashion because of the privacy, ownership, and communication costs. This paper proposes a new method for consensus community detection and estimation in a multi-layer SBM using locally stored network data with privacy protection and local computational constraints. A novel algorithm named privacy-preserving Distributed Spectral Clustering (ppDSC) is developed. To preserve the edges' privacy, we adopt the randomized response (RR) mechanism to perturb the network edges, which satisfies the strong notion of differential privacy. The ppDSC algorithm is performed on the squared RR-perturbed adjacency matrices to prevent possible cancellation of communities among different layers. To remove the bias incurred by RR and the squared network matrices, we develop a two-step bias-adjustment procedure. Then we perform eigen-decomposition on the debiased matrices, aggregation of the local eigenvectors with weights computed by orthogonal Procrustes transformation (OPT), and k-means clustering. We provide theoretical analysis on the statistical errors of ppDSC in terms of eigen-vector estimation and clustering and show that under mild conditions, the errors from the privacy protection and the local computation are asymptotically negligible. In addition, the blessings and curses of network heterogeneity are well-explained by our bounds. Numerical and real data experiments support our theoretical findings. 
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Haishan Ye</div>
            <div class="institute">Xi'an Jiaotong University</div>
            <div class="title">Title: Eigencurve: Optimal Learning Rate Schedule for SGD on Quadratic Objectives with Skewed Hessian Spectrums</div>
            <div class="abstract">
                <strong>Abstract:</strong> Learning rate schedulers have been widely adopted in training deep neural networks. Despite their practical importance, there is a discrepancy between its practice and its theoretical analysis. For instance, it is not known what schedules of SGD achieve best convergence, even for simple problems such as optimizing quadratic objectives. In this paper, we propose Eigencurve, the first family of learning rate schedules that can achieve minimax optimal convergence rates (up to a constant) for SGD on quadratic objectives when the eigenvalue distribution of the underlying Hessian matrix is skewed. The condition is quite common in practice. Experimental results show that Eigencurve can significantly outperform step decay in image classification tasks on CIFAR-10, especially when the number of epochs is small. Moreover, the theory inspires two simple learning rate schedulers for practical applications that can approximate eigencurve. For some problems, the optimal shape of the proposed schedulers resembles that of cosine decay, which sheds light to the success of cosine decay for such situations. For other situations, the proposed schedulers are superior to cosine decay. 
            </div>
        </div>
    </div>
    <div class="row">
        <div class="container">
            <div class="name-bar">Pengfei Liu</div>
            <div class="institute">Shanghai Jiao Tong University</div>
            <div class="title">Title: 生成式人工智能模型的安全可靠的讨论</div>
            <div class="abstract">
                <strong>Abstract:</strong> 以自然语言处理中预训练语言模型为核心的生成式人工智能已经逐渐从学术论文走入到产品，例如Jasper、ChatGPT等，并且其在应用层的潜力还在不断被人挖掘。生成式人工智能（AI）使复杂应用的开发成为可能，这些应用以预先训练好的大型模型为骨架，通过适当的引导就可以生成高质量的文本、图像和其他输出。然而，评估这些生成系统（例如评估ChatGPT生成文本的质量）是一个可能比生成本身更艰巨的任务，生成模型的结果往往难以控制，比如生成有攻击性、有偏见、事实错误的内容，如何自动地从多方面定量评估模型的可靠性成为一个关键的问题。本报告将会讨论如何评估并建立一个安全可靠的大模型。
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
