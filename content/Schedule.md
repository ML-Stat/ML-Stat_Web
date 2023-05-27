---
title: Schedule
weight: 40
---



Friday, Aug 25, 2023
------

<hr style="border: 0; border-top: 5px solid;">

<div class="tip">
    <img class="icon" src="/images/shizhong.png" />
    <u>Time</u>: 1:30 pm — 2:30 pm 
</div>
<div class="tip">
    <img class="icon" src="/images/didian.png" />
    <u>location</u>: Room 101
</div>

<div class="tip">
    <img class="icon" src="/images/yanjiang.png" />
    <u>Session</u>: <span class="font-bold" style="font-size:120%">Trustworthy Machine Learning</span>
</div>

<div class="tip">
    <img class="icon" src="/images/lingdao.png" />
    <u>Session Chair</u>: <a href="http://xiangyuchang.github.io/" target="_blank">Xiangyu Chang</a>
</div>


________________________________________

<div class="row">
    <div class="left">
        <img src="/images/xiangyu.png" class="avatar" />
        <div class="font-small font-bold">
            <a href="http://xiangyuchang.github.io/" target="_blank">
                Xiangyu Chang
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            2D-Shapley: A Framework for Fragmented Data Valuation
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            Data valuation---quantifying the contribution of individual data sources to certain predictive behaviors of a model---is of great importance to enhancing the transparency of machine learning and designing incentive systems for data sharing. Existing work has focused on evaluatindg data sources with the shared feature or sample space. How to evaluate fragmented data sources of which each only contains partial features and samples remains an open question. We start by presenting a method to calculate the counterfactual of removing a fragment from the aggregated data matrix. Based on the counterfactual calculation, we further propose 2D-Shapley, a theoretical framework for fragmented data valuation that uniquely satisfies some appealing axioms in the fragmented data context. 2D-Shapley empowers a range of new use cases, such as selecting useful data fragments, providing interpretation for sample-wise data values, and fine-grained data issue diagnosis.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/person.jpeg" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Haishan Ye
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Eigencurve: Optimal Learning Rate Schedule for SGD on Quadratic Objectives with Skewed Hessian Spectrums
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            Learning rate schedulers have been widely adopted in training deep neural networks. Despite their practical importance, there is a discrepancy between its practice and its theoretical analysis. For instance, it is not known what schedules of SGD achieve best convergence, even for simple problems such as optimizing quadratic objectives. In this paper, we propose Eigencurve, the first family of learning rate schedules that can achieve minimax optimal convergence rates (up to a constant) for SGD on quadratic objectives when the eigenvalue distribution of the underlying Hessian matrix is skewed. The condition is quite common in practice. Experimental results show that Eigencurve can significantly outperform step decay in image classification tasks on CIFAR-10, especially when the number of epochs is small. Moreover, the theory inspires two simple learning rate schedulers for practical applications that can approximate eigencurve. For some problems, the optimal shape of the proposed schedulers resembles that of cosine decay, which sheds light to the success of cosine decay for such situations. For other situations, the proposed schedulers are superior to cosine decay.
        </div>
    </div>
</div>

<div class="row">
    <div class="left">
        <img src="/images/person.jpeg" class="avatar" />
        <div class="font-small font-bold">
            <a>
                Xiao Guuo
            </a>
        </div>
    </div>
    <div class="right">
        <div class="font-small">
            <u>Title:</u> &nbsp;
            Privacy-Preserving Community Detection for Locally Distributed Multiple Networks
        </div>
        <div class="content font-small">
            <u>Abstract:</u> &nbsp;
            Modern network analysis often involves multi-layer network data in which the nodes are aligned, but the edges on different layers come from various sources  (e.g., hospitals, companies, and banks). The multi-layer stochastic block model (SBM) has been popularly used for analyzing this type of network data. In the literature, different estimation and clustering methods have been proposed for multi-layer SBMs based on the assumption that the networks are collected and preserved centrally. However, in practice, the networks are commonly stored and analyzed in a local and distributed fashion because of the privacy, ownership, and communication costs. This paper proposes a new method for consensus community detection and estimation in a multi-layer SBM using locally stored network data with privacy protection and local computational constraints. A novel algorithm named privacy-preserving Distributed Spectral Clustering (ppDSC) is developed. To preserve the edges' privacy, we adopt the randomized response (RR) mechanism to perturb the network edges, which satisfies the strong notion of differential privacy. The ppDSC algorithm is performed on the squared RR-perturbed adjacency matrices to prevent possible cancellation of communities among different layers. To remove the bias incurred by RR and the squared network matrices, we develop a two-step bias-adjustment procedure. Then we perform eigen-decomposition on the debiased matrices, aggregation of the local eigenvectors with weights computed by orthogonal Procrustes transformation (OPT), and k-means clustering. We provide theoretical analysis on the statistical errors of ppDSC in terms of eigen-vector estimation and clustering and show that under mild conditions, the errors from the privacy protection and the local computation are asymptotically negligible. In addition, the blessings and curses of network heterogeneity are well-explained by our bounds. Numerical and real data experiments support our theoretical findings.    
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
    font-size: 12px;
}

.font-bold {
    font-weight: bold;
}
</style>
