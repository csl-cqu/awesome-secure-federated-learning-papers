# Awesome-Security-and-Privacy-Federated-Learning

A curated list of security and privacy federated learning publications, organized by the order **System Overview**, **Integrity Attacks and Defenses**, **Privacy Threats and Defenses**

## System Overview

| Title                                                        | Team/Authors    | Venue and Year | code |
| ------------------------------------------------------------ | --------------- | -------------- | ---- |
| [Large Scale Distributed Deep Networks](https://proceedings.neurips.cc/paper/2012/file/6aca97005c68f1206823815f66102863-Paper.pdf) | Google Research | NeurIPS 2012   |      |
| [Imagenet classification with deep convolutional neural networks](https://proceedings.neurips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf) | UT              | NeurIPS 2012   |      |
| [More Effective Distributed ML via a Stale Synchronous Parallel Parameter Server](https://proceedings.neurips.cc/paper/2013/hash/b7bb35b9c6ca2aee2df08cf09d7016c2-Abstract.html) | CMU             | NeurIPS 2013   |      |
| [Scaling Distributed Machine Learning with the Parameter Server](https://www.usenix.org/conference/osdi14/technical-sessions/presentation/li_mu) | CMU             | USENIX 2014    |      |
| [SPARKNET: TRAINING DEEP NETWORKS IN SPARK](https://arxiv.org/abs/1511.06051) | UC              | ICLR 2016      |      |
| [Towards Federated Learning at Scale: System Design](https://arxiv.org/abs/1902.01046) | Google Research | SysML 2019     |      |

## Integrity Attacks and Defense

### Attacks

**Data Poison**

| Title                                                        | Team/Authors | venue and year | code |
| ------------------------------------------------------------ | ------------ | -------------- | ---- |
| [BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain](https://arxiv.org/abs/1708.06733) | NYU          | arXiv 2017     |      |
| [Backdoor Attacks against Learning Systems](https://ieeexplore.ieee.org/abstract/document/8228656) | LU           | CNS 2017       |      |
| [DBA: DISTRIBUTED BACKDOOR ATTACKS AGAINST FEDERATED LEARNING](https://openreview.net/forum?id=rkgyS0VFvr) | ZJU          | ICLR 2019      |      |
| [Attack of the Tails: Yes, You Really Can Backdoor Federated Learning](https://arxiv.org/pdf/2007.05084.pdf) | UWM          | arXiv 2020     |      |
| [Data Poisoning Attacks on Federated Machine Learning](https://arxiv.org/abs/2004.10020) | CAS          | arXiv 2020     |      |
| [Clean-Label Backdoor Attacks on Video Recognition Models](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhao_Clean-Label_Backdoor_Attacks_on_Video_Recognition_Models_CVPR_2020_paper.html) | FUDAN        | CVPR 2020      |      |
| [Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks](https://arxiv.org/abs/1804.00792) | UMD          | NeurIPS 2018   |      |
| [Transferable Clean-Label Poisoning Attacks on Deep Neural Nets](http://proceedings.mlr.press/v97/zhu19a.html) | UMD          | ICML 2019      |      |
| [MetaPoison: Practical General-purpose Clean-label Data Poisoning](https://arxiv.org/abs/2004.00225) | UMD          | NeurIPS 2020   |      |
| [Clean-Label Backdoor Attacks](clean_label_backdoor_attacks.pdf) | MIT          | ICLR 2019      |      |
| [poison attacks on federated learning based IoT intrusion detection system](https://www.ndss-symposium.org/wp-content/uploads/2020/04/diss2020-23003-paper.pdf) | TU Darmstadt | DISS 2020      |      |
|                                                              |              |                |      |

**Model Poison**

| Title                                                        | Team/Authors | venue and year | code |
| ------------------------------------------------------------ | ------------ | -------------- | ---- |
| [Analyzing Federated Learning through an Adversarial Lens](http://proceedings.mlr.press/v97/bhagoji19a.html) | PU           | ICML 2019      |      |
| [Can You Really Backdoor Federated Learning?](https://arxiv.org/abs/1911.07963) | CU           | arXiv 2019     |      |
| [How To Backdoor Federated Learning](https://arxiv.org/pdf/2007.05084.pdf) | Cornell      | ICML 2020      |      |
| [Local Model Poisoning Attacks to Byzantine-Robust Federated Learning](https://www.usenix.org/conference/usenixsecurity20/presentation/fang) | Duke         | USENIX 2020    |      |

### Defense

**Data-based inspection**

| Title                                                        | Team/Authors | venue and year                                            | code |
| ------------------------------------------------------------ | ------------ | --------------------------------------------------------- | ---- |
| [Spectral Signatures in Backdoor Attacks](https://arxiv.org/abs/1811.00636) | MIT          | NeurIPS 2018                                              |      |
| [Detecting Backdoor Attacks on Deep Neural Networks by Activation Clustering](https://arxiv.org/pdf/1811.03728.pdf) | ??           | arXiv 2018                                                |      |
| [Poison as a Cure: Detecting & Neutralizing Variable-Sized Backdoor Attacks in Deep Neural Networks](https://arxiv.org/abs/1911.08040) | NTU          | arXiv 2019                                                |      |
| [STRIP: A Defence Against Trojan Attacks on Deep Neural Networks](https://dl.acm.org/doi/abs/10.1145/3359789.3359790) | Njust        | ACSAC 2019                                                |      |
| [ABS: Scanning Neural Networks for Back-doors by Artificial Brain Stimulation](https://dl.acm.org/doi/abs/10.1145/3319535.3363216) | PU           | CCS 2019                                                  |      |
| [NIC: Detecting Adversarial Samples with Neural Network Invariant Checking](https://par.nsf.gov/servlets/purl/10139597) | PU           | NDSS 2019                                                 |      |
| [Neural Cleanse: Identifying and Mitigating Backdoor Attacks in Neural Networks](https://ieeexplore.ieee.org/abstract/document/8835365) | UCSB         | SP 2019                                                   |      |
| [NeuronInspect: Detecting Backdoors in Neural Networks via Output Explanations](https://arxiv.org/abs/1911.07399) | UCLA         | arXiv 2019                                                |      |
| [DeepInspect: A Black-box Trojan Detection and Mitigation Framework for Deep Neural Networks](http://www.aceslab.org/sites/default/files/DeepInspect.pdf) | USCD         | IJCAI 2019                                                |      |
| [Deep Leakage from Gradients](https://proceedings.neurips.cc/paper/2019/hash/60a6c4002cc7b29142def8871531281a-Abstract.html) | MIT          | NeurIPS 2019                                              |      |
| [Systematic Evaluation of Backdoor Data Poisoning Attacks on Image Classifiers](https://openaccess.thecvf.com/content_CVPRW_2020/html/w47/Truong_Systematic_Evaluation_of_Backdoor_Data_Poisoning_Attacks_on_Image_Classifiers_CVPRW_2020_paper.html) | WWU          | CVPR 2020                                                 |      |
| [SentiNet: Detecting Localized Universal Attacks Against Deep Learning Systems](https://ieeexplore.ieee.org/abstract/document/9283822) | Stanford     | SPW 2020                                                  |      |
| [Backdoor attacks and defenses in feature-partitioned collaborative learning](https://arxiv.org/abs/2007.03608) | Webank       | arXiv 2020                                                |      |
| [Shielding Collaborative Learning: Mitigating Poisoning Attacks through Client-Side Detection](https://ieeexplore.ieee.org/abstract/document/9066920) | WHU          | IEEE Transactions on Dependable and Secure Computing 2020 |      |
| [Scalable Backdoor Detection in Neural Networks](https://arxiv.org/abs/2006.05646) | DKU          | arXiv 2020                                                |      |

## Privacy Threats and Defenses

### Threats

**Membership inference**

| Title                                                        | Team/Authors | Venue and Year                                        | Code |
| ------------------------------------------------------------ | ------------ | ----------------------------------------------------- | ---- |
| [Exploiting Unintended Feature Leakage in Collaborative Learning](https://ieeexplore.ieee.org/abstract/document/8835269) | UCL          | SP 2019                                               |      |
| [Comprehensive privacy analysis of deep learning: Passive and active white-box inference attacks against centralized and federated learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8835245) | UMASS        | SP 2019                                               |      |
| [GAN Enhanced Membership Inference: A Passive LocalAttack in Federated Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9148790) | UTS          | ICC 2020                                              |      |
| [Membership Inference Attacks Against Machine Learning Models](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7958568) | Cornell      | SP 2017                                               |      |
| [Beyond inferring class representatives: User-level privacy leakage from federated learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8737416) | WHU          | ICCC 2019                                             |      |
| [Analyzing user-level privacy attack against federated learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9109557) | WHU          | IEEE Journal on Selected Areas in Communications 2020 |      |
| [iDLG: Improved Deep Leakage from Gradients](https://arxiv.org/abs/2001.02610) | Edin         | arXiv 2020                                            |      |
| [Inverting Gradients–How easy is it to break privacy in federated learning](https://arxiv.org/abs/2003.14053) | UniSiegen    | arXiv 2020                                            |      |
### Defenses

| Title                                                        | Team/Authors    | Venue and Year                                               | Code |
| ------------------------------------------------------------ | --------------- | ------------------------------------------------------------ | ---- |
| [Deep learning with differential privacy](https://dl.acm.org/doi/abs/10.1145/2976749.2978318) | Google Research | CCS 2016                                                     |      |
| [Differentially private empirical risk minimization](https://www.jmlr.org/papers/volume12/chaudhuri11a/chaudhuri11a.pdf) | UC              | Journal of Machine Learning Research 2011                    |      |
| [Evaluating Differentially Private Machine Learning in Practice](https://www.usenix.org/conference/usenixsecurity19/presentation/jayaraman) | UVa             | USENIX 2019                                                  |      |
| [Differentially private distributed online learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8260919) | HUST            | IEEE Transactions on Knowledge and Data Engineering 2018     |      |
| [Differentially private model publishing for deep learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8835283) | Gatech          | SP 2019                                                      |      |
| [Improving the Privacy and Accuracy of ADMM-Based Distributed Algorithms](http://proceedings.mlr.press/v80/zhang18f/zhang18f.pdf) | Umich           | ICML 2018                                                    |      |
| [Protection against reconstruction and its applications in private federated learning](https://arxiv.org/pdf/1812.00984.pdf) | Apple           | arXiv 2019                                                   |      |
| [Efficient deep learning on multi-source private data](https://arxiv.org/pdf/1807.06689.pdf) | Berkeley        | arXiv 2018                                                   |      |
| [Weighted Distributed Differential Privacy ERM: Convex and Nonconvex](https://www.sciencedirect.com/science/article/pii/S0167404821000997) | CAS             | Computers & Security 2019                                    |      |
| [Differential privacy preservation for deep auto-encoders: An application of human behavior prediction](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/viewPaper/12174) | Uoregon         | AAAI 2016                                                    |      |
| [Privacy-preserving deep learning](https://dl.acm.org/doi/abs/10.1145/2810103.2813687) | Utexas          | CCS 2015                                                     |      |
| [Federated Learning with Differential Privacy: Algorithms and Performance Analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9069945) | NTU             | IEEE Transactions on Information Forensics and Security 2020 |      |
| [Distributed learning without distress: Privacy-preserving empirical risk minimization](https://proceedings.neurips.cc/paper/2018/file/7221e5c8ec6b08ef6d3f9ff3ce6eb1d1-Paper.pdf) | UVa             | NeurIPS 2018                                                 |      |
| [DP-EM: Differentially Private Expectation Maximization](http://proceedings.mlr.press/v54/park17c.html) | UvA             | ICML 2017                                                    |      |
