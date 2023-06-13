# Graph-based Fraud Detection Papers and Resources
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

**Table of Content**
- GNN Papers: [2023](#2023-back-to-top) | [2022](#2022-back-to-top) | [2021](#2021-back-to-top) | [2020](#2020-back-to-top) | [Before 2020](#before-2020-back-to-top)
- [Non-GNN Papers since 2014](#non-gnn-papers-since-2014-back-to-top)
- [Toolbox](#toolbox-back-to-top)
- [Dataset](#dataset-back-to-top)
- [Other Resource](#other-resource-back-to-top)
- [Survey Paper](#survey-paper-back-to-top)




## GNN Papers

### 2023 [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]
| Year   | Title  | Venue |  Paper | Code  |
|-------|--------|--------|--------|-----------|
|2023 | **GAD-NR: Graph Anomaly Detection via Neighborhood Reconstruction** | arXiv 2023 | [Link](https://arxiv.org/pdf/2306.01951.pdf) |  [link](https://github.com/Graph-COM/GAD-NR) | 
| 2023 | **Truncated Affinity Maximization: One-class Homophily Modeling for Graph Anomaly Detection** | arXiv 2023 | [Link](https://arxiv.org/abs/2306.00006) |  [link](https://github.com/mala-lab/TAM-master/) |
| 2023 | **Anti-Money Laundering by Group-Aware Deep Graph Learning** | IEEE TKDE | [Link](https://doi.org/10.1109/TKDE.2023.3272396) | Link |
| 2023 | **Semi-Supervised Credit Card Fraud Detection via Attribute-Driven Graph Representation** | AAAI 2023 | [Link](https://www.xiangshengcloud.top/publication/semi-supervised-credit-card-fraud-detection-via-attribute-driven-graph-representation/Sheng-AAAI2023.pdf) | [link](https://github.com/finint/antifraud) |
| 2023 | **DEDGAT: Dual Embedding of Directed Graph Attention Networks for Detecting Financial Risk**  | arXiv 2023 |  [Link](https://arxiv.org/pdf/2303.03933.pdf) | Link |
| 2023 | **Towards Improved Illicit Node Detection with Positive-Unlabelled Learning**  | IEEE ICBC 2023 |  [Link](https://arxiv.org/pdf/2303.02462.pdf) | Link |
| 2023 | **Counterfactual Graph Learning for Anomaly Detection on Attributed Networks**  | IEEE TKDE |  [Link](https://ieeexplore.ieee.org/abstract/document/10056298) | Link |
| 2023 | **Catch Me If You Can: Semi-supervised Graph Learning for Spotting Money Laundering**  | arXiv 2023 |  [Link](https://arxiv.org/pdf/2302.11880) | [Link](https://github.com/AwesomeDeepAI/Graph-based-money-laundering-detection) |
| 2023 | **Energy-based Out-of-Distribution Detection for Graph Neural Networks**  | ICLR 2023 |  [Link](https://arxiv.org/pdf/2302.02914.pdf) | [Link](https://github.com/qitianwu/GraphOOD-GNNSafe) |
| 2023 | **Attacking Fake News Detectors via Manipulating News Social Engagement**  | TheWebConf 2023 |  [Link](https://arxiv.org/pdf/2302.07363.pdf) | [Link](https://github.com/hwang219/AttackFakeNews) |
| 2023 | **Label Information Enhanced Fraud Detection against Low Homophily in Graphs**  | TheWebConf 2023 |  [Link](https://arxiv.org/pdf/2302.10407.pdf) | [Link](https://github.com/Orion-wyc/GAGA) |
| 2023 | **Addressing Heterophily in Graph Anomaly Detection: A Perspective of Graph Spectrum**  | TheWebConf 2023 |  [Link](https://blacksingular.github.io/papers/www23-GHRN.pdf) | [Link](https://github.com/blacksingular/GHRN) |
| 2023 | **LGM-GNN: A Local and Global Aware Memory-Based Graph Neural Network for Fraud Detection**  | IEEE TBD |  [Link](https://ieeexplore.ieee.org/abstract/document/10008063) | Link |
| 2023 | **Temporal Motifs for Financial Networks: AStudy on Mercari, JPMC, and Venmo Platforms**  | arXiv 2023 |  [Link](https://arxiv.org/pdf/2301.07791.pdf) | Link |
| 2023 | **Evolve Path Tracer: Early Detection of Malicious Addresses in Cryptocurrency**  | arXiv 2023 |  [Link](https://arxiv.org/pdf/2301.05412.pdf) | Link |
| 2023 | **RiskProp: Account Risk Rating on Ethereum via De-anonymous Score and Network Propagation**  | arXiv 2023 |  [Link](https://arxiv.org/pdf/2301.00354.pdf) | Link |
### 2022 [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]
| Year   | Title  | Venue |  Paper | Code  |
|-------|--------|--------|--------|-----------|
| 2022 | **Alleviating Structural Distribution Shift in Graph Anomaly Detection**  | WSDM 2023 |  [Link](https://blacksingular.github.io/papers/wsdm23-GDN.pdf) | [Link](https://github.com/blacksingular/wsdm_GDN) |
| 2022 | **Cross-Domain Graph Anomaly Detection via Anomaly-aware Contrastive Alignment**  | AAAI 2023 |  [Link](https://arxiv.org/pdf/2212.01096.pdf) | [Link](https://github.com/QZ-WANG/ACT) |
| 2022 | **Towards Learning to Discover Money Laundering Sub-network in Massive Transaction Network**  | AAAI 2023 |  [Link](http://yangy.org/works/gnn/AAAI23_Laundering.pdf) | Link |
| 2022 | **Demystifying Bitcoin Address Behavior via Graph Neural Networks**  | ICDE 2023 |  [Link](https://arxiv.org/pdf/2211.14582.pdf) | Link |
| 2022 | **Anomaly Detection in Multiplex Dynamic Networks: from Blockchain Security to Brain Disease Prediction**  | NeurIPS 2022 Workshops |  [Link](https://arxiv.org/pdf/2211.08378.pdf) | Link |
| 2022 | **EvAnGCN: Evolving Graph Deep Neural Network Based Anomaly Detection in Blockchain**  | ADMA 2022 |  [Link](https://link.springer.com/chapter/10.1007/978-3-031-22064-7_32) | Link |
| 2022 | **Dual-discriminative Graph Neural Network for Imbalanced Graph-level Anomaly Detection**  | NeurIPS 2022 |  [Link](https://openreview.net/pdf?id=d6mf9AFoR-O) | [Link](https://github.com/graph-level-anomalies/iGAD) |
| 2022 | **Are we really making much progress in unsupervised graph outlier detection? Revisiting the problem with new insight and superior method**  | arXiv 2022 |  [Link](https://arxiv.org/pdf/2210.12941.pdf) | Link |
| 2022 | **SybilFlyover: Heterogeneous graph-based fake account detection model on social networks**  | Knowledge-Based Systems |  [Link](https://doi.org/10.1016/j.knosys.2022.110038) | Link |
| 2022 | **Guided Self-Training based Semi-Supervised Learning for Fraud Detection**  | ACM ICAIF 2022 |  [Link](https://dl.acm.org/doi/abs/10.1145/3533271.3561783) | Link |
| 2022 | **The Devil is in the Conflict: Disentangled Information Graph Neural Networks for Fraud Detection**  | ICDM 2022 |  [Link](https://arxiv.org/pdf/2210.12384.pdf) | Link |
| 2022 | **GraphBERT: Bridging Graph and Text for Malicious Behavior Detection on Social Media**  | ICDM 2022 |  [Link](https://aragakiyuiii.github.io/data/GraphBERT-%20Bridging%20Graph%20and%20Text%20for%20Malicious%20Behavior%20Detection%20on%20Social%20Media-ICDM22.pdf) | Link |
| 2022 | **DAGAD: Data Augmentation for Graph Anomaly Detection**  | ICDM 2022 |  [Link](https://arxiv.org/pdf/2210.09766.pdf) | [Link](https://github.com/FanzhenLiu/DAGAD) |
| 2022 | **Graph Anomaly Detection with Unsupervised GNNs**  | ICDM 2022 |  [Link](https://arxiv.org/pdf/2210.09535.pdf) | [Link](https://github.com/sawlani/GLAM) |
| 2022 | **A Unified Propagation Forest-based Framework for Fake News Detection**  | COLING 2022 |  [Link](https://aclanthology.org/2022.coling-1.244.pdf) | Link |
| 2022 | **Adversarial Contrastive Learning for Evidence-aware Fake News Detection with Graph Neural Networks**  | arXiv 2022 |  [Link](https://arxiv.org/pdf/2210.05498.pdf) | [Link](https://github.com/CRIPAC-DIG/GETRAL) |
| 2022 | **BOND: Benchmarking Unsupervised Outlier Node Detection on Static Attributed Graphs**  | NeurIPS 2022 |  [Link](https://arxiv.org/pdf/2206.10071.pdf) | [Link](https://github.com/pygod-team/pygod/tree/main/benchmark) |
| 2022 | **DGraph: A Large-Scale Financial Dataset for Graph Anomaly Detection**  | NeurIPS 2022 |  [Link](https://arxiv.org/pdf/2207.03579.pdf) | [Link](https://github.com/DGraphXinye/DGraphFin_baseline) |
| 2022 | **Dual-Augment Graph Neural Network for Fraud Detection**  | CIKM 2022  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3511808.3557586)  | Link |
| 2022 | **Explainable Graph-based Fraud Detection via Neural Meta-graph Search**  | CIKM 2022  |  [Link](https://ponderly.github.io/pub/NGS_CIKM2022.pdf)  | Link |
| 2022 | **Domain-Aware Federated Social Bot Detection with Multi-Relational Graph Neural Networks**  | IJCNN 2022  |  [Link](http://www.liyangyang.com/wp-content/uploads/2022/10/IJCNN22-Bot-YangyangLi.pdf)  | Link |
| 2022 | **GCCAD: Graph Contrastive Coding for Anomaly Detection**  | IEEE TKDE 2022  |  [Link](https://arxiv.org/pdf/2108.07516.pdf)  | [Link](https://github.com/allanchen95/GCCAD) |
| 2022 | **Reinforcement Subgraph Reasoning for Fake News Detection**  | KDD 2022 |  [Link](https://www.microsoft.com/en-us/research/uploads/prod/2022/05/KDD2022_FakeNewsDetection_camera_ready.pdf) | Link |
| 2022 | **ROLAND: Graph Learning Framework for Dynamic Graphs**  | KDD 2022 |  [Link](https://arxiv.org/pdf/2208.07239.pdf) | [Link](https://github.com/snap-stanford/roland) |
| 2022 | **Hierarchical Multi-Modal Fusion on Dynamic Heterogeneous Graph for Health Insurance Fraud Detection**  | IEEE ICME 2022 |  [Link](https://ieeexplore.ieee.org/abstract/document/9859871/) | Link |
| 2022 | **Graph-Aware Deep Fusion Networks for Online Spam Review Detection**  | IEEE TCSS 2022 |  [Link](https://ieeexplore.ieee.org/document/9833456) | Link |
| 2022 | **Modeling User Behavior With Interaction Networks for Spam Detection**  | SIGIR 2022 |  [Link](https://arxiv.org/pdf/2207.10767.pdf) | Link |
| 2022 | **Table2Graph: Transforming Tabular Data to Unified Weighted Graph**  | IJCAI 2022 |  [Link](https://www.ijcai.org/proceedings/2022/0336.pdf) | Link |
| 2022 | **RoSGAS: Adaptive Social Bot Detection with Reinforced Self-Supervised GNN Architecture Search**  | arXiv 2022 |  [Link](https://arxiv.org/pdf/2206.06757.pdf) | Link |
| 2022 | **Rethinking Graph Neural Networks for Anomaly Detection**  | ICML 2022 |  [Link](https://arxiv.org/pdf/2205.15508.pdf) | [Link](https://github.com/squareRoot3/Rethinking-Anomaly-Detection) |
| 2022 | **Can Abnormality be Detected by Graph Neural Networks?**  | IJCAI 2022 |  [Link](http://yangy.org/works/gnn/IJCAI22_Abnormality.pdf) | [Link](https://github.com/zjunet/AMNet) |
| 2022 | **Modelling graph dynamics in fraud detection with "Attention"**  | Preprint |  [Link](https://www.researchgate.net/publication/360164442_Modelling_graph_dynamics_in_fraud_detection_with_Attention) | [Link](https://github.com/DS3Lab/DyHGN) |
| 2022 | **ALLIE: Active Learning on Large-scale Imbalanced Graphs**  | WWW 2022 |  [Link](https://assets.amazon.science/b0/3c/5d25ba6a44a9aeef450083b41e88/allie-active-learning-on-large-scale-imbalanced-graphs.pdf) | Link |
| 2022 | **H2-FDetector: A GNN-based Fraud Detector with Homophilic and Heterophilic Connections**  | WWW 2022 |  [Link](https://dl.acm.org/doi/pdf/10.1145/3485447.3512195) | Link |
| 2022 | **Prohibited Item Detection via Risk Graph Structure Learning**  | WWW 2022 |  [Link](http://shichuan.org/doc/130.pdf) | Link |
| 2022 | **TTAGN:Temporal Transaction Aggregation Graph Network For Ethereum Phishing Scams Detection**  | WWW 2022 |  [Link](https://arxiv.org/pdf/2204.13442.pdf) | Link |
| 2022 | **AUC-oriented Graph Neural Network for Fraud Detection**  | WWW 2022 |  [Link](https://ponderly.github.io/pub/AOGNN_WWW2022.pdf) | Link |
| 2022 | **Bi-Level Selection via Meta Gradient for Graph-based Fraud Detection**  | DASFAA 2022 |  [Link](https://ponderly.github.io/pub/BLS_DASFAA2022.pdf) | Link |
| 2022 | **Nowhere to Hide: Online Rumor Detection Based on Retweeting Graph Neural Networks**  | IEEE TNNLS 2022 |  [Link](https://ieeexplore.ieee.org/abstract/document/9750388) | Link |
| 2022 | **Improved Aggregating and Accelerating Training Methods for Spatial Graph Neural Networks on Fraud Detection**  | arXiv 2022 |  [Link](https://arxiv.org/pdf/2202.06580.pdf) | Link |
| 2022 | **BotSpot++: A Hierarchical Deep Ensemble Model for Bots Install Fraud Detection in Mobile Advertising**  | ACM TOIS 2022 |  [Link](https://dl.acm.org/doi/10.1145/3476107) | [Link](https://github.com/mobvistaresearch/BotSpot-Plus) |
| 2022 | **Inductive Graph Representation Learning for fraud detection**  | Expert Systems with Applications 2022 |  [Link](https://www.sciencedirect.com/science/article/pii/S0957417421017449) | [Link](https://github.com/Charlesvandamme/Inductive-Graph-Representation-Learning-for-Fraud-Detection) |
| 2022 | **Improving Fraud Detection via Hierarchical Attention-based Graph Neural Network**  | arXiv 2022 |  [Link](https://arxiv.org/pdf/2202.06096.pdf) | Link |
| 2022 | **Markov-Driven Graph Convolutional Networksfor Social Spammer Detection**  | IEEE TKDE 2022 |  [Link](https://ieeexplore.ieee.org/abstract/document/9712381) | [Link](https://github.com/dleyan/MDGCN) |
| 2022 | **Deep Graph Learning for Anomalous Citation Detection**  | IEEE TNNLS 2022 |  [Link](https://arxiv.org/pdf/2202.11360.pdf) | Link |
| 2022 | **Towards Fine-Grained Reasoning for Fake News Detection**  | AAAI 2022 |  [Link](https://arxiv.org/pdf/2110.15064.pdf) | [Link](https://github.com/Ahren09/FinerFact) |

### 2021 [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]
| Year   | Title  | Venue |  Paper | Code  |
|-------|--------|--------|--------|-----------|
| 2021 | **eFraudCom: An E-commerce Fraud Detection System via Competitive Graph Neural Networks**  | ACM TOIS 2021 |  [Link](https://www.researchgate.net/publication/353353148_eFraudCom_An_E-commerce_Fraud_Detection_System_via_Competitive_Graph_Neural_Networks) | [Link](https://github.com/GeZhangMQ/eFraudCom) |
| 2021 | **MAFI: GNN-based Multiple Aggregators and Feature Interactions Network for Fraud Detection over Heterogeneous Graph**  | IEEE TBD 2021 |  [Link](https://ieeexplore.ieee.org/abstract/document/9638331) | Link |
| 2021 | **FRAUDRE: Fraud Detection Dual-Resistant to Graph Inconsistency and Imbalance**  | ICDM 2021  |  [Link](https://www.researchgate.net/publication/357512222_FRAUDRE_Fraud_Detection_Dual-Resistant_to_Graph_Inconsistency_and_Imbalance) | [Link](https://github.com/FraudDetection/FRAUDRE) |
| 2021 | **Fake Reviewer Group Detection in Online Review Systems**  | ICDM 2021 Workshop  |  [Link](https://arxiv.org/pdf/2112.06403.pdf) | Link |
| 2021 | **Temporal Graph Representation Learning for Detecting Anomalies in E-payment Systems**  | ICDM 2021 Workshop  |  Link | Link |
| 2021 | **Know-GNN: An Explainable Knowledge-Guided Graph Neural Network for Fraud Detection**  | ICONIP 2021  |  [Link](https://link.springer.com/chapter/10.1007/978-3-030-92307-5_19) | Link |
| 2021 | **TEGDetector: A Phishing Detector that Knows Evolving Transaction Behaviors**  | arXiv 2021  |  [Link](https://arxiv.org/pdf/2111.15446.pdf) | Link |
| 2021 | **Knowledge-Guided Fraud Detection Using Semi-supervised Graph Neural Network**  | WISE 2021  |  [Link](http://link.springer.com/chapter/10.1007/978-3-030-90888-1_29) | Link |
| 2021 | **Deep Fraud Detection on Non-attributed Graph**  | IEEE BigData 2021  |  [Link](https://arxiv.org/pdf/2110.01171.pdf) | Link |
| 2021 | **Distilling Meta Knowledge on Heterogeneous Graph for Illicit Drug Trafficker Detection on Social Media**  | NeurIPS 2021  |  [Link](https://chuxuzhang.github.io/paper/NeurIPS21-MetaHG.pdf) | [Link](https://github.com/Meta-HG/MetaHG) |
|2021  | **ANEMONE: Graph Anomaly Detection with Multi-Scale Contrastive Learning** | CIKM 2021 |[Link](https://shiruipan.github.io/publication/cikm-21-jin/cikm-21-jin.pdf)| [Link](https://github.com/GRAND-Lab/ANEMONE)|
| 2021 | **Prohibited Item Detection on Heterogeneous Risk Graphs**  | CIKM 2021  |  [Link](http://shichuan.org/doc/118.pdf) | Link |
| 2021 | **Modeling Heterogeneous Graph Network on Fraud Detection: A Community-based Framework with Attention Mechanism**  | CIKM 2021  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3459637.3482277) | Link |
| 2021 | **Structural Temporal Graph Neural Networks for Anomaly Detection in Dynamic Graphs**  | CIKM 2021  |  [Link](https://arxiv.org/pdf/2005.07427.pdf)  | Link|
| 2021 | **Action Sequence Augmentation for Early Graph-based Anomaly Detection**  | CIKM 2021  |  [Link](http://nshah.net/publications/ELAND.CIKM.21.pdf)  | [Link](https://github.com/DM2-ND/Eland) |
| 2021 | **Towards Anomaly-resistant Graph Neural Networks via Reinforcement Learning**  | CIKM 2021  |  [Link](http://www.public.asu.edu/~kding9/pdf/CIKM2021_RARE-GNN.pdf)  | Link|
| 2021 | **Hetero-SCAN: Towards Social Context Aware Fake News Detection via Heterogeneous Graph Neural Network**  | arXiv 2021  |  [Link](https://arxiv.org/pdf/2109.08022.pdf)  | Link|
| 2021 | **A Synergistic Approach for Graph Anomaly Detection With Pattern Mining and Feature Learning**  | IEEE TNNLS 2021  |  [Link](https://ieeexplore.ieee.org/abstract/document/9525041)  | [Link](https://github.com/zhao-tong/Graph-Anomaly-Loss) |
| 2021 | **Cross-domain Graph Anomaly Detection**  | IEEE TNNLS 2021  |  [Link](http://www.public.asu.edu/~kding9/pdf/TNNLS_Commander.pdf)  | Link |
| 2021 | **Recurrent Graph Neural Networks for Rumor Detection in Online Forums**  | KDD 2021 Workshop |  [Link](https://arxiv.org/pdf/2108.03548.pdf)  | Link |
| 2021 | **Heterogeneous Temporal Graph Transformer: An Intelligent System for Evolving Android Malware Detection**  | KDD 2021  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3447548.3467168)  | Link |
| 2021 | **Intention-aware Heterogeneous Graph Attention Networks for Fraud Transactions Detection**  | KDD 2021  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3447548.3467142)  | Link |
| 2021 | **Live-Streaming Fraud Detection: A Heterogeneous Graph Neural Network Approach**  | KDD 2021  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3447548.3467065)  | Link |
| 2021 | **Bipartite Dynamic Representations for Abuse Detection**  | KDD 2021  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3447548.3467141)  | [Link](https://github.com/qema/bidyn) |
| 2021 | **Relational Graph Neural Networks for Fraud Detection in a Super-App environment**  | KDD 2021 Workshop  |  [Link](https://arxiv.org/pdf/2107.13673.pdf)  | Link |
| 2021 | **Compare to The Knowledge: Graph Neural Fake News Detection with External Knowledge**  | ACL 2021  |  [Link](https://aclanthology.org/2021.acl-long.62.pdf)  | [Link](https://github.com/BUPT-GAMMA/CompareNet_FakeNewsDetection) |
| 2021 | **Towards Propagation Uncertainty: Edge-enhanced Bayesian Graph Convolutional Networks for Rumor Detection**  | ACL 2021  |  [Link](https://aclanthology.org/2021.acl-long.297.pdf)  | [Link](https://github.com/weilingwei96/EBGCN) |
| 2021 | **Catch me if you can: A participant-level rumor detection framework via fine-grained user representation learning**  | Information Processing & Management 2021  |  [Link](https://www.sciencedirect.com/science/article/pii/S0306457321001643)  | Link |
| 2021 | **Decoupling Representation Learning and Classification for GNN-based Anomaly Detection**  | SIGIR 2021  |  [Link](https://dl.acm.org/doi/10.1145/3404835.3462944)  | [Link](https://github.com/wyl7/DCI-pytorch) |
| 2021 | **Improving fake news detection with domain-adversarial and graph-attention neural network**  | Decision Support Systems  |  [Link](https://www.sciencedirect.com/science/article/pii/S0167923621001433)  | Link |
| 2021 | **Anomaly Detection in Dynamic Graphs via Transformer**  | arXiv 2021  |  [Link](https://arxiv.org/pdf/2106.09876.pdf)  | Link |
| 2021 | **HIN-RNN: A Graph Representation Learning Neural Network for Fraudster Group Detection With No Handcrafted Features**  | arXiv 2021  |  [Link](https://arxiv.org/pdf/2105.11602.pdf)  | Link |
| 2021 | **Fraud Detection in Online Product Review Systems via Heterogeneous Graph Transformer**  | IEEE Access  |  [Link](https://www.researchgate.net/publication/352008651_Fraud_Detection_in_Online_Product_Review_Systems_via_Heterogeneous_Graph_Transformer)  | Link |
| 2021 | **User Preference-aware Fake News Detection**  | SIGIR 2021  |  [Link](https://arxiv.org/pdf/2104.12259.pdf)  | [Link](https://github.com/safe-graph/GNN-FakeNews) |
| 2021 | **Temporal-Aware Graph Neural Network for Credit Risk Prediction**  | SDM 2021  |  [Link](https://epubs.siam.org/doi/pdf/10.1137/1.9781611976700.79)  | Link |
| 2021 | **IFSpard: An Information Fusion-based Framework for Spam Review Detection**  | WWW 2021  |  [Link](https://dl.acm.org/doi/abs/10.1145/3442381.3449920)  | Link |
| 2021 | **Improving Cyberbullying Detection with User Interaction**  | WWW 2021  |  [Link](https://arxiv.org/pdf/2011.00449.pdf)  | [Link](https://github.com/gesy17/TGBully) |
| 2021 | **Pick and Choose: A GNN-based Imbalanced Learning Approach for Fraud Detection**  | WWW 2021  |  [Link](https://ponderly.github.io/pub/PCGNN_WWW2021.pdf)  | [Link](https://github.com/PonderLY/PC-GNN) |
| 2021 | **Credit Risk and Limits Forecasting in E-Commerce Consumer Lending Service via Multi-view-aware Mixture-of-experts Nets**  | WSDM 2021  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3437963.3441743)  | Link |
| 2021 | **DeepIS: Susceptibility Estimation on Social Networks**  | WSDM 2021  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3437963.3441829)  | [Link](https://github.com/xiawenwen49/DeepIS) |
| 2021 | **Few-shot Network Anomaly Detection via Cross-network Meta-learning**  | WWW 2021  |  [Link](https://arxiv.org/pdf/2102.11165v1.pdf)  | [Link](https://github.com/kaize0409/Meta-GDN_AnomalyDetection) |
| 2021 | **Towards Consumer Loan Fraud Detection: Graph Neural Networks with Role-Constrained Conditional Random Field**  | AAAI 2021  |  [Link](https://www.aaai.org/AAAI21Papers/AAAI-6859.XuB.pdf)  | Link |

### 2020 [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]
| Year   | Title  | Venue |  Paper | Code  |
|-------|--------|--------|--------|-----------|
|2020| **Anomaly Detection on Attributed Networks via Contrastive Self-Supervised Learning**| IEEE TNNLS 2020 |[link](https://arxiv.org/abs/2103.00113)|[link](https://github.com/GRAND-Lab/CoLA)|
| 2020 | **Suspicious Massive Registration Detection via Dynamic Heterogeneous Graph Neural Networks**  | AAAI 2021 Workshop  |  [Link](https://arxiv.org/pdf/2012.10831.pdf)  | Link |
| 2020 | **Phishing Scams Detection in Ethereum Transaction Network**  | ACM TOIT 2020 |  [Link](https://dl.acm.org/doi/10.1145/3398071)  | Link |
| 2020 | **APAN: Asynchronous Propagation Attention Network for Real-time Temporal Graph Embedding**  | SIGMOD 2021  |  [Link](https://arxiv.org/pdf/2011.11545.pdf)  | Link |
| 2020 | **Anomaly Detection on Dynamic Bipartite Graph with Burstiness**  | ICDM 2020   |  [Link](https://ieeexplore.ieee.org/document/9338258)  | Link |
| 2020 | **Metagraph Aggregated Heterogeneous Graph Neural Network for Illicit Traded Product Identification in Underground Market**  | ICDM 2020   |  [Link](https://engineering.case.edu/groups/xusheng-xiao/sites/engineering.case.edu.groups.xusheng-xiao/files/docs/metagraph.pdf)  | Link |
| 2020 | **Adversarial Active Learning based Heterogeneous Graph Neural Network for Fake News Detection**  | ICDM 2020   |  [Link](https://arxiv.org/pdf/2101.11206.pdf)  |  [Link](https://www.dropbox.com/sh/bmgz7d1q3tq5429/AAAAcmbgKOp-gtftVWhz533ua?dl=0) |
| 2020 | **Heterogeneous Mini-Graph Neural Network and Its Application to Fraud Invitation Detection**  | ICDM 2020   |  [Link](https://cs.nju.edu.cn/liyf/paper/icdm20-hmgnn.pdf)  |  [Link](https://github.com/iqiyi/HMGNN) |
| 2020 | **xFraud: Explainable Fraud Transaction Detection on Heterogeneous Graphs**  | arXiv 2021 |  [Link](https://arxiv.org/pdf/2011.12193.pdf)  |  Link |
| 2020 | **BotSpot: A Hybrid Learning Framework to Uncover Bot Install Fraud in Mobile Advertising**  | CIKM 2020   |  [Link](https://dl.acm.org/doi/abs/10.1145/3340531.3412690)  |  [Link](https://github.com/mobvistaresearch/CIKM2020-BotSpot) |
| 2020 | **Alike and Unlike: Resolving Class Imbalance Problem in Financial Credit Risk Assessment**  | CIKM 2020   |  [Link](https://ponderly.github.io/pub/ADAAR_CIKM2020.pdf)  |  Link |
| 2020 | **Early Anomaly Detection by Learning and Forecasting Behavior** | arXiv |  [Link](https://arxiv.org/pdf/2010.10016.pdf) | Link |
| 2020 | **ResGCN: Attention-based Deep Residual Modeling for Anomaly Detection on Attributed Networks**  | arXiv 2021  |  [Link](https://arxiv.org/pdf/2009.14738.pdf)  |  Link |
| 2020 | **Multivariate Time-series Anomaly Detection via Graph Attention Network**  | ICDM 2020   |  [Link](https://arxiv.org/pdf/2009.02040.pdf)  |  Link |
| 2020 | **GFD: A Weighted Heterogeneous Graph Embedding Based Approach for Fraud Detection in Mobile Advertising**  | Security and Communication Networks 2020  |  [Link](https://downloads.hindawi.com/journals/scn/2020/8810817.pdf)  |  Link |
| 2020 | **Enhancing Graph Neural Network-based Fraud Detectors against Camouflaged Fraudsters**  | CIKM 2020   |  [Link](https://arxiv.org/pdf/2008.08692.pdf)  |  [Link](https://github.com/YingtongDou/CARE-GNN) |
| 2020 | **Graph-based Modeling of Online Communities for Fake News Detection**  | arXiv 2021  |  [Link](https://arxiv.org/pdf/2008.06274.pdf)  |  [Link](https://github.com/shaanchandra/SAFER) |
| 2020 | **FANG: Leveraging Social Context for Fake News Detection Using Graph Representation**  | CIKM 2020   |  [Link](https://arxiv.org/pdf/2008.07939.pdf)  |  [Link](https://github.com/nguyenvanhoang7398/FANG) |
| 2020 | **Loan Default Analysis with Multiplex Graph Learning**  | CIKM 2020   |  [Link](https://www.researchgate.net/publication/343626706_Loan_Default_Analysis_with_Multiplex_Graph_Learning)  |  Link |
| 2020 | **Error-Bounded Graph Anomaly Loss for GNNs**  | CIKM 2020   |  [Link](http://www.meng-jiang.com/pubs/gal-cikm20/gal-cikm20-paper.pdf)  |  [Link](https://github.com/zhao-tong/Graph-Anomaly-Loss) |
| 2020 | **GCNEXT: graph convolutional network with expanded balance theory for fraudulent user detection**  | Social Network Analysis and Mining 2020    |  [Link](https://link.springer.com/article/10.1007/s13278-020-00697-w)  |  Link |
| 2020 | **FauxWard: a graph neural network approach to fauxtography detection using social media comments**  | Social Network Analysis and Mining 2020   |  [Link](https://link.springer.com/article/10.1007/s13278-020-00689-w)  |  Link |
| 2020 | **A Scalable Framework for Group Fraud Detection in Transaction using Deep Graph Neural Network**  | KDD 2020 Workshop   |  [Link](https://drive.google.com/file/d/14CPo4U9nmRClf_62NhVnhJVG5yhQXzEt/view)   |  Link|
| 2020 | **Early Fraud Detection with Augmented Graph Learning**  | KDD 2020 Workshop   |  [Link](http://www.meng-jiang.com/pubs/earlyfraud-dlg20/earlyfraud-dlg20-paper.pdf)   |  Link|
| 2020 | **TIES: Temporal Interaction Embeddings For Enhancing Social Media Integrity At Facebook**  | KDD 2020   |  [Link](https://arxiv.org/pdf/2002.07917.pdf)   |  Link|
| 2020 | **DETERRENT: Knowledge Guided Graph Attention Network for Detecting Healthcare Misinformation**  | KDD 2020   |  [Link](http://pike.psu.edu/publications/kdd20-deterrent.pdf)   |  [Link](https://github.com/cuilimeng/DETERRENT) |
| 2020 | **Alleviating the Inconsistency Problem of Applying Graph Neural Network to Fraud Detection**  | SIGIR 2020   |  [Link](https://arxiv.org/pdf/2005.00625.pdf)   |  [Link](https://github.com/safe-graph/DGFraud-TF2/tree/main/algorithms/GraphConsis) |
| 2020 | **GCAN: Graph-aware Co-Attention Networks for Explainable Fake News Detection on Social Media**  | ACL 2020   |  [Link](https://www.aclweb.org/anthology/2020.acl-main.48.pdf)   |  [Link](https://github.com/l852888/GCAN) |
| 2020 | **Camouflaged Chinese Spam Content Detection with Semi-supervised Generative Active Learning**  | ACL 2020   |  [Link](https://www.aclweb.org/anthology/2020.acl-main.279.pdf)   |  [Link](https://github.com/Giruvegan/generative-camouflaged-spam-detector) |
| 2020 | **DFraud3-Multi-Component Fraud Detection free of Cold-start**  | arXiv 2021  |  [Link](https://arxiv.org/pdf/2006.05718.pdf)   |  Link |
| 2020 | **Financial Risk Analysis for SMEs with Graph-based Supply Chain Mining**  | IJCAI 2020   |  [Link](https://www.ijcai.org/Proceedings/2020/0643.pdf)   |  Link |
| 2020 | **Rumor Detection on Social Media with Graph Structured Adversarial Learning**  | IJCAI 2020   |  [Link](https://www.ijcai.org/Proceedings/2020/0197.pdf)   |  Link |
| 2020 | **GCN-Based User Representation Learning for Unifying Robust Recommendation and Fraudster Detection**  | SIGIR 2020   |  [Link](https://arxiv.org/pdf/2005.10150.pdf)   |  [Link](https://github.com/zsjdddhr/GraphRfi) |
| 2020 | **ASA: Adversary Situation Awareness via Heterogeneous Graph Convolutional Networks**  | WWW 2020 Workshop   |  [Link](https://dl.acm.org/doi/10.1145/3366424.3391266)   |  Link |
| 2020 | **Graph Convolutional Networks with Markov Random Field Reasoning for Social Spammer Detection**  | AAAI 2020   |  [Link](http://staff.ustc.edu.cn/~liandefu/paper/aaai2020_spammer.pdf)   |  Link |
| 2020 | **Rumor Detection on Social Media with Bi-Directional Graph Convolutional Networks**  | AAAI 2020   |  [Link](https://arxiv.org/abs/2001.06362)   |  [Link](https://github.com/TianBian95/BiGCN) |

### Before 2020 [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]
| Year   | Title  | Venue |  Paper | Code  |
|-------|--------|--------|--------|-----------|
| 2019 | **A Dynamic Default Prediction Framework for Networked-guarantee Loans**  | CIKM 2019  | [Link](https://dl.acm.org/doi/10.1145/3357384.3357804) | Link |
| 2019 | **Spam Review Detection with Graph Convolutional Networks**  | CIKM 2019  | [Link](https://arxiv.org/pdf/1908.10679.pdf) | [Link](https://github.com/safe-graph/DGFraud-TF2/tree/main/algorithms/GAS) |
| 2019 | **A Semi-supervised Graph Attentive Network for Fraud Detection**  | ICDM 2019  |  [Link](https://ieeexplore.ieee.org/document/8970829)   |  [Link](https://github.com/safe-graph/DGFraud-TF2/tree/main/algorithms/SemiGNN) |
| 2019 | **Detect Camouflaged Spam Content via StoneSkipping: Graph and Text Joint Embedding for Chinese Character Variation Representation**  | EMNLP 2019  | [Link](https://www.aclweb.org/anthology/D19-1640.pdf) | [Link](https://github.com/Giruvegan/stoneskipping) |
| 2019 | **Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics**  | KDD 2019 Workshop| [Link](https://arxiv.org/pdf/1908.02591.pdf) | Link |
| 2019 | **Uncovering Insurance Fraud Conspiracy with Network Learning**  | SIGIR 2019 | [Link](https://dl.acm.org/citation.cfm?id=3331184.3331372) | Link |
| 2019 | **Detect Me If You Can: Spam Bot Detection Using Inductive Representation Learning**  | WWW 2019 Workshop| [Link](https://www.researchgate.net/publication/333067454_Detect_Me_If_You_Can_Spam_Bot_Detection_Using_Inductive_Representation_Learning) | Link |
| 2019 | **FdGars: Fraudster Detection via Graph Convolutional Networks in Online App Review System**  | WWW 2019 Workshop| [Link](https://dl.acm.org/citation.cfm?id=3316586) | [Link](https://github.com/safe-graph/DGFraud) |
| 2019 | **GeniePath: Graph Neural Networks with Adaptive Receptive Paths**  | AAAI 2019 | [Link](https://arxiv.org/pdf/1802.00910.pdf) | [Link](https://github.com/safe-graph/DGFraud) |
| 2018 | **Heterogeneous Graph Neural Networks for Malicious Account Detection**  | CIKM 2018 | [Link](https://arxiv.org/pdf/2002.12307.pdf) | [Link](https://github.com/safe-graph/DGFraud-TF2/tree/main/algorithms/GEM) |
| 2018 | **GraphRAD: A Graph-based Risky Account Detection System**  | KDD 2018 Workshop | [Link](https://www.mlgworkshop.org/2018/papers/MLG2018_paper_12.pdf) | Link |
| 2018 | **Selective Graph Attention Networks for Account Takeover Detection**  | ICDM 2018 Workshop | [Link](https://ieeexplore.ieee.org/document/8637408) | Link |

## Non-GNN Papers since 2014 [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]
| Year   | Title  | Venue |  Paper | Code  |
|-------|--------|--------|--------|-----------|
| 2022 | **Spade: A Real-Time Fraud Detection Framework on Evolving Graphs**  | VLDB 2023 |  [Link](https://arxiv.org/pdf/2211.06977.pdf) | Link |
| 2022 | **Temporal burstiness and collaborative camouflage aware fraud detection**  | IPM 2023 |  [Link](https://doi.org/10.1016/j.ipm.2022.103170) | Link |
| 2022 | **AntiBenford Subgraphs: Unsupervised Anomaly Detection in Financial Networks**  | KDD 2022 |  [Link](https://arxiv.org/pdf/2205.13426.pdf) | [Link](https://github.com/tsourakakis-lab/antibenford-subgraphs) |
| 2022 | **Subset Node Anomaly Tracking over Large Dynamic Graphs**  | KDD 2022 |  [Link](https://arxiv.org/pdf/2205.09786.pdf) | [Link](https://github.com/zjlxgxz/DynAnom) |
| 2022 | **Internet Financial Fraud Detection Based on Graph Learning**  | IEEE TCSS 2022 |  [Link](https://ieeexplore.ieee.org/document/9831118) | Link |
| 2022 | **Exploiting Anomalous Structural Nodes in Dynamic Social Networks**  | WWW 2022 Workshop |  [Link](https://dl.acm.org/doi/abs/10.1145/3487553.3524189) | Link |
| 2022 | **Adaptive Label Propagation for Group Anomaly Detection in Large-scale Networks**  | IEEE TKDE 2022 |  [Link](https://ieeexplore.ieee.org/abstract/document/9779570) | Link |
| 2022 | **eRiskCom: an e-commerce risky community detection platform**  | VLDB Journal 2022 |  [Link](https://link.springer.com/article/10.1007/s00778-021-00723-z) | Link |
| 2022 | **Knowledge Sharing via Domain Adaptation in Customs Fraud Detection**  | AAAI 2022  | [Link](https://arxiv.org/abs/2201.06759) | Link |
| 2022 | **Active Learning for Human-in-the-Loop Customs Inspection**  | IEEE TKDE 2022  | [Link](https://ieeexplore.ieee.org/document/9695316) | [Link](https://github.com/Seondong/Customs-Fraud-Detection) |
| 2021 | **Analytical Models for Motifs in Temporal Networks: Discovering Trends and Anomalies**  | arXiv 2021 |  [Link](https://arxiv.org/pdf/2112.14871.pdf) | [Link](https://www.dropbox.com/sh/81tkcf1amemmq2i/AAC2k1vdX2DhsbFQz9LCzovEa?dl=0) |
| 2021 | **Customs Fraud Detection in the Presence of Concept Drift**  | ICDMW 2021 |  [Link](https://arxiv.org/pdf/2109.14155.pdf) | Link |
| 2021 | **Certification and Trade-off of Multiple Fairness Criteria in Graph-based Spam Detection**  | CIKM 2021  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3459637.3482325) | Link |
| 2021 | **Unveiling Fake Accounts at the Time of Registration: An Unsupervised Approach**  | KDD 2021  |  [Link](https://dl.acm.org/doi/pdf/10.1145/3447548.3467094)  | Link |
| 2021 | **Mining Fraudsters and Fraudulent Strategies in Large-Scale Mobile Social Networks**  |IEEE TKDE 2021 |  [Link](http://yangy.org/works/telecom_fraud/TKDE_Fraud_Yang.pdf)  | Link |
| 2021 | **GuiltyWalker: Distance to illicit nodes in the Bitcoin network**  | KDD 2021 Workshop |  [Link](https://arxiv.org/pdf/2102.05373.pdf)  | Link |
| 2021 | **Deep Entity Classification: Abusive Account Detection for Online Social Networks**  | USENIX Security 2021  |  [Link](https://www.usenix.org/system/files/sec21summer_xu.pdf)   |  Link |
| 2021 | **EnsemFDet: An Ensemble Approach to Fraud Detection based on Bipartite Graph**  | ICDE 2021  |  [Link](https://arxiv.org/pdf/1912.11113.pdf)   |  Link |
| 2021 | **Network Inference from a Mixture of Diffusion Models for Fake News Mitigation**  | ICWSM 2021  | [Link](https://arxiv.org/pdf/2008.03450.pdf) | Link |
| 2021 | **Uncovering Coordinated Networks on Social Media**  | ICWSM 2021  | [Link](https://arxiv.org/pdf/2001.05658.pdf) | Link |
| 2021 | **F-FADE: Frequency Factorization for Anomaly Detection in Edge Streams**  | WSDM 2021  | [Link](https://arxiv.org/pdf/2011.04723.pdf) | [Link](https://github.com/snap-stanford/F-FADE) |
| 2020 | **Subgraph Anomaly Detection in Financial Transaction Networks**  | ICAIF 2020  | [Link](https://dl.acm.org/doi/pdf/10.1145/3383455.3422548) | Link |
| 2020 | **AUTOAUDIT: Mining Accounting and Time-Evolving Graphs**  | IEEE BigData 2020  | [Link](https://arxiv.org/pdf/2011.00447.pdf) | [Link](https://github.com/mengchillee/AutoAudit) |
| 2020 | **SpecGreedy: Unified Dense Subgraph Detection**  | ECML-PKDD 2020  | [Link](https://shenghua-liu.github.io/papers/pkdd2020_specgreedy.pdf) | [Link](https://github.com/wenchieh/specgreedy) |
| 2020 | **Real-Time Streaming Anomaly Detection in Dynamic Graphs**  | arXiv 2020  |  [Link](https://arxiv.org/pdf/2009.08452.pdf)  |  [Link](https://github.com/Stream-AD/MIDAS) |
| 2020 | **Robust Spammer Detection by Nash Reinforcement Learning**  | KDD 2020  | [Link](https://arxiv.org/pdf/2006.06069.pdf) | [Link](https://github.com/YingtongDou/Nash-Detect) |
| 2020 | **DATE: Dual Attentive Tree-aware Embedding for Customs Fraud Detection**  | KDD 2020  | [Link](https://dl.acm.org/doi/pdf/10.1145/3394486.3403339) | [Link](https://github.com/Roytsai27/Dual-Attentive-Tree-aware-Embedding) |
| 2020 | **KNH: Multi-View Modeling with K-Nearest Hyperplanes Graph for Misinformation Detection**  | KDD 2020 Workshop  | [Link](https://drive.google.com/file/d/1BBNtSQeayy7ozonQbsbXmMdtEKDF4DLi/view) | Link |
| 2020 | **Representing Fine-Grained Co-Occurrences for Behavior-Based Fraud Detection in Online Payment Services**  | IEEE TDSC 2020   |  [Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9085905)   |  Link |
| 2020 | **Collaboration Based Multi-Label Propagation for Fraud Detection**  | IJCAI 2020  | [Link](https://www.ijcai.org/Proceedings/2020/0343.pdf) | Link |
| 2020 | **Hierarchical Propagation Networks for Fake News Detection: Investigation and Exploitation**  | ICWSM 2020  | [Link](https://arxiv.org/pdf/1903.09196.pdf) | [Link](https://www.dropbox.com/sh/v1nmsdabk4wumcn/AADiRakrTIxx546qaOMNHPTWa?dl=0) |
| 2020 | **Friend or Faux: Graph-Based Early Detection of Fake Accounts on Social Networks**  | WWW 2020  |  [Link](https://arxiv.org/pdf/2004.04834.pdf)   |  Link |
| 2020 | **Financial Defaulter Detection on Online Credit Payment via Multi-view Attributed Heterogeneous Information Network**  | WWW 2020   |  [Link](https://dl.acm.org/doi/abs/10.1145/3366423.3380159)   |  Link |
| 2020 | **MIDAS: Microcluster-Based Detector of Anomalies in Edge Streams**  | AAAI 2020   |  [Link](https://arxiv.org/pdf/1911.04464.pdf)   |  [Link](https://github.com/Stream-AD/MIDAS) |
| 2020 | **FlowScope: Spotting Money Laundering Based on Graphs**  | AAAI 2020  |  [Link](http://shichuan.org/doc/78.pdf)   |  [Link](https://github.com/aplaceof/FlowScope) |
| 2019 | **A Dynamic Default Prediction Framework for Networked-guarantee Loans**  | CIKM 2019  |  [Link](https://dl.acm.org/doi/10.1145/3357384.3357804)   |  Link |
| 2019 | **Understanding Default Behavior in Online Lending**  | CIKM 2019  |  [Link](http://yangy.org/works/loan_fraud/cikm19_loan.pdf)   |  Link |
| 2019 | **SliceNDice: Mining Suspicious Multi-attribute Entity Groups with Multi-view Graphs**  | DSAA 2019  |  [Link](https://arxiv.org/pdf/1908.07087.pdf)   |  [Link](https://github.com/hamedn/SliceNDice) |
| 2019 | **From Anomaly Detection to Rumour Detection using Data Streams of Social Platforms**  | VLDB 2019  |  [Link](http://www.vldb.org/pvldb/vol12/p1016-nguyen.pdf)   |  Link |
| 2019 | **TitAnt: Online Real-time Transaction Fraud Detection in Ant Financial**  | VLDB 2019  |  [Link](https://arxiv.org/pdf/1906.07407.pdf)   |  Link |
| 2019 | **Mining Fraudsters and Fraudulent Strategies in Large-Scale Mobile Social Networks**  | IEEE TKDE |  [Link](https://keg.cs.tsinghua.edu.cn/yuxiao/papers/TKDE19-yang-fraud-detection.pdf)   |  Link |
| 2019 | **Fraud Detection in Dynamic Interaction Network**  | IEEE TKDE |  [Link](https://ieeexplore.ieee.org/document/8695738)   |  Link |
| 2019 | **Spotting Collective Behaviour of Online Frauds in Customer Reviews**  | IJCAI 2019  |  [Link](https://www.ijcai.org/proceedings/2019/0035.pdf)   |  [Link](https://github.com/LCS2-IIITD/DeFrauder) |
| 2019 | **Cash-Out User Detection Based on Attributed Heterogeneous Information Network with a Hierarchical Attention Mechanism**  | AAAI 2019 | [Link](https://aaai.org/ojs/index.php/AAAI/article/view/3884) | [Link](https://github.com/safe-graph/DGFraud) |
| 2018 | **Deep Structure Learning for Fraud Detection**  | ICDM 2018  | [Link](https://www.researchgate.net/publication/330030140_Deep_Structure_Learning_for_Fraud_Detection) | [Link](https://github.com/zhao-tong/DeepFD-pyTorch) |
| 2018 | **FeatNet: Large-scale Fraud Device Detection by Network Representation Learning with Rich Features**  | AiSec 2018 | [Link](https://surrealyz.github.io/files/pubs/featnet-aisec2018.pdf) | Link |
| 2018 | **HGsuspector: Scalable Collective Fraud Detection in Heterogeneous Graphs**  | KDD 2018 Workshop | [Link](https://www.mlgworkshop.org/2018/papers/MLG2018_paper_16.pdf) | Link |
| 2018 | **Online E-Commerce Fraud: A Large-scale Detection and Analysis**  | ICDE 2018 | [Link](https://nesa.zju.edu.cn/download/Online%20E-Commerce%20Fraud%20A%20Large-scale%20Detection%20and%20Analysis.pdf) | [Link](https://github.com/maianhpuco/alibabaFraud) |
| 2018 | **FraudNE: a Joint Embedding Approach for Fraud Detection**  | IJCNN 2018 | [Link](https://opus.cloud.lib.uts.edu.au/bitstream/10453/133230/4/08489585.pdf) | Link |
| 2018 | **Combating Crowdsourced Review Manipulators: A Neighborhood-Based Approach**  | WSDM 2018  | [Link](http://faculty.cse.tamu.edu/caverlee/pubs/parisa18wsdm.pdf) | Link |
| 2018 | **REV2: Fraudulent User Prediction in Rating Platforms**  | WSDM 2018 | [Link](https://cs.stanford.edu/~srijan/pubs/rev2-wsdm18.pdf) | [Link](https://cs.stanford.edu/~srijan/rev2/) |
| 2017 | **ZooBP: Belief Propagation for Heterogeneous Networks**  | VLDB 2017 | [Link](http://www.vldb.org/pvldb/vol10/p625-eswaran.pdf) | [Link](https://github.com/safe-graph/UGFraud) |
| 2017 | **HitFraud: A Broad Learning Approach for Collective Fraud Detection in Heterogeneous Information Networks**  | ICDM 2017 | [Link](https://arxiv.org/pdf/1709.04129.pdf) | Link |
| 2017 | **GANG: Detecting Fraudulent Users in Online Social Networks via Guilt-by-Association on Directed Graph**  | ICDM 2017 | [Link](https://ieeexplore.ieee.org/document/8215519) | [Link](https://github.com/safe-graph/UGFraud) |
| 2017 | **The Many Faces of Link Fraud**  | ICDM 2017 | [Link](https://arxiv.org/pdf/1704.01420.pdf) | Link |
| 2017 | **HoloScope: Topology-and-Spike Aware Fraud Detection**  | CIKM 2017 | [Link](https://arxiv.org/pdf/1705.02505.pdf) | [Link](https://github.com/shenghua-liu/HoloScope) |
| 2017 | **iBGP: A Bipartite Graph Propagation Approach for Mobile Advertising Fraud Detection**  | Mobile Information Systems 2017 | [Link](https://downloads.hindawi.com/journals/misy/2017/6412521.pdf) | Link |
| 2017 | **Adaptive Spammer Detection with Sparse Group Modeling**  | ICWSM 2017 | [Link](http://www.liangwu.me/files/papers/ICWSM17_Liang%20Wu_Adaptive%20Spammer%20Detection.pdf) | Link |
| 2017 | **NetSpam: A Network-Based Spam Detection Framework for Reviews in Online Social Media**  | IEEE TIFS 2017 | [Link](https://www.researchgate.net/publication/314160993_NetSpam_A_Network-Based_Spam_Detection_Framework_for_Reviews_in_Online_Social_Media) | Link |
| 2016 | **FRAUDAR: Bounding Graph Fraud in the Face of Camouflage**  | KDD 2016  | [Link](https://bhooi.github.io/papers/fraudar_kdd16.pdf) | [Link](https://github.com/safe-graph/UGFraud) |
| 2015 | **AFRAID: Fraud detection via active inference in time-evolving social networks**  | ASONAM 2015 | [Link](http://www.andrew.cmu.edu/user/lakoglu/pubs/15-ASONAM-ActiveInferenceforFraud.pdf) | Link |
| 2015 | **Collective Opinion Spam Detection: Bridging Review Networks and Metadata**  | KDD 2015 | [Link](https://www.andrew.cmu.edu/user/lakoglu/pubs/15-kdd-collectiveopinionspam.pdf) | [Link](https://github.com/safe-graph/UGFraud) |
| 2014 | **Spotting Suspicious Link Behavior with fBox: An Adversarial Perspective**  | ICDM 2014 | [Link](https://arxiv.org/pdf/1410.3915.pdf) | [Link](https://github.com/safe-graph/UGFraud) |


## Toolbox [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]

[PyGOD: A Python Library for Graph Outlier Detection (Anomaly Detection)](https://github.com/pygod-team/pygod)

[DGFraud-TF2: A Deep Graph-based Toolbox for Fraud Detection in TensorFlow 2.0](https://github.com/safe-graph/DGFraud-TF2)

[DGFraud: A Deep Graph-based Toolbox for Fraud Detection](https://github.com/safe-graph/DGFraud)

[UGFraud: An Unsupervised Graph-based Toolbox for Fraud Detection](https://github.com/safe-graph/UGFraud)

[GNN-based Fake News Detection](https://github.com/safe-graph/GNN-FakeNews)

[Realtime Fraud Detection with GNN on DGL](https://github.com/awslabs/realtime-fraud-detection-with-gnn-on-dgl)


## Dataset [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]

[Node Outlier Detection Benchmark](https://github.com/pygod-team/pygod/tree/main/benchmark)

[Twitter Fake News Propagation Graph Dataset](https://github.com/safe-graph/GNN-FakeNews)

[Yelp & Amazon Fraud Graph Dataset](https://github.com/dmlc/dgl/blob/master/python/dgl/data/fraud.py)

[Risk Commodities Detection on Large-Scale E-commerce Graphs](https://tianchi.aliyun.com/competition/entrance/531976/introduction?lang=en-us)

[Fraudster Nodes in Dynamic Financial Social Network](https://dgraph.xinye.com/dataset)

[Anomalous Accounts in Transaction and Social Networks](https://github.com/squareRoot3/Rethinking-Anomaly-Detection)

[Ethereum Phishing Transaction Network](http://xblock.pro/tx/)

[IEEE-CIS Fraud Detection Dataset](https://www.kaggle.com/c/ieee-fraud-detection)

[Outlier Detection DataSets (ODDS)](http://odds.cs.stonybrook.edu/)

[Graph Fraud Datasets from Prof. Srijan Kumar](https://cs.stanford.edu/~srijan/)

[Bitcoin Fraudulent Transaction Dataset](https://www.kaggle.com/ellipticco/elliptic-data-set)

[Mobile App Install Fraud Dataset](https://github.com/mobvistaresearch/CIKM2020-BotSpot)


## Other Resource [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]

[\[Blog\] Graph Neural Network-based Graph Outlier Detection: A Brief Introduction](https://www.tigergraph.com/blog/graph-neural-network-based-graph-outlier-detection-a-brief-introduction/)

[\[Slides\] Leveraging GNNs for Financial Fraud Detection: Practices and Challenges](https://ytongdou.com/files/GNN_Fin_Fraud.pdf)

[\[Slides\] Graph Learning in Financial Networks by Jiaxuan You](https://snap.stanford.edu/graphlearning-workshop/slides/stanford_graph_learning_Finance.pdf)

[\[Blog\] 伊利诺伊大学窦英通：基于图神经网络的欺诈检测](https://zhuanlan.zhihu.com/p/457105796)

[\[Slides\] Graph Neural Network-based Fraud Detection -- from Research to Application](https://ytongdou.com/files/GNN_Fraud_Talk.pdf)

[\[Video\] Fraud Detection with Graph Neural Networks](https://youtu.be/MZGuz-o7Fl0)

[\[Video\] Fake News Detection using Graphs with Pytorch Geometric](https://youtu.be/QAIVFr24FrA) 

[\[Paper List\] Graph Adversarial Learning Literature](https://github.com/safe-graph/graph-adversarial-learning-literature)

[\[Paper List\] Awesome Fraud Detection Research Papers](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers)

[\[Tutorial\] Graph-Based User Behavior Modeling: From Prediction to Fraud Detection](https://www.cs.cmu.edu/~abeutel/kdd2015_tutorial/tutorial.pdf)

## Survey Paper [[Back to Top](#graph-based-fraud-detection-papers-and-resources)]

[Graph Learning for Anomaly Analytics: Algorithms, Applications, and Challenges](https://dl.acm.org/doi/pdf/10.1145/3570906)

[A Comprehensive Survey of Graph-based Deep Learning Approaches for Anomaly Detection in Complex Distributed Systems](https://arxiv.org/pdf/2206.04149.pdf)

[Intelligent financial fraud detection practices in post-pandemic era](https://www.sciencedirect.com/science/article/pii/S2666675821001016)

[A Comprehensive Survey on Graph Anomaly Detection with Deep Learning](https://arxiv.org/pdf/2106.07178.pdf)

[Anomaly Mining - Past, Present and Future](https://arxiv.org/pdf/2105.10077.pdf)

[Graph Computing for Financial Crime and Fraud Detection: Trends, Challenges and Outlook](https://arxiv.org/pdf/2103.03227.pdf)

[Graph based anomaly detection and description: a survey](https://link.springer.com/article/10.1007/s10618-014-0365-y)

[Adversarial Attack and Defense on Graph Data: A Survey](https://arxiv.org/abs/1812.10528)

[Suspicious behavior detection: Current trends and future directions](https://ieeexplore.ieee.org/abstract/document/7389913)

[False information on web and social media: A survey](https://arxiv.org/abs/1804.08559)

[Misinformation in Social Media: Definition, Manipulation, and Detection](https://dl.acm.org/citation.cfm?id=3373475)

[Mining Disinformation and Fake News: Concepts, Methods, and Recent Advancements](https://arxiv.org/abs/2001.00623)

