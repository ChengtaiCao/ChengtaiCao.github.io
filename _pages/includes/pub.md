## Autonomous Driving

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/IJCAI_2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SGDCL: Semantic-Guided Dynamic Correlation Learning for Explainable Autonomous Driving](https://www.ijcai.org/proceedings/2024/66) [**[Project]**](https://github.com/ChengtaiCao/SGDCL)  
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

## Continual Learning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/AAAI_2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Overcoming Catastrophic Forgetting in Graph Neural Networks with Experience Replay](https://ojs.aaai.org/index.php/AAAI/article/view/16602) <strong><span class='show_paper_citations' data='BbsnLQYAAAAJ:2osOgNQ5qMEC'></span></strong>  
Fan Zhou and **Chengtai Cao\*** (Corresponding Author)

- In this paper, we propose a dedicated continual learning method for graph neural networks, which is to our best
knowledge the first attempt along this line. Specifically, we design a topology-aware weight preserving module which explicitly captures the topological information of graphs and measures the importance of the network’s parameters based on the task-related loss function and the topological information. When learning a new task, changes to the important parameters will be penalized to remember old tasks. Moreover, the proposed approach can be readily extended to arbitrary GNNs. The extensive experiments on both node-level tasks and graph-level one demonstrates the effectiveness and applicability of the proposed continual learning method on the graph domain.
</div>
</div>

## Meta-Learning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INFOCOM 2020</div><img src='images/INFOCOM_2020.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fast Network Alignment via Graph Meta-learning](https://ieeexplore.ieee.org/abstract/document/9155456) <strong><span class='show_paper_citations' data='BbsnLQYAAAAJ:u-x6o8ySG0sC'></span></strong>  
Fan Zhou, **Chengtai Cao**, Goce Trajcevski, Kunpeng Zhang, Ting Zhong, and Ji Geng.

- In this paper, we recast the network alignment (NA) problem as a one-shot classification problem and presented an effective and efficient meta-learning based model for addressing this task, providing a new perspective. The proposed Meta-NA is a flexible and general framework that can significantly improve the NA accuracy and reduce the computational overheads. As our future work, one immediate extension is to incorporate the auxiliary information for more accurate network alignment. In addition, leveraging Meta-NA we plan to tackle another interesting topic – the network alignment without structural information – e.g., linking the anchor nodes across locationbased social networks with only the footprints of users available.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2019</div><img src='images/CIKM_2019.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Meta-GNN: on Few-shot Node Classification in Graph Meta-Learning](https://dl.acm.org/doi/abs/10.1145/3357384.3358106) <strong><span class='show_paper_citations' data='BbsnLQYAAAAJ:u5HHmVD_uO8C'></span></strong>  [**[Project]**](https://github.com/ChengtaiCao/Meta-GNN)  
Fan Zhou, **Chengtai Cao**, Kunpeng Zhang, Goce Trajcevski, Ting Zhong, and Ji Geng

- We have presented a generic graph meta-learning framework for few-shot node classification that leverages meta-learning mechanism to learn better parameter initialization of GNNs. The proposed Meta-GNN model can adapt well to new learning tasks (even new classes) with few labeled samples and significantly improves the performance in the context of few-shot node classification under meta-learning paradigm. Encouraging results have been obtained on three widely used datasets. In our future work, we would like to extend our framework to address more challenging problems such as few-shot graph classification and zero-shot node classification.
</div>
</div>


## Graph Neural Network
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICC 2024</div><img src='images/ICC_2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Trajectory-User Linking via Graph Neural Network](https://ieeexplore.ieee.org/abstract/document/9500836) <strong><span class='show_paper_citations' data='BbsnLQYAAAAJ:qjMakFHDy7sC'></span></strong>  
Fan Zhou, Shupei Chen, Jin Wu, **Chengtai Cao**, and Shengming Zhang

- This paper presented a general graph construction method to generate a check-in graph from massive trajectory data while modeling geographical features associated with users’ checkins and temporal moving intentions. We also proposed an effective and efficient model GNNTUL to address the human mobility discrimination problem by utilizing graph neural networks to capture higher-order spatio-temporal information, as well as the implicit transition patterns between check-ins from the constructed graph. Extensive experiments have been conducted on real-world LBSN data, and the results prove that our method can successfully enhance TUL performance and improve mobility learning efficiency.
</div>
</div>

## Thesis
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Master Thesis</div><img src='images/Thesis_2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Application of Graph Neural Network Base on Meta-learning (基于元学习的图神经网络应用研究)](https://www.cnki.net/KCMS/detail/detail.aspx?dbcode=CMFD&dbname=CMFD202201&filename=1021748039.nh&uniplatform=OVERSEA&v=IOm4_go2JbG-GNi8-6GuC3ojIq6MirrxrsNc1rpnfKBFRkaFM-K-aTiPvlKkOh41)  
**Chengtai Cao**

- With the advancement of machine learning and deep learning, graph structure data learning has gained significant attention from researchers. Graph data is prevalent in applications like social networks, citation networks, and biomolecules, leading to various graph learning models such as graph convolutional neural networks. However, existing methods face challenges: poor generalization, difficulty learning from few samples, inability to learn to learn, and low model efficiency. To address these issues, this research proposes two methods: Meta-GNN and Meta-NA. Meta-GNN focuses on few-shot node classification, using meta-learning to achieve good model initialization. Meta-NA approaches network alignment as a few-shot inter-network node classification problem, mapping nodes from multiple graphs into a shared metric space. Experimental results on real-world benchmarks demonstrate that both proposed methods outperform existing baselines in their respective applications.

</div>
</div>

## Others
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA 2021</div><img src='images/ESWA_2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Meta-Knowledge for Few-shot Image Emotion Recognition](https://www.sciencedirect.com/science/article/abs/pii/S0957417420309830) <strong><span class='show_paper_citations' data='BbsnLQYAAAAJ:9yKSN-GCB0IC'></span></strong>  
Fan, Zhou, **Chengtai Cao**, Ting Zhong, and Ji Geng.

- In this research, we propose a generic meta-learning framework for the few-shot image emotion classification, called Meta-IEC, which provides the capability of well adapting or generalizing to new classes that have not been encountered before, and transferring to a new dataset where labels are completely different and only very few labeled examples are available. To capture the uncertainty and ambiguity during meta-testing, we implement a hierarchical Bayesian graphical model to understand latent relationships among various parameters between meta-training and meta-testing. Extensive experiments conducted on three publicly available datasets show that our proposed model outperforms several state-of-the-art baselines ranging from feature-engineering oriented to deep learning based. In addition, the study also demonstrates the impact of various factors on the model performance, such as the Meta-IEC framework, the network architecture, the hyperparameters, and the choice of labels in meta-training and meta-testing.
</div>
</div>


- ``IJCAI 2024`` [SGDCL: Semantic-Guided Dynamic Correlation Learning for Explainable Autonomous Driving](https://www.ijcai.org/proceedings/2024/66). **Chengtai Cao**, Xinhong Chen, Jianping Wang, Qun Song, Rui Tan, and Yung-Hui Li
- ``AAAI 2024`` [CCTR: Calibrating Trajectory Prediction for Uncertainty-Aware Motion Planning in Autonomous Driving](https://ojs.aaai.org/index.php/AAAI/article/view/30085). **Chengtai Cao**, Xinhong Chen, Jianping Wang, Qun Song, Rui Tan, and Yung-Hui Li
- ``AAAI 2021`` [Overcoming Catastrophic Forgetting in Graph Neural Networks with Experience Replay](https://ojs.aaai.org/index.php/AAAI/article/view/16602). Fan Zhou and **Chengtai Cao\*** (Corresponding Author)
- ``ESWA 2021`` [Learning Meta-Knowledge for Few-shot Image Emotion Recognition](https://www.sciencedirect.com/science/article/abs/pii/S0957417420309830). Fan, Zhou, **Chengtai Cao**, Ting Zhong, and Ji Geng
- ``ICC 2021`` [Trajectory-User Linking via Graph Neural Network](https://ieeexplore.ieee.org/abstract/document/9500836). Fan Zhou, Shupei Chen, Jin Wu, **Chengtai Cao**, and Shengming Zhang
- ``Master Thesis`` [Application of Graph Neural Network Base on Meta-learning (基于元学习的图神经网络应用研究)](https://www.cnki.net/KCMS/detail/detail.aspx?dbcode=CMFD&dbname=CMFD202201&filename=1021748039.nh&uniplatform=OVERSEA&v=IOm4_go2JbG-GNi8-6GuC3ojIq6MirrxrsNc1rpnfKBFRkaFM-K-aTiPvlKkOh41). **Chengtai Cao**
- ``INFOCOM 2020`` [Fast Network Alignment via Graph Meta-learning](https://ieeexplore.ieee.org/abstract/document/9155456). Fan Zhou, **Chengtai Cao**, Goce Trajcevski, Kunpeng Zhang, Ting Zhong, and Ji Geng
- ``CIKM 2019`` [Meta-GNN: on Few-shot Node Classification in Graph Meta-Learning](https://dl.acm.org/doi/abs/10.1145/3357384.3358106). Fan Zhou, **Chengtai Cao**, Kunpeng Zhang, Goce Trajcevski, Ting Zhong, and Ji Geng
  

### Patents
- China Invention Patent, No. CN113095440B: Training Data Generation Method and Causal Effect Heterogeneous Response Difference Estimation Method Based on Meta-Learner (基于元学习者的训练数据生成方法及因果效应异质反应差异估计方法). Fan Zhou, **Chengtai Cao**, Ting Zhong, and Xovee Xu
- China Invention Patent, No. CN112613556B: Few-Shot Image Sentiment Classification Method Based on Meta-Learning (基于元学习的少样本图像情感分类方法). Fan Zhou, **Chengtai Cao**, Ting Zhong, and Tianliang Wang