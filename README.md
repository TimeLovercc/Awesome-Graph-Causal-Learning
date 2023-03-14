# Awesome Graph Causal Learning

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  ![GitHub stars](https://img.shields.io/github/stars/TimeLovercc/Awesome-Graph-Causal-Learning)

This repository contains a list of **Graph Causal Learning** resources. We also have a survey paper about **Counterfactual Learning on Graphs**. We include a [Not for Graph](#not-for-graph) section to introduce well-selected materials for beginners to learn causal-related concepts.
We will try our best to continuously maintain this Repository in weekly manner.

**Why Causal Learning?**
>Causality connotes lawlike necessity, whereas probabilities connote exceptionality, doubt, and lack of regularity.    --Judea Pearl

Graph Causal Learning is an emerging research area and it can be widely applied in dealing with out of distribution, fairness and explanation problems.

## News
* 2023/01/04: I change the format of the repo and try to include both causal learning papers and counterfactual learning papers.

## Reference
If our repo or survey is useful for your research, please cite our paper as follows:
```
To be done
```

## Contributing
Please help to contribute this list by adding [pull request](https://github.com/TimeLovercc/Awesome-Graph-Causal-Learning/pulls)

Markdown format:
```markdown
- Paper Name. 
  [[pdf]](link) 
  [[code]](link)
  - Author 1, Author 2, **and** Author 3. *Conference/Journal*, Year.
```
**Note**: In the same year, please place the conference paper before the journal paper, as journals are usually submitted a long time ago and therefore have some lag. (*i.e.*, Conferences-->Preprints-->Journals)

## Table of Contents
- [Not for Graph](#not-for-graph)
- [Survey](#survey)
- [Causal Learning](#causal-learning)
    - [Node Classification](#node-classification)
    - [Out of Distribution](#out-of-distribution)
    - [Contrastive Learning](#contrastive-learning)
    - [Recommendation](#recommendation)
- [Counterfactual Learning](#counterfactual-learning)
    - [Counterfactual Fairness](#counterfactual-fairness)
    - [Counterfactual Explanation](#counterfactual-explanation)
    - [Counterfactual Link Prediction and Recommendation](#counterfactual-link-prediction-and-recommendation)
    - [Counterfactual Learning in Real-World Applications](#counterfactual-learning-in-real-world-applications)
- [Causal Discovery](#causal-discovery)
- [Causal Effect Estimate](#causal-effect-estimate)
- [Benchmark](#benchmark)
- [Application](#application)
- [A Summary of Open-source Codes](#a-summary-of-open-source-codes)


## Not for Graph
- Deep Causal Learning: Representation, Discovery and Inference.
  [[pdf]](https://arxiv.org/ftp/arxiv/papers/2211/2211.03374.pdf)
  - Zizhen Deng, Xiaolong Zheng, Hu Tian, and Daniel Dajun Zeng. *arXiv*, 2022.

- Causal Machine Learning: A Survey and Open Problems.
  [[pdf]](https://arxiv.org/pdf/2206.15475.pdf)
  - Jean Kaddour, Aengus Lynch, Qi Liu, Matt J. Kusner, and Ricardo Silva. *arXiv*, 2022.

- Toward Causal Representation Learning.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9363924)
  - Bernhard Schölkopf, Francesco Locatello, Stefan Bauer, Nan Rosemary Ke, Nal Kalchbrenner, Anirudh Goyal, and Yoshua Bengio. *arXiv*, 2021.

- A Survey on Causal Inference.
  [[pdf]](https://arxiv.org/pdf/2002.02770.pdf)
  - Liuyi Yao, Zhixuan Chu, Sheng Li, Yaliang Li, Jing Gao, and Aidong Zhang. *arXiv*, 2020.

- A Survey of Learning Causality with Data: Problems and Methods.
  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3397269)
  - Ruocheng Guo, Lu Cheng, Jundong Li, P. Richard Hahn, and Huan Liu. *ACM Computing Surveys*, 2020.

- Causality for Machine Learning.
  [[pdf]](https://arxiv.org/pdf/1911.10500.pdf)
  - Bernhard Schölkopf. *arXiv*, 2019.

- Counterfactual Fairness.
  [[pdf]](https://arxiv.org/pdf/1703.06856.pdf)
  - Matt J. Kusner, Joshua R. Loftus, Chris Russell, and Ricardo Silva. *NeurIPS*, 2017.

- Learning Representations for Counterfactual Inference.
  [[pdf]](http://proceedings.mlr.press/v48/johansson16.pdf)
  - Fredrik D. Johansson, Uri Shalit, and David Sontag. *ICML*, 2016.

- Causal inference in statistics: An overview.
  [[pdf]](https://ftp.cs.ucla.edu/pub/stat_ser/r350.pdf)
  - Judea Pearl. *Statistics Surveys*, 2009.

## Survey
- A Survey on Graph Counterfactual Explanations: Definitions, Methods, Evaluation.
  [[pdf]](https://arxiv.org/pdf/2210.12089.pdf)
  - Mario Alfonso Prado-Romero, Bardh Prenkaj, Giovanni Stilo, and Fosca Giannotti. *arXiv*, 2022.

## Causal Learning

### Node Classification
- Interpretable and Generalizable Graph Learning via Stochastic Attention Mechanism.
  [[pdf]](https://proceedings.mlr.press/v162/miao22a/miao22a.pdf)
  [[code]](https://github.com/Graph-COM/GSAT)
  - Siqi Miao, Miaoyuan Liu, and Pan Li. *ICML*, 2022.

- Graph Rationalization with Environment-based Augmentations.
  [[pdf]](https://arxiv.org/pdf/2206.02886.pdf)
  [[code]](https://github.com/liugangcode/GREA)
  - Gang Liu, Tong Zhao, Jiaxin Xu, Tengfei Luo, and Meng Jiang. *KDD*, 2022.

### Out of Distribution
- Introducing Expertise Logic into Graph Representation Learning from A Causal Perspective.
  [[pdf]](https://arxiv.org/pdf/2301.08496.pdf)
  - Hang Gao, Jiangmeng Li, Wenwen Qiang, Lingyu Si, Xingzhe Su1, Fengge wu, Changwen Zheng, and Fuchu Sun. *arXiv*, 2023.

- Causal Attention for Interpretable and Generalizable Graph Classification.
  [[pdf]](https://arxiv.org/pdf/2112.15089.pdf)
  [[code]](https://github.com/yongduosui/CAL)
  - Yongduo Sui, Xiang Wang, Jiancan Wu, Min Lin, Xiangnan He, and Tat-Seng Chua. *KDD*, 2022.

- Discovering Invariant Rationales for Graph Neural Networks.
  [[pdf]](https://openreview.net/pdf?id=hGXij5rfiHw)
  [[code]](https://github.com/Wuyxin/DIR-GNN)
  - Ying-Xin Wu, Xiang Wang, An Zhang, Xiangnan He, and Tat-Seng Chua. *ICLR*, 2022.

- Handling Distribution Shifts on Graphs: An Invariance Perspective.
  [[pdf]](https://openreview.net/pdf?id=FQOC5u-1egI)
  [[code]](https://github.com/qitianwu/GraphOOD-EERM)
  - Qitian Wu, Hengrui Zhang, Junchi Yan, and David Wipf. *ICLR*, 2022.

- Debiasing Graph Neural Networks via Learning Disentangled Causal Substructure.
  [[pdf]](https://arxiv.org/pdf/2209.14107.pdf)
  [[code]](https://github.com/googlebaba/DisC)
  - Shaohua Fan, Xiao Wang, Yanhu Mo, Chuan Shi, Jian Tang. *NeurIPS*, 2022.

- Learning Causally Invariant Representations for Out-of-Distribution Generalization on Graphs.
  [[pdf]](https://arxiv.org/pdf/2202.05441v3.pdf)
  [[code]](https://github.com/LFhase/CIGA)
  - Yongqiang Chen, Yonggang Zhang, Yatao Bian, Han Yang, Kaili Ma, Binghui Xie, Tongliang Liu, Bo Han, and James Cheng. *NeurIPS*, 2022.

- Dynamic graph neural networks under spatio-temporal distribution shift.
  [[pdf]](https://openreview.net/pdf?id=1tIUqrUuJxx)
  [[code]](https://github.com/wondergo2017/DIDA)
  - Zeyang Zhang, Xin Wang, Ziwei Zhang, Haoyang Li, Zhou Qin, and Wenwu Zhu. *NeurIPS*, 2022.

- Learning Substructure Invariance for Out-of-Distribution Molecular Representations.
  [[pdf]](https://openreview.net/pdf?id=2nWUNTnFijm)
  [[code]](https://github.com/yangnianzu0515/MoleOOD)
  - Nianzu Yang, Kaipeng Zeng, Qitian Wu, Xiaosong Jia, and Junchi Yan. *NeurIPS*, 2022.

- Learning Causally Invariant Representations for Out-of-Distribution Generalization on Graphs.
  [[pdf]](https://arxiv.org/pdf/2202.05441.pdf)
  [[code]](https://github.com/LFhase/CIGA)
  - Yongqiang Chen, Yonggang Zhang, Yatao Bian, Han Yang, Kaili Ma, and Binghui Xie. *NeurIPS*, 2022.

- Adversarial Causal Augmentation for Graph Covariate Shift.
  [[pdf]](https://arxiv.org/pdf/2211.02843.pdf)
  - Yongduo Sui, Xiang Wang, Jiancan Wu, An Zhang, and Xiangnan He. *arXiv*, 2022.

- Robust Causal Graph Representation Learning against Confounding Effects.
  [[pdf]](https://arxiv.org/pdf/2208.08584.pdf)
  - Hang Gao, Jiangmeng Li, Wenwen Qiang, Lingyu Si, Bing Xu, Changwen Zheng, and Fuchun Sun. *arXiv*, 2022.

### Contrastive Learning
- Let Invariant Rationale Discovery Inspire Graph Contrastive Learning.
  [[pdf]](https://proceedings.mlr.press/v162/li22v/li22v.pdf)
  [[code]](https://github.com/lsh0520/RGCL)
  - Sihang Li, Xiang Wang, An zhang, Yingxin Wu, Xiangnan He, and Tat-Seng Chua. *ICML*, 2022.

### Fairness
- FairEdit: Preserving Fairness in Graph Neural Networks through Greedy Graph Editing.
  [[pdf]](https://arxiv.org/pdf/2201.03681.pdf)
  [[code]](https://github.com/royull/FairEdit)
  - Donald Loveland, Jiayi Pan, Aaresh Farrokh Bhathena, and Yiyang Lu. *arXiv, 2022.

- VACA: Designing Variational Graph Autoencoders for Causal Queries.
  [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/download/20789/20548)
  [[code]](https://github.com/psanch21/VACA)
  - Pablo Sanchez-Martin, Miriam Rateike, and Isabel Valera. *AAAI*, 2022.

### Explanation
- Explaining GNN over Evolving Graphs using Information Flow.
  [[pdf]](https://arxiv.org/pdf/2111.10037.pdf)
  - Yazheng Liu, Xi Zhang, and Sihong Xie. *AAAI*, 2022.

- Orphicx: A causality-inspired latent variable model for interpreting graph neural networks.
  [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Lin_OrphicX_A_Causality-Inspired_Latent_Variable_Model_for_Interpreting_Graph_Neural_CVPR_2022_paper.pdf)
  [[code]](https://github.com/wanyugroup/cvpr2022-orphicx)
  - Wanyu Lin, Hao Lan, Hao Wang, and Baochun Li. *CVPR*, 2022.

- Reinforced Causal Explainer for Graph Neural Networks.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9763330&casa_token=9DbMc0tWMUEAAAAA:T8-jj7iyCoho6IertAUHY9oWPd-RNJSA0AYkbHA6r3NGbz1AMRAnF4ZcKH-wzBJnO84YJQ)
  [[code]](https://github.com/xiangwang1223/reinforced_causal_explainer)
  - Xiang Wang, Yingxin Wu, An Zhang, Fuli Feng, Xiangnan He, and Tat-Seng Chua. *IEEE Transactions on Pattern Analysis and Machine Intelligence*, 2022.

- Generative Causal Explanations for Graph Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2104.06643.pdf)
  [[code]](https://github.com/wanyu-lin/ICML2021-Gem)
  - Wanyu Lin, Hao Lan, and Baochun Li. *ICML*, 2021.

- ExplaiNE: An Approach for Explaining Network Embedding-based Link Predictions.
  [[pdf]](https://arxiv.org/pdf/1904.12694.pdf)
  - Bo Kang, Jefrey Lijffijt, and Tijl De Bie. *arXiv*, 2019.

### Recommendation
- Causality-based CTR prediction using graph neural networks.
  [[pdf]](https://www.sciencedirect.com/sdfe/reader/pii/S0306457322002382/pdf)
  - Panyu Zhai, Yanwu, Yang, and Chunjie Zhang. *Information Processing & Management*, 2023.

## Counterfactual Learning

### Counterfactual Fairness
- Learning Fair Node Representations with Graph Counterfactual Fairness.
  [[pdf]](https://arxiv.org/pdf/2201.03662.pdf)
  [[code]](https://github.com/jma712/GEAR)
  - Jing Ma, Ruocheng Guo, Mengting Wan, Longqi Yang, Aidong Zhang, and Jundong Li. *WSDM*, 2022.

- Towards a Unified Framework for Fair and Stable Graph Representation Learning.
  [[pdf]](https://proceedings.mlr.press/v161/agarwal21b/agarwal21b.pdf)
  [[code]](https://github.com/chirag126/nifty)
  - Chirag Agarwal, Himabindu Lakkaraju, and Marinka Zitnik. *UAI*, 2021.

- A Multi-view Confidence-calibrated Framework for Fair and Stable Graph Representation Learning.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9679093&casa_token=-YEdbpXuQYYAAAAA:XGpJ-yf6lXD8U9-smhmhom7IE7c_XhplHePMDolzZJ9BTxJThOptcaXIEIIEfhB6phfq2Q&tag=1)
  - Xu Zhang, Liang Zhang, Bo Jin, and Xinjiang Lu. *ICDM*, 2021.

- Fairness-Aware Node Representation Learning.
  [[pdf]](https://arxiv.org/pdf/2106.05391.pdf)
  - O. Deniz Kose, and Yanning Shen. *arXiv*, 2021.

### Counterfactual Explanation
- Global Counterfactual Explainer for Graph Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2210.11695.pdf)
  [[code]](https://github.com/mertkosan/GCFExplainer)
  - Mert Kosan, Zexi Huang, Sourav Medya, Sayan Ranu, and Ambuj Singh. *WSDM*, 2023.

- Model agnostic generation of counterfactual explanations for molecules.
  [[pdf]](https://pubs.rsc.org/en/content/articlehtml/2022/sc/d1sc05259d)
  [[code]](https://github.com/ur-whitelab/exmol)
  - Geemi P. Wellawatte, Aditi Seshadri, and Andrew D. White. *Chemical Science*, 2022.

- Ensemble approaches for Graph Counterfactual Explanations.
  [[pdf]](https://ceur-ws.org/Vol-3277/paper6.pdf)
  - Mario Alfonso Prado-Romero, Bardh Prenkaj, Giovanni Stilo, Alessandro Celi, Ernesto Estevanell-Valladares, and Daniel Alejandro Valdés-Pérez. *CEUR-WS*, 2022.

- GRETEL: A unified framework for Graph Counterfactual Explanation Evaluation.
  [[pdf]](https://arxiv.org/pdf/2206.02957.pdf)
  [[code]](https://github.com/MarioTheOne/GRETEL)
  - Mario Alfonso Prado-Romero, and Giovanni Stilo. *arXiv*, 2022.

- Learning and Evaluating Graph Neural Network Explanations based on Counterfactual and Factual Reasoning.
  [[pdf]](https://arxiv.org/pdf/2202.08816.pdf)
  [[code]](https://github.com/chrisjtan/gnn_cff)
  - Juntao Tan, Shijie Geng, Zuohui Fu, Yingqiang Ge, Shuyuan Xu, Yunqi Li, and Yongfeng Zhang. *WWW*, 2022.

- Flow-based counterfactuals for interpretable graph node classification.
  [[pdf]](https://www.mi.fu-berlin.de/inf/groups/ag-ki/Theses/Completed-theses/Bachelor-theses/2022/Ohly/thesis_ohly.pdf)
  - Lorenz Ohly. *Bachelar Disseration at Freie Universität Berlin*, 2022.

- Probing GNN Explainers: A Rigorous Theoretical and Empirical Analysis of GNN Explanation Methods.
  [[pdf]](https://arxiv.org/pdf/2106.09078.pdf)
  - Chirag Agarwal, Marinka Zitnik, and Himabindu Lakkaraju. *AISTATS*, 2022

- Preserve, Promote, or Attack? GNN Explanation via Topology Perturbation.
  [[pdf]](https://arxiv.org/pdf/2103.13944.pdf)
  - Yi Sun, Abel Valente, Sijia Liu, and Dakuo Wang. *arXiv*, 2021.

- CF-GNNExplainer: Counterfactual Explanations for Graph Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2102.03322.pdf)
  [[code]](https://github.com/a-lucic/cf-gnnexplainer)
  - Ana Lucic, Maartje ter Hoeve, Gabriele Tolomei, Maarten de Rijke, and Fabrizio Silvestri. *arXiv*, 2021.

- Robust Counterfactual Explanations on Graph Neural Networks.
  [[pdf]](https://proceedings.neurips.cc/paper/2021/file/2c8c3a57383c63caef6724343eb62257-Paper.pdf)
  [[code]](https://github.com/RomanOort/FACTAI)
  - Mohit Bajaj, Lingyang Chu, Zi Yu Xue, Jian Pei, Lanjun Wang, Peter Cho-Ho Lam, and Yong Zhang. *arXiv*, 2021.

- MEG: Generating Molecular Counterfactual Explanations for Deep Graph Networks.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9534266)
  [[code]](https://github.com/danilonumeroso/meg)
  - Danilo Numeroso, and Davide Bacciu. *IJCNN*, 2021.

- Counterfactual Graphs for Explainable Classification of Brain Networks.
  [[pdf]](https://arxiv.org/pdf/2106.08640.pdf)
  [[code]](https://github.com/carlo-abrate/CounterfactualGraphs)
  - Carlo Abrate, and Francesco Bonchi. *KDD*, 2021.


### Counterfactual Link Prediction and Recommendation
- Knowledge Graph Completion with Counterfactual Augmentation.
  [[pdf]](https://arxiv.org/pdf/2302.13083.pdf)
  - Heng Chang, Jie Cai, and Jia Li. *WWW*, 2023.

- Alleviating Spurious Correlations in Knowledge-aware Recommendations through Counterfactual Generator.
  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3477495.3531934?casa_token=ix1Lqmvze-UAAAAA:31ggoL-81DTGg3u7LJNvPgcWm5pboSKgFTwa_rJWQA0U1nmVanE44sE6zdoyL5Wdo9x2vZcYMaGUVw)
  [[code]](https://github.com/RUCAIBox/CGKR)
  - Shanlei Mu, Yaliang Li, Wayne Xin Zhao, Jingyuan Wang, Bolin Ding and Ji-Rong Wen. *SIGIR*, 2022.

- Learning from Counterfactual Links for Link Prediction.
  [[pdf]](https://arxiv.org/pdf/2106.02172.pdf)
  [[code]](https://github.com/DM2-ND/CFLP)
  - Tong Zhao, Gang Liu, Daheng Wang, Wenhao Yu, and Meng Jiang. *ICML*, 2022.

- GREASE: Generate Factual and Counterfactual Explanations for GNN-based Recommendations.
  [[pdf]](https://arxiv.org/pdf/2208.04222.pdf)
  - Ziheng Chen, Fabrizio Silvestri, Jia Wang, Yongfeng Zhang, Zhenhua Huang, Hongshik Ahn, and Gabriele Tolomei. *arXiv*, 2022.

- Clicks can be Cheating: Counterfactual Recommendation for Mitigating Clickbait Issue.
  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3404835.3462962)
  [[code]](https://github.com/WenjieWWJ/Clickbait/)
  - Wenjie Wang, Fuli Feng, Xiangnan He, Hanwang Zhang, and Tat-Seng Chua. *SIGIR*, 2021.

- Improving Location Recommendation with Urban Knowledge Graph.
  [[pdf]](https://arxiv.org/pdf/2111.01013.pdf)
  - Chang Liu, Chen Gao, Depeng Jin, and Yong Li. *arXiv*, 2021.

### Counterfactual Learning in Real-World Applications
- Counterfactual based reinforcement learning for graph neural networks.
  [[pdf]](https://link.springer.com/article/10.1007/s10479-022-04978-9)
  - David Pham, and Yongfeng Zhang. *Annals of Operations Research*, 2022.

- Deconfounding Physical Dynamics with Global Causal Relation and Confounder Transmission for Counterfactual Prediction.
  [[pdf]](https://www.aaai.org/AAAI22Papers/AAAI-3051.LiZ.pdf)
  - Zongzhao Li, Xiangyu Zhu, Zhen Lei1, and Zhaoxiang Zhang. *AAAI*, 2022.

- Counterfactual and Factual Reasoning over Hypergraphs for Interpretable Clinical Predictions on EHR.
  [[pdf]](https://proceedings.mlr.press/v193/xu22a/xu22a.pdf)
  - Ran Xu, Yue Yu, Chao Zhang, Mohammed K Ali, Joyce C Ho, and Carl Yang. *ML4H*, 2022.

- Capturing Molecular Interactions in Graph Neural Networks: A Case Study in Multi-Component Phase Equilibrium.
  [[pdf]](https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/626e8217ebac3a1603e9d3d0/original/capturing-molecular-interactions-in-graph-neural-networks-a-case-study-in-multi-component-phase-equilibrium.pdf)
  [[code]](https://github.com/zavalab/ML/tree/SolvGNN)
  - Shiyi Qin, Shengli Jiang, Jianping Li, Prasanna Balaprakash1, Reid C. Van Lehn, and Victor M. Zavala. *Chemrxiv*, 2022.

- Estimating counterfactual treatment outcomes over time in complex multi-agent scenarios.
  [[pdf]](https://arxiv.org/pdf/2206.01900.pdf)
  [[code]](https://github.com/TGV-CRN/TGV-CRN)
  - Keisuke Fujii, Koh Takeuchi, Atsushi Kuribayashi, Naoya Takeishi, Yoshinobu Kawahara, and Kazuya Takeda. *arXiv*, 2022.

- CausalGNN: Causal-based Graph Neural Networks for Spatio-Temporal Epidemic Forecasting.
  [[pdf]](https://www.aaai.org/AAAI22Papers/AISI-6475.WangL.pdf)
  - Lijing Wang, Aniruddha Adiga, Jiangzhuo Chen, Adam Sadilek, Srinivasan Venkatramanan, and Madhav Marathe. *AAAI*, 2022.

- Multivariate Time Series Forecasting with Transfer Entropy Graph.
  [[pdf]](https://arxiv.org/pdf/2005.01185.pdf)
  [[code]](https://github.com/RRRussell/CauGNN)
  - Ziheng Duan, Haoyan Xu, Yida Huang, Jie Feng, and Yueyang Wang. *arXiv*, 2021.

- Towards multi-modal causability with Graph Neural Networks enabling information fusion for explainable AI.
  [[pdf]](https://www.sciencedirect.com/science/article/pii/S1566253521000142)
  - Andreas Holzinger, Bernd Malle, Anna Saranti, and Bastian Pfeifer. *Information Fusion*, 2021.

- Counterfactual Supporting Facts Extraction for Explainable Medical Record Based Diagnosis with Graph Network.
  [[pdf]](https://aclanthology.org/2021.naacl-main.156.pdf)
  [[code]](https://github.com/CKRE/CMGE)
  - Haoran Wu, Wei Chen, Shuang Xu, and Bo Xu. *NAACL*, 2021.

- Multi-objective Explanations of GNN Predictions.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9679172)
  - Yifei Liu, Chao Chen, Yazheng Liu, Xi Zhang, and Sihong Xie. *ICDM*, 2021.

- Causal Discovery in Physical Systems from Videos.
  [[pdf]](https://arxiv.org/pdf/2007.00631.pdf)
  [[code]](https://github.com/pairlab/v-cdn)
  - Yunzhu Li, Antonio Torralba, Anima Anandkumar, Dieter Fox, and Animesh Garg. *NeurIPS*, 2020.

- Wireless Power Control via Counterfactual Optimization of Graph Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2002.07631.pdf)
  - Navid Naderializadeh, Mark Eisen, and Alejandro Ribeiro. *arXiv*, 2020.

- Counterfactual multi-agent reinforcement learning with graph convolution communication.
  [[pdf]](https://arxiv.org/pdf/2004.00470.pdf)
  - Jianyu Su, Stephen Adams, and Peter A. Beling. *arXiv*, 2020.

- Cophy: Counterfactual learning of physical dynamics.
  [[pdf]](https://arxiv.org/pdf/1909.12000.pdf)
  [[code]](https://projet.liris.cnrs.fr/cophy/)
  - Fabien Baradel, Natalia Neverova, Julien Mille, Greg Mori, and Christian Wolf. *arXiv*, 2019.

## Causal Discovery
- Relating Graph Neural Networks to Structural Causal Models.
  [[pdf]](https://128.84.4.13/pdf/2109.04173.pdf)
  [[code]](https://anonymous.4open.science/r/Relating-Graph-Neural-Networks-to-Structural-Causal-Models-A8EE/README.md)
  - Matej Zečević, Devendra Singh Dhami, Petar Veličković, and Kristian Kersting. *arXiv*, 2021.

- A Graph Autoencoder Approach to Causal Structure Learning.
  [[pdf]](https://arxiv.org/pdf/1911.07420.pdf)
  [[code]](https://github.com/huawei-noah/trustworthyAI)
  - Ignavier Ng, Shengyu Zhu, Zhitang Chen, and Zhuangyan Fang. *NeurIPS Workshop*, 2019.

- DAG-GNN: DAG Structure Learning with Graph Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1904.10098.pdf)
  [[code]](https://github.com/fishmoon1234/DAG-GNN)
  - Yue Yu, Jie Chen, Tian Gao, and Mo Yu. *ICML*, 2019.



## Causal Effect Estimate
- Causal Inference under Networked Interference and Intervention Policy Enhancement.
  [[pdf]](http://proceedings.mlr.press/v130/ma21c/ma21c.pdf)
  - Yunpu Ma, and Volker Tresp. *AISTATS*, 2021.

## Benchmark
- CausalBench: A Large-scale Benchmark for Network Inference from Single-cell Perturbation Data.
  [[pdf]](https://arxiv.org/pdf/2210.17283.pdf)
  [[code]](https://github.com/causalbench/causalbench)
  - Mathieu Chevalley, Yusuf Roohani, Arash Mehrjou, Jure Leskovec, and Patrick Schwab. *arXiv*, 2022.

- GOOD: A Graph Out-of-Distribution Benchmark.
  [[pdf]](https://arxiv.org/pdf/2206.08452.pdf)
  [[code]](https://github.com/divelab/GOOD/)
  - Shurui Gui, Xiner Li, Limei Wang, and Shuiwang Ji. *NeurIPS Track on Datasets and Benchmarks*, 2022.

## Application


## A Summary of Open-source Codes


