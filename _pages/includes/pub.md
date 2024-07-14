## Autonomous Driving

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/IJCAI_2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SGDCL: Semantic-Guided Dynamic Correlation Learning for Explainable Autonomous Driving [**Project**](https://github.com/ChengtaiCao/SGDCL)  
**Chengtai Cao**, Xinhong Chen, Jianping Wang, Qun Song, Rui Tan, and Yung-Hui Li

- This work introduces SGDCL, a novel approach for explainable autonomous driving. SGDCL addresses critical shortcomings of existing methods via a semantic-guided learning module and a dynamic correlation learning module to learn category-specific features and model their interplay. Furthermore, we propose a novel loss item that leverages fine-grained co-occurrence statistics to regularize model training. Our comprehensive evaluation of two benchmarks demonstrates its effectiveness, surpassing seven state-of-the-art baselines and a large vision-language model. SGDCL improves prediction performance by a large margin and offers interpretable attention scores, enhancing the explainability and transparency of autonomous driving systems. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/AAAI_2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CCTR: Calibrating Trajectory Prediction for Uncertainty-Aware Motion Planning in Autonomous Driving](https://ojs.aaai.org/index.php/AAAI/article/view/30085) <strong><span class='show_paper_citations' data='BbsnLQYAAAAJ:_FxGoFyzp5QC'></span></strong>  
**Chengtai Cao**, Xinhong Chen, Jianping Wang, Qun Song, Rui Tan, and Yung-Hui Li

- This paper presents a novel CCTR framework to address the challenge of proper uncertainty calibration in trajectory prediction models, improving their reliability. CCTR offers a solution by introducing a calibration-oriented regularizer to align predicted variances with ground truth divergence and generating tailor-made temperature scalers for each prediction based on context and historical information. Extensive experiments demonstrate the superiority of CCTR over various baselines in uncertainty estimation and downstream planning tasks, leading to better-calibrated predictions and more trustworthy planning. Moreover, the ablation studies show the effectiveness of each component, with in-depth empirical analysis verifying CCTR's desirable properties. Future work can exploit more advanced post-processing modules to further improve calibration quality. 
</div>
</div>

# Continual Learning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/AAAI_2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Overcoming Catastrophic Forgetting in Graph Neural Networks with Experience Replay](https://ojs.aaai.org/index.php/AAAI/article/view/16602) <strong><span class='show_paper_citations' data='BbsnLQYAAAAJ:2osOgNQ5qMEC'></span></strong>  
Fan Zhou and **Chengtai Cao\*** (\* Corresponding Author)

- In this paper, we propose a dedicated continual learning method for graph neural networks, which is to our best
knowledge the first attempt along this line. Specifically, we design a topology-aware weight preserving module which explicitly captures the topological information of graphs and measures the importance of the network’s parameters based on the task-related loss function and the topological information. When learning a new task, changes to the important parameters will be penalized to remember old tasks. Moreover, the proposed approach can be readily extended to arbitrary GNNs. The extensive experiments on both node-level tasks and graph-level one demonstrates the effectiveness and applicability of the proposed continual learning method on the graph domain.
</div>
</div>

# Meta-Learning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2019</div><img src='images/CIKM_2019.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Meta-GNN: on Few-shot Node Classification in Graph Meta-Learning](https://dl.acm.org/doi/abs/10.1145/3357384.3358106) <strong><span class='show_paper_citations' data='BbsnLQYAAAAJ:u5HHmVD_uO8C'></span></strong>  [**Project**](https://github.com/ChengtaiCao/Meta-GNN)  
Fan Zhou, **Chengtai Cao**, Kunpeng Zhang, Goce Trajcevski, Ting Zhong, and Ji Geng

- We have presented a generic graph meta-learning framework for few-shot node classification that leverages meta-learning mechanism to learn better parameter initialization of GNNs. The proposed Meta-GNN model can adapt well to new learning tasks (even new classes) with few labeled samples and significantly improves the performance in the context of few-shot node classification under meta-learning paradigm. Encouraging results have been obtained on three widely used datasets. In our future work, we would like to extend our framework to address more challenging problems such as few-shot graph classification and zero-shot node classification.
</div>
</div>


- `IJCAI 2024` SGDCL: Semantic-Guided Dynamic Correlation Learning for Explainable Autonomous Driving. **Chengtai Cao**, Xinhong Chen, Jianping Wang, Qun Song, Rui Tan, and Yung-Hui Li
- `AAAI 2024` [CCTR: Calibrating Trajectory Prediction for Uncertainty-Aware Motion Planning in Autonomous Driving](https://ojs.aaai.org/index.php/AAAI/article/view/30085). **Chengtai Cao**, Xinhong Chen, Jianping Wang, Qun Song, Rui Tan, and Yung-Hui Li
- `AAAI 2021` [Overcoming Catastrophic Forgetting in Graph Neural Networks with Experience Replay](https://ojs.aaai.org/index.php/AAAI/article/view/16602). Fan Zhou and **Chengtai Cao\*** (\* Corresponding Author)
- `CIKM 2019` [Meta-GNN: on Few-shot Node Classification in Graph Meta-Learning](https://dl.acm.org/doi/abs/10.1145/3357384.3358106). Fan Zhou, **Chengtai Cao**, Kunpeng Zhang, Goce Trajcevski, Ting Zhong, and Ji Geng.