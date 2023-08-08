# Awesome Attack and Defense on Graph-based recommendation system Papers
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

This repository aims to provide links to work about adversarial robustness and privacy security on Graph-based recommendation system
<div align=center><img src="https://www.cs.cit.tum.de/fileadmin/w00cfj/daml/nettack/nettack.png" width="500" /></div>



### Contents


* [1. Survey Papers](#1-survey-papers)
* [2. Graph-based recommendation system Papers](#2-graph-based-recommendation-papers) 
* [3. Adversarial robustness Papers](Adversarial robustness  Papers)
    * [3.1 White-box Attack & Grey-box Attack](#31-White-box Attack&Grey-box Attack)
    * [3.2 Blak-box-attack](#32-blak-box-attack) 
    * [3.3 Adversarial robustness defend](#33-Adversarial-robustness-defend)
    * [3.4 Graph purification](#34-Graph purification)
    * [3.5 Graph-based recommendation system robustness evaluation](#35-Graph-based-recommendation-system-robustness-revaluation)
* [4. Privacy attack Papers](#4-Privacy-attack-Papers)
* [5. Different privacy on Graph-based recommendation system Papers](#5-Different-privacy-on-Graph-based-recommendation-system-Papers)
* [6. Federal learning on Graph-based recommendation system Papers](#6-Federal learning on Graph-based recommendation system Papers)

## 0. Toolbox
Github Repository: **DeepRobust** ([https://github.com/DSE-MSU/DeepRobust](https://github.com/DSE-MSU/DeepRobust))

Corresponding paper: **DeepRobust: A PyTorch Library for Adversarial Attacks and Defenses.** [[paper]](https://arxiv.org/abs/2005.06149)[[documentation]](https://deeprobust.readthedocs.io/en/latest/)

## 1. Survey Papers
1. **Adversarial Attacks and Defenses on Graphs: A Review and Empirical Study.**  SIGKDD Explorations 2020. [[paper]](https://arxiv.org/abs/2003.00653) [[code]](https://github.com/DSE-MSU/DeepRobust/)
1. **A Comprehensive Survey on Trustworthy Recommender Systems.** WWW, Tutorial 2023. [[paper]](https://arxiv.org/pdf/2209.10117.pdf) [[tutorial]](https://advanced-recommender-systems.github.io/trustworthiness-tutorial/)
1. **Adversarial attack and defense on graph data: A survey.** IEEE Transactions on Knowledge and Data Engineering, 2022. [[paper]](https://ieeexplore.ieee.org/abstract/document/9878092/) 

## 2. Graph-based recommendation system Papers
1. **Inductive Representation Learning on Large Graphs** SIGIR 2017. [[paper]](https://cs.stanford.edu/people/jure/pubs/graphsage-nips17.pdf) [[code]](https://github.com/williamleif/GraphSAGE)
1. **Lightgcn: Simplifying and powering graph convolution network for recommendation.** SIGIR 2020. [[paper]](https://dl.acm.org/doi/abs/10.1145/3397271.3401063) [[code]](https://github.com/gusye1234/LightGCN-PyTorch)


## 3. Adversarial robustness Papers
### 3.1 White-box Attack & Grey-box Attack
1. **Poisoning attacks to graph-based recommender systems.** ACSAC 2018. [[paper]](https://par.nsf.gov/servlets/purl/10110254) 
1. **Adversarial attacks on neural networks for graph data.** KDD 2018. [[paper]](https://dl.acm.org/doi/abs/10.1145/3219819.3220078) [[code]](https://github.com/danielzuegner/nettack)
1. **Learning to Deceive Knowledge Graph Augmented Models via Targeted Perturbation.** ICLR 2021. [[paper]](https://arxiv.org/abs/2010.12872) [[code]](https://github.com/INK-USC/deceive-KG-models)


### 3.2 Blackbox Attack
1. **An Adaptive Data Poisoning Framework for Attacking Black-box Recommender Systems.** ICDE 2020. [[paper]](https://ieeexplore.ieee.org/abstract/document/9101655/) 
1. **Knowledge-enhanced Black-box Attacks for Recommendations.** KDD 2022. [[paper]](https://ieeexplore.ieee.org/abstract/document/9101655/) [[slide]](https://wenqifan03.github.io/slides/KDD2022/KDD2022-KGAttack.pdf)

### 3.3 Adversarial robustness defend 
1. **Gcn-based user representation learning for unifying robust recommendation and fraudster detection.** SIGIR 2020 [[paper]](https://arxiv.org/pdf/2005.10150.pdf) [[code]](https://github.com/zsjdddhr/GraphRfi)
1. **Adversarial graph perturbations for recommendations at scale.** SIGIR 2022 [[paper]](https://dl.acm.org/doi/abs/10.1145/3477495.3531763) 
1. **Anti-FakeU: Defending Shilling Attacks on Graph Neural Network based Recommender Model.** www 2023 [[paper]](https://dl.acm.org/doi/abs/10.1145/3543507.3583289) 

### 3.4 Graph purification
1. **FRAUDRE: Fraud Detection Dual-Resistant to Graph Inconsistency and Imbalance.** ICDM 2021 [[paper]](https://ieeexplore.ieee.org/document/9679178) [[code]](https://github.com/FraudDetection/FRAUDRE)

### 3.5 Graph-based recommendation system robustness evaluation

1. **Robust Preference-Guided Denoising for Graph based Social Recommendation.** WWW 2023 [[paper]](https://arxiv.org/abs/2303.08346) [[code]](https://github.com/tsinghua-fib-lab/Graph-Denoising-SocialRec)

## 4. Privacy attack Papers
1. **Debiasing Learning for Membership Inference Attacks Against Recommender Systems.** KDD 2022. [[paper]](https://arxiv.org/pdf/2206.12401.pdf) [[code]](https://github.com/WZH-NLP/DL-MIA-KDD-2022)
1. **Graph embedding for recommendation against attribute inference attacks.** WWW 2021. [[paper]](https://dl.acm.org/doi/fullHtml/10.1145/3442381.3449813) 
1. **Black-box attacks on sequential recommenders via data-free model extraction..** RecSys  2021. [[paper]](https://arxiv.org/abs/2109.01165) [[code]](https://github.com/Yueeeeeeee/RecSys-Extraction-Attack)

## 5. Different privacy on Graph-based recommendation system Papers
1. **Certified Robustness of Graph Convolution Networks for Graph Classification under Topological Attacks.**[[paper]](http://www.cs.emory.edu/~jyang71/files/dpggen_sup.pdf)
1. **Heterogeneous graph neural network for privacy-preserving recommendation.** ICDM 2022. [[paper]](https://ieeexplore.ieee.org/abstract/document/10027714/) [[code]](https://github.com/AixWinnie/HeteDP)
## 6. Federal learning on Graph-based recommendation system Papers
1. **Heterogeneous graph neural network for privacy-preserving recommendation.** ICML 2023. [[paper]](https://arxiv.org/abs/2303.05786) [[code]](https://github.com/maiph123/VerticalGNN)

   


