# Awesome Secure Collaborative Learning Papers

A curated list of robust and privacy-preserving collaborative learning publications, organized by the order **System Overview**, **Integrity Attacks and Defenses**, **Privacy Threats and Defenses**

## Table of Content

- [Awesome Secure Collaborative Learning Papers](#awesome-s-p-collaborative-learning-papers)
  * [System Overview](#system-overview)
    + [Centralized](#centralized)
    + [Decentralized](#decentralized)
    + [Federated Learning](#federated-learning)
    + [Application](#application)
    + [Survey](#survey)
  * [Integrity Attacks](#integrity-attacks)
    + [Data Poison](#data-poison)
    + [Model Poison](#model-poison)
  * [Integrity Defenses](#integrity-defenses)
    + [Data Based Inspection](#data-based-inspection)
    + [Model Based Inspection](#model-based-inspection)
  * [Privacy Threats](#privacy-threats)
    + [Membership Inference Attacks](#membership-inference-attacks)
    + [Property Inference Attacks](#property-inference-attacks)
    + [Sample Inference Attacks](#sample-inference-attacks)
    + [Membership &amp; Property](#membership---property)
  * [Privacy Defenses](#privacy-defenses)
    + [Differential Privacy Defences]()
    + [Cryptographic Privacy Defenses]()
    + [Practical Privacy Defenses]()
  * [Hybrid Defenses and Beyond]()
    + [Hybrid Defenses]()
    + [Collaborative Adversarial Training]()

## System Overview

### Centralized

* [Exploiting GPUs for Efficient Gradient Boosting Decision Tree Training](https://ieeexplore.ieee.org/document/8727750/) , TPDS 2020
* [SPARKNET: TRAINING DEEP NETWORKS IN SPARK](https://arxiv.org/abs/1511.06051)  , ICLR 2016
* [Scaling Distributed Machine Learning with the Parameter Server](https://www.usenix.org/conference/osdi14/technical-sessions/presentation/li_mu) , USENIX 2014
* [More Effective Distributed ML via a Stale Synchronous Parallel Parameter Server](https://proceedings.neurips.cc/paper/2013/hash/b7bb35b9c6ca2aee2df08cf09d7016c2-Abstract.html)  , NeurIPS 2013
* [Large Scale Distributed Deep Networks](https://proceedings.neurips.cc/paper/2012/file/6aca97005c68f1206823815f66102863-Paper.pdf) , NeurIPS 2012

### Decentralized

* [Decentralized Learning With Lazy and Approximate Dual Gradients](https://ieeexplore.ieee.org/document/9347822/), IEEE Trans. Signal Process. 2021
* [Consensus Control for Decentralized Deep Learning](https://arxiv.org/pdf/2102.04828.pdf), ICML 2021
* [Cross-Gradient Aggregation for Decentralized Learning from Non-IID data](http://arxiv.org/abs/2103.02051), ICML 2021
* [Byzantine-Resilient Decentralized Policy Evaluation With Linear Function Approximation](https://ieeexplore.ieee.org/document/9462519/), IEEE Trans. Signal Process. 2021
* [Stability and Generalization of Decentralized Stochastic Gradient Descent](https://ojs.aaai.org/index.php/AAAI/article/view/17173), AAAI 2021
* [Optimal and Practical Algorithms for Smooth and Strongly Convex Decentralized Optimization](https://proceedings.neurips.cc/paper/2020/file/d530d454337fb09964237fecb4bea6ce-Paper.pdf), NeurIPS 2020
* [A Decentralized Parallel Algorithm for Training Generative Adversarial Nets](https://par.nsf.gov/servlets/purl/10233157) , NeurIPS 2020
* [Communication Compression for Decentralized Training](https://papers.nips.cc/paper/2018/file/44feb0096faa8326192570788b38c1d1-Paper.pdf), NeurIPS 2018
* [an Decentralized Algorithms Outperform Centralized Algorithms? A Case Study for Decentralized Parallel Stochastic Gradient Descent](https://proceedings.neurips.cc/paper/2017/file/f75526659f31040afeb61cb7133e4e6d-Paper.pdf), NeurIPS 2017
* [Fully Decentralized Policies for Multi-Agent Systems: An Information Theoretic Approach](https://proceedings.neurips.cc/paper/2017/file/8bb88f80d334b1869781beb89f7b73be-Paper.pdf), NeurIPS 2017

### Federated Learning

* [Curse or Redemption? How Data Heterogeneity Affects the Robustness of Federated Learning](https://www.aaai.org/AAAI21Papers/AAAI-8990.ZawadS.pdf) , AAAI 2021
* [On the Convergence of Communication-Efficient Local SGD for Federated Learning](https://www.aaai.org/AAAI21Papers/AAAI-3649.GaoH.pdf) , AAAI 2021
* [Federated Bayesian Optimization via Thompson Sampling](http://arxiv.org/abs/2010.10154)  , NeurIPS 2020
* [Performance Optimization of Federated Person Re-identification via Benchmark Analysis](https://dl.acm.org/doi/10.1145/3394171.3413814) , MM 2020
* [Tackling the Objective Inconsistency Problem in Heterogeneous Federated Optimization](https://proceedings.neurips.cc/paper/2020/file/564127c03caab942e503ee6f810f54fd-Paper.pdf) , NeurIPS 2020
* [SCAFFOLD: Stochastic Controlled Averaging for Federated Learning](http://proceedings.mlr.press/v119/karimireddy20a.html) , ICML 2020
* [Practical Federated Gradient Boosting Decision Trees](https://ojs.aaai.org/index.php/AAAI/article/view/5895) , AAAI 2020
* [Personalized Federated Learning with Theoretical Guarantees: A Model-Agnostic Meta-Learning Approach](https://proceedings.neurips.cc/paper_files/paper/2020/hash/24389bfe4fe2eba8bf9aa9203a44cdad-Abstract.html) , NeurIPS 2020
* [Towards Federated Learning at Scale: System Design](https://arxiv.org/abs/1902.01046)  , SysML 2019
* [Adaptive Kernel Value Caching for SVM Training](https://ieeexplore.ieee.org/document/8890007/)  , IEEE Trans Neural Netw Learn Syst 2019
* [A Performance Evaluation of Federated Learning Algorithms](https://dl.acm.org/doi/10.1145/3286490.3286559)  , DIDL 2018
* [Federated Multi-Task Learning](http://papers.neurips.cc/paper/7029-federated-multi-task-learning.pdf)  , NeurIPS 2017

### Application

* [Model-Contrastive Federated Learning](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Model-Contrastive_Federated_Learning_CVPR_2021_paper.pdf) , CVPR 2021
* [Federated Meta-Learning for Fraudulent Credit Card Detection](https://www.ijcai.org/proceedings/2020/642) , IJCAI 2020
* [Group Knowledge Transfer: Federated Learning of Large CNNs at the Edge](https://proceedings.neurips.cc/paper/2020/file/a1d4c20b182ad7137ab3606f0e3fc8a4-Paper.pdf) , NeurIPS 2020
* [Privacy Regulation Aware Process Mapping in Geo-Distributed Cloud Data Centers](https://ieeexplore.ieee.org/document/8632727/) , TPDS 2019
* [Client Selection for Federated Learning with Heterogeneous Resources in Mobile Edge](https://ieeexplore.ieee.org/document/8761315/) , ICC 2019
* [Federated Learning for Keyword Spotting](https://ieeexplore.ieee.org/document/8683546/) , ICASSP 2019
* [Imagenet classification with deep convolutional neural networks](https://proceedings.neurips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf) , NeurIPS 2012

### Survey

* [A Survey on Federated Learning: The Journey From Centralized to Distributed On-Site Learning and Beyond](https://ieeexplore.ieee.org/document/9220780/) , IEEE Internet Things J. 2021
* [A survey on security and privacy of federated learning](https://linkinghub.elsevier.com/retrieve/pii/S0167739X20329848), Future Gener. Comput. Syst. 2021
* [A Comprehensive Survey of Privacy-preserving Federated Learning: A Taxonomy, Review, and Future Directions](https://dl.acm.org/doi/10.1145/3460427), ACM Comput. Surv. 2021
* [Privacy and Robustness in Federated Learning: Attacks and Defenses](http://arxiv.org/abs/2012.06337), arXiv 2020
* [Threats to Federated Learning: A Survey](http://arxiv.org/abs/2003.02133), arXiv 2020

## Integrity Attacks

### Data Poison
* [Invisible backdoor attack with sample-specific triggers](http://openaccess.thecvf.com/content/ICCV2021/html/Li_Invisible_Backdoor_Attack_With_Sample-Specific_Triggers_ICCV_2021_paper.html) , CVPR 2021
* [LIRA: Learnable, Imperceptible and Robust Backdoor Attacks](http://openaccess.thecvf.com/content/ICCV2021/html/Doan_LIRA_Learnable_Imperceptible_and_Robust_Backdoor_Attacks_ICCV_2021_paper.html) , CVPR 2021
* [PoisonGAN: Generative Poisoning Attacks Against Federated Learning in Edge Computing Systems](https://ieeexplore.ieee.org/document/9194010/) , IEEE Internet Things J. 2021
* [Poison Attacks on Federated Learning Based IoT Intrusion Detection System](https://www.ndss-symposium.org/wp-content/uploads/2020/04/diss2020-23003-paper.pdf) , DISS 2020
* [MetaPoison: Practical General-purpose Clean-label Data Poisoning](https://arxiv.org/abs/2004.00225) , NeurIPS 2020
* [Clean-Label Backdoor Attacks on Video Recognition Models](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhao_Clean-Label_Backdoor_Attacks_on_Video_Recognition_Models_CVPR_2020_paper.html) , CVPR 2020
* [Data Poisoning Attacks on Federated Machine Learning](https://arxiv.org/abs/2004.10020) , arXiv 2020
* [Attack of the Tails: Yes, You Really Can Backdoor Federated Learning](https://arxiv.org/pdf/2007.05084.pdf) , arXiv 2020
* [Transferable Clean-Label Poisoning Attacks on Deep Neural Nets](http://proceedings.mlr.press/v97/zhu19a.html) , ICML 2019
* [Clean-Label Backdoor Attacks](https://github.com/csl-cqu/awesome-secure-collebrative-learning-papers/blob/main/clean_label_backdoor_attacks.pdf) , ICLR 2019
* [DBA: DISTRIBUTED BACKDOOR ATTACKS AGAINST FEDERATED LEARNING](https://openreview.net/forum?id=rkgyS0VFvr) , ICLR 2019
* [Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks](https://arxiv.org/abs/1804.00792) , NeurIPS 2018
* [Backdoor Attacks against Learning Systems](https://ieeexplore.ieee.org/abstract/document/8228656) , CNS 2017
* [BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain](https://arxiv.org/abs/1708.06733) , arXiv 2017
* [Data Poisoning Attacks on Factorization-Based Collaborative Filtering](https://proceedings.neurips.cc/paper/2016/file/83fa5a432ae55c253d0e60dbfa716723-Paper.pdf) , NeurIPS 2016
* [Data Poisoning Attacks against Autoregressive Models](https://ojs.aaai.org/index.php/AAAI/article/view/10237) , AAAI 2016

### Model Poison

* [Local Model Poisoning Attacks to Byzantine-Robust Federated Learning](https://www.usenix.org/conference/usenixsecurity20/presentation/fang) , USENIX 2020
* [How To Backdoor Federated Learning](https://arxiv.org/pdf/2007.05084.pdf) , ICML 2020
* [Can You Really Backdoor Federated Learning?](https://arxiv.org/abs/1911.07963) , arXiv 2019
* [Analyzing Federated Learning through an Adversarial Lens](http://proceedings.mlr.press/v97/bhagoji19a.html) , ICML 2019

## Integrity Defenses

### Data Based Inspection
* [FL-WBC: Enhancing Robustness against Model Poisoning Attacks in Federated Learning from a Client Perspective](https://proceedings.neurips.cc/paper/2021/hash/692baebec3bb4b53d7ebc3b9fabac31b-Abstract.html) , NeurIPS 2021
* [Scalable Backdoor Detection in Neural Networks](https://arxiv.org/abs/2006.05646) , arXiv 2020 .
* [Shielding Collaborative Learning: Mitigating Poisoning Attacks through Client-Side Detection](https://ieeexplore.ieee.org/abstract/document/9066920) , TDSC 2020 .
* [SentiNet: Detecting Localized Universal Attacks Against Deep Learning Systems](https://ieeexplore.ieee.org/abstract/document/9283822) , SPW 2020
* [Systematic Evaluation of Backdoor Data Poisoning Attacks on Image Classifiers](https://openaccess.thecvf.com/content_CVPRW_2020/html/w47/Truong_Systematic_Evaluation_of_Backdoor_Data_Poisoning_Attacks_on_Image_Classifiers_CVPRW_2020_paper.html) , CVPR 2020
* [ ABS: Scanning neural networks for back-doors by artificial brain stimulation](https://dl.acm.org/doi/abs/10.1145/3319535.3363216) , SIGSAC
* [STRIP: A Defence Against Trojan Attacks on Deep Neural Networks](https://dl.acm.org/doi/abs/10.1145/3359789.3359790) , ACSAC 2019
* [Poison as a Cure: Detecting &amp; Neutralizing Variable-Sized Backdoor Attacks in Deep Neural Networks](https://arxiv.org/abs/1911.08040) , arXiv 2019
* [Spectral Signatures in Backdoor Attacks](https://arxiv.org/abs/1811.00636) , NeurIPS 2018
* [Detecting Backdoor Attacks on Deep Neural Networks by Activation Clustering](https://arxiv.org/pdf/1811.03728.pdf) , arXiv 2018

### Model Based Inspection

* [DeepSight: Mitigating Backdoor Attacks in Federated Learning Through Deep Model Inspection](https://arxiv.org/pdf/2201.00763.pdf) , NDSS 2022
* [CRFL: Certifiably Robust Federated Learning against Backdoor Attacks](http://arxiv.org/abs/2106.08283) , ICML 2021
* [Backdoor attacks and defenses in feature-partitioned collaborative learning](https://arxiv.org/abs/2007.03608) , arXiv 2020
* [ABS: Scanning Neural Networks for Back-doors by Artificial Brain Stimulation](https://dl.acm.org/doi/abs/10.1145/3319535.3363216) , CCS 2019
* [NIC: Detecting Adversarial Samples with Neural Network Invariant Checking](https://par.nsf.gov/servlets/purl/10139597) , NDSS 2019
* [Neural Cleanse: Identifying and Mitigating Backdoor Attacks in Neural Networks](https://ieeexplore.ieee.org/abstract/document/8835365) , Oakland 2019
* [NeuronInspect: Detecting Backdoors in Neural Networks via Output Explanations](https://arxiv.org/abs/1911.07399) , arXiv 2019 .
* [DeepInspect: A Black-box Trojan Detection and Mitigation Framework for Deep Neural Networks](http://www.aceslab.org/sites/default/files/DeepInspect.pdf) , IJCAI 2019

## Privacy Threats

### Membership Inference Attacks
* [Beyond Class-Level Privacy Leakage: Breaking Record-Level Privacy in Federated Learning](https://ieeexplore.ieee.org/abstract/document/9456909/) , IEEE Internet Things J. 2021
* [GAN Enhanced Membership Inference: A Passive LocalAttack in Federated Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9148790) , ICC 2020
* [Comprehensive Privacy Analysis of Deep Learning: Passive and Active White-box Inference Attacks against Centralized and Federated Learning](https://ieeexplore.ieee.org/document/8835245/) , Oakland 2019
* [Membership Inference Attacks Against Machine Learning Models](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7958568) , Oakland 2017

### Property Inference Attacks
* [Leakage of Dataset Properties in Multi-Party Machine Learning](https://www.usenix.org/conference/usenixsecurity21/presentation/zhang-wanrong) , USENIX 2021
* [Beyond inferring class representatives: User-level privacy leakage from federated learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8737416) , ICCC 2019

### Sample Inference Attacks
* [See through Gradients: Image Batch Recovery via GradInversion](https://openaccess.thecvf.com/content/CVPR2021/html/Yin_See_Through_Gradients_Image_Batch_Recovery_via_GradInversion_CVPR_2021_paper.html), CVPR 2021
* [ Revealing and Protecting Labels in Distributed Training](https://proceedings.neurips.cc/paper/2021/hash/0d924f0e6b3fd0d91074c22727a53966-Abstract.html) , NeurIPS 2021
* [CAFE: Catastrophic Data Leakage in Vertical Federated Learning](https://arxiv.org/abs/2110.15122)  , NeurIPS 2021
* [Label Inference Attacks Against Vertical Federated Learning](https://www.usenix.org/conference/usenixsecurity22/presentation/fu) , USENIX 2021
* [Knowledge-Enriched Distributional Model Inversion Attacks](http://openaccess.thecvf.com/content/ICCV2021/html/Chen_Knowledge-Enriched_Distributional_Model_Inversion_Attacks_ICCV_2021_paper.html) , CVPR 2021
* [Gradient Disaggregation: Breaking Privacy in Federated Learning by Reconstructing the User Participant Matrix](http://arxiv.org/abs/2106.06089) , ICML 2021
* [Inverting Gradients–How easy is it to break privacy in federated learning](https://arxiv.org/abs/2003.14053) , arXiv 2020
* [iDLG: Improved Deep Leakage from Gradients](https://arxiv.org/abs/2001.02610) , arXiv 2020
* [Deep Leakage from Gradients](https://proceedings.neurips.cc/paper/2019/hash/60a6c4002cc7b29142def8871531281a-Abstract.html) , NeurIPS 2019

### Membership & Property

* [Exploiting Unintended Feature Leakage in Collaborative Learning](https://ieeexplore.ieee.org/abstract/document/8835269) , Oakland 2019

## Privacy Defenses

### Differentially Private Defences
* [Accurate Differentially Private Deep Learning on the Edge](https://ieeexplore.ieee.org/abstract/document/9372811/) , IEEE Trans Parallel Distrib Syst 2021
* [User-Level Privacy-Preserving Federated Learning: Analysis and Performance Optimization](https://ieeexplore.ieee.org/abstract/document/9347706/) , IEEE Trans Mob Comput 2021
* [Gradient-leakage resilient federated learning](https://ieeexplore.ieee.org/abstract/document/9546481/) , ICDCS 2021
* [Pain-FL: Personalized Privacy-Preserving Incentive for Federated Learning](https://ieeexplore.ieee.org/abstract/document/9565851/) , IEEE J. Sel. Areas Commun. 2021
* [Romoa: Robust Model Aggregation for the Resistance of Federated Learning to Model Poisoning Attacks](https://link.springer.com/chapter/10.1007/978-3-030-88418-5_23) , ESORICS 2021
* [Privacy Threat and Defense for Federated Learning with Non-iid Data in AIoT](https://ieeexplore.ieee.org/abstract/document/9408373/) , IEEE Trans Industr Inform 2021
* [Differentially Private and Communication Efficient Collaborative Learning](https://www.aaai.org/AAAI21Papers/AAAI-1503.DingJ.pdf), AAAI 2021
* [FLAME: Differentially Private Federated Learning in the Shuffle Model](https://www.aaai.org/AAAI21Papers/AAAI-4838.LiuR.pdf) , AAAI 2021
* [Local Differential Privacy-Based Federated Learning for Internet of Things](https://ieeexplore.ieee.org/document/9253545/) , IEEE Internet Things J. 2021
* [Federated Learning with Local Differential Privacy: Trade-Offs Between Privacy, Utility, and Communication](https://ieeexplore.ieee.org/document/9413764/) , ICASSP 2021
* [LDP-FL: Practical Private Aggregation in Federated Learning with Local Differential Privacy](http://arxiv.org/abs/2007.15789) , IJCAI 2021
* [Federated Learning with Sparsification-Amplified Privacy and Adaptive Optimization](https://www.ijcai.org/proceedings/2021/202) , IJCAI 2021
* [Attacks to Federated Learning: Responsive Web User Interface to Recover Training Data from User Gradients](http://arxiv.org/abs/2006.04695) , ASIACCS 2020
* [Federated Learning with Differential Privacy: Algorithms and Performance Analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9069945) , TIFS 2020
* [Protection against reconstruction and its applications in private federated learning](https://arxiv.org/pdf/1812.00984.pdf) , arXiv 2019
* [Differentially private model publishing for deep learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8835283) , Oakland 2019
* [Evaluating Differentially Private Machine Learning in Practice](https://www.usenix.org/conference/usenixsecurity19/presentation/jayaraman) , USENIX 2019
* [Differentially private distributed online learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8260919) , TKDE 2018
* [Improving the Privacy and Accuracy of ADMM-Based Distributed Algorithms](http://proceedings.mlr.press/v80/zhang18f/zhang18f.pdf) , ICML 2018
* [DP-EM: Differentially Private Expectation Maximization](http://proceedings.mlr.press/v54/park17c.html) , ICML 2017
* [Differential privacy preservation for deep auto-encoders: An application of human behavior prediction](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/viewPaper/12174) , AAAI 2016
* [Deep learning with differential privacy](https://dl.acm.org/doi/abs/10.1145/2976749.2978318) , CCS 2016
* [Privacy-preserving deep learning](https://dl.acm.org/doi/abs/10.1145/2810103.2813687) , CCS 2015
* [Differentially private empirical risk minimization](https://www.jmlr.org/papers/volume12/chaudhuri11a/chaudhuri11a.pdf) , JMLR 2011

### Cryptographic Privacy Defenses

#### Homomorphic Encryption(HE)
* [GALA: Greedy ComputAtion for Linear Algebra in Privacy-Preserved Neural Networks](https://arxiv.org/abs/2105.01827) , NDSS 2021
* [Batchcrypt: Efficient homomorphic encryption for cross-silo federated learning](https://www.usenix.org/conference/atc20/presentation/zhang-chengliang) , USENIX 2020
* [Privacy-Preserving Federated Deep Learning with Irregular Users](https://ieeexplore.ieee.org/abstract/document/9130089/) , IEEE Trans Dependable Secure Comput 2020
* [Secure Logistic Regression Based on Homomorphic Encryption: Design and Evaluation](http://medinform.jmir.org/2018/2/e19/), JMIR 2018
* [Privacy-Preserving Deep Learning via Additively Homomorphic Encryption](http://ieeexplore.ieee.org/document/8241854/), IEEE Trans.Inform.Forensic Secur. 2018
* [Oblivious Neural Network Predictions via MiniONN Transformations](https://dl.acm.org/doi/10.1145/3133956.3134056) , CCS 2017
* [SecureML: A System for Scalable Privacy-Preserving Machine Learning](http://ieeexplore.ieee.org/document/7958569/), Oakland 2017
* [Scalable and Secure Logistic Regression via Homomorphic Encryption](https://dl.acm.org/doi/10.1145/2857705.2857731), CODASPY 2016

#### Secure Muti-Party Computation(SMC)
* [Privacy-Preserving Federated Learning Framework Based on Chained Secure Multiparty Computing](https://ieeexplore.ieee.org/document/9187932/) , IEEE Internet Things J. 2021
* [Keep Your Data Locally: Federated-Learning-Based Data Privacy Preservation in Edge Computing](https://ieeexplore.ieee.org/document/9318241/) , IEEE Network 2021
* [Toward secure and privacy-preserving distributed deep learning in fog-cloud computing](https://ieeexplore.ieee.org/abstract/document/9151163/) , IEEE Internet Things J. 2020
* [Secure single-server aggregation with (poly) logarithmic overhead](https://dl.acm.org/doi/abs/10.1145/3372297.3417885) , IEEE Trans. Inf. Forensics Secur 2020
* [HybridAlpha: An Efficient Approach for Privacy-Preserving Federated Learning](http://dl.acm.org/citation.cfm?doid=3338501.3357371) , AISec 2019
* [Chameleon: A Hybrid Secure Computation Framework for Machine Learning Applications](https://dl.acm.org/doi/10.1145/3196494.3196522) , CCS 2018
* [Practical Secure Aggregation for Privacy-Preserving Machine Learning](https://dl.acm.org/doi/10.1145/3133956.3133982) , CCS 2017

#### DP & SMC

* [A Hybrid Approach to Privacy-Preserving Federated Learning](http://dl.acm.org/citation.cfm?doid=3338501.3357370) , AISec 2019
* [Distributed learning without distress: Privacy-preserving empirical risk minimization](https://proceedings.neurips.cc/paper/2018/file/7221e5c8ec6b08ef6d3f9ff3ce6eb1d1-Paper.pdf) , NeurIPS 2018

#### DP & Trusted Hardware

* [Efficient deep learning on multi-source private data](https://arxiv.org/pdf/1807.06689.pdf) , arXiv 2018

### Practical Privacy Defenses
* [Privacy-preserving collaborative learning with automatic transformation search](https://personal.ntu.edu.sg/tianwei.zhang/paper/cvpr2021.pdf) , CVPR 2021
* [PrivateDL: Privacy-preserving collaborative deep learning against leakage from gradient sharing](https://onlinelibrary.wiley.com/doi/full/10.1002/int.22241) , International Journal of Intelligent Systems 2020
## Hybrid Defenses and Beyond
### Hybrid Defenses
* [Privacy-preserving Byzantine-robust federated learning](https://www.sciencedirect.com/science/article/pii/S0920548921000568) , Comput. Stand 2022
* [Privacy-preserving blockchain-based federated learning for traffic flow prediction](https://www.sciencedirect.com/science/article/pii/S0167739X2033065X) , Future Gener Comput Syst 2021
* [Privacy-Enhanced Federated Learning Against Poisoning Adversaries](https://ieeexplore.ieee.org/abstract/document/9524709/) , IEEE Trans. Inf. Forensics Secur 2021
* [DP-SIGNSGD: When Efficiency Meets Privacy and Robustness](https://ieeexplore.ieee.org/abstract/document/9414538/) , ICASSP 2021
* [FLOD: Oblivious Defender for Private Byzantine-Robust Federated Learning with Dishonest-Majority](https://eprint.iacr.org/2021/993) , ESORICS 2021
* [Secure and Privacy-Preserving Federated Learning via Co-Utility](https://ieeexplore.ieee.org/abstract/document/9504596/) , IEEE Internet Things J. 2021
* [Toward robustness and privacy in federated learning: Experimenting with local and central differential privacy](https://arxiv.org/abs/2009.03561) , arXiv 2020
* [Robust aggregation for adaptive privacy preserving federated learning in healthcare](https://arxiv.org/abs/2009.08294) , arXiv 2020
### Collaborative Adversarial Training
* [Recent Advances in Adversarial Training for Adversarial Robustness](https://arxiv.org/abs/2102.01356) , arXiv 2021
* [Federated Robustness Propagation: Sharing Adversarial Robustness in Federated Learning](https://arxiv.org/abs/2106.10196) , arXiv 2021
* [Adversarial training in communication constrained federated learning](https://arxiv.org/abs/2103.01319) , arXiv 2021
* [Adversarially Robust Federated Learning for Neural Networks](https://openreview.net/forum?id=5xaInvrGWp) , 2020
* [Fast is better than free: Revisiting adversarial training](https://arxiv.org/abs/2001.03994) , arXiv 2020
* [Adversarial training for free](https://proceedings.neurips.cc/paper/2019/file/7503cfacd12053d309b6bed5c89de212-Paper.pdf) , NeurIPS 2019
