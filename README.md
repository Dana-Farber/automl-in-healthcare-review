# AutoML in Healthcare Review
Automated machine learning: Review of the state-of-the-art and opportunities for healthcare

Selected highlights from the 2020 AutoML Review [https://doi.org/10.1016/j.artmed.2020.101822] that reviewed over **2,160 works related to the field of automated machine learning**. 

## The curated list of automated feature engineering tools for Automated Machine Learning
More at https://doi.org/10.1016/j.artmed.2020.101822
| Method                  | Work                                                                                                                                                                                                                | Feature Engineering Technique | Used by how many works |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|---------------------------------------|
| Deep Feature Synthesis  | [LINK](https://dai.lids.mit.edu/wp-content/uploads/2017/10/DSAA_DSM_2015.pdf)                                                                                                                                      | Expand-Reduce                 | 151                                   |
| Explore Kit             | [LINK](http://people.eecs.berkeley.edu/~dawnsong/papers/icdm-2016.pdf)                                                                                                                                               | Expand-Reduce                 | 53                                    |
| One Button Machine      | [LINK](https://arxiv.org/pdf/1706.00327.pdf)                                                                                                                                                                         | Expand-Reduce                 | 32                                    |
| AutoLearn               | [LINK](http://web2py.iiit.ac.in/research_centres/publications/download/inproceedings.pdf.88535e0ea3a74e72.4943444d2d20323031372e706466.pdf)                                                                          | Expand-Reduce                 | 16                                    |
| GP Feature Construction | [LINK](https://homepages.ecs.vuw.ac.nz/~xuebing/Papers/GPFCFSmemeticComputing.pdf)                                                                                                                                   | Genetic Programming           | 68                                    |
| Cognito                 | [LINK](https://ieeexplore.ieee.org/abstract/document/7836821)                                                                                                                                                        | Hierarchical Greedy Search    | 38                                    |
| RLFE                    | [LINK](https://arxiv.org/pdf/1709.07150.pdf)                                                                                                                                                                         | Reinforcement Learning        | 21                                    |
| LFE                     | [LINK](https://www.researchgate.net/profile/Udayan_Khurana/publication/318829821_Learning_Feature_Engineering_for_Classification/links/5a13e08a0f7e9b1e5730a735/Learning-Feature-Engineering-for-Classification.pdf) | Meta-Learning                 | 34                                    |


## AutoML pipeline optimizers
More at https://doi.org/10.1016/j.artmed.2020.101822
| Method                    | Work                                                                                                           | Optimization Algorithm                               | Data Pre-Processing | Feature Engineering | Model Selection    | Hyperparameter Optimization | Ensemble Learning  | Meta-Learning      | Used by how many works |
|---------------------------|-----------------------------------------------------------------------------------------------------------------|------------------------------------------------------|---------------------|---------------------|--------------------|-----------------------------|--------------------|--------------------|---------------------------------------|
| Auto-Weka                 | [LINK](https://arxiv.org/pdf/1208.3719.pdf)                                                                     | Bayesian Optimization (SMAC)                         | :heavy_check_mark:  |                     | :heavy_check_mark: | :heavy_check_mark:          |                    |                    | 703                                   |
| Auto-Sklearn              | [LINK](http://papers.nips.cc/paper/5872-efficient-and-robust-automated-machine-learning.pdf)                    | Joint Bayesian Optimization and Bandit Search (BOHB) | :heavy_check_mark:  |                     | :heavy_check_mark: | :heavy_check_mark:          | :heavy_check_mark: | :heavy_check_mark: | 542                                   |
| TPOT                      | [LINK](https://arxiv.org/pdf/1601.07925.pdf)                                                                    | Evolutionary Algorithm                               | :heavy_check_mark:  | :heavy_check_mark:  | :heavy_check_mark: | :heavy_check_mark:          |                    |                    | 84                                    |
| TuPAQ                     | [LINK](https://thisisdhaas.com/papers/SOCC2015TuPAQ.pdf)                                                        | Bandit Search                                        |                     |                     | :heavy_check_mark: | :heavy_check_mark:          |                    |                    | 94                                    |
| ATM                       | [LINK](http://www.thswear.com/files/SwearingenEtAl-ATM-BigData2017.pdf)                                         | Joint Bayesian Optimization and Bandit Search        |                     | :heavy_check_mark:  |                    | :heavy_check_mark:          |                    | :heavy_check_mark: | 29                                    |
| Automatic Frankensteining | [LINK](https://www.ismll.uni-hildesheim.de/pub/pdfs/wistuba_et_al_SDM_2017.pdf)                                 | Bayesian Optimization                                |                     |                     | :heavy_check_mark: | :heavy_check_mark:          | :heavy_check_mark: |                    | 12                                    |
| ML-Plan                   | [LINK](https://link.springer.com/article/10.1007/s10994-018-5735-z)                                             | Hierarchical Task Networks (HTN)                     | :heavy_check_mark:  |                     | :heavy_check_mark: | :heavy_check_mark:          |                    |                    | 24                                    |
| Autostacker               | [LINK](https://arxiv.org/pdf/1803.00684.pdf)                                                                    | Evolutionary Algorithm                               |                     |                     | :heavy_check_mark: | :heavy_check_mark:          | :heavy_check_mark: |                    | 18                                    |
| AlphaD3M                  | [LINK](https://www.cs.columbia.edu/~idrori/AlphaD3M.pdf)                                                        | Reinforcement Learning/Monte Carlo Tree Search       | :heavy_check_mark:  |                     | :heavy_check_mark: | :heavy_check_mark:          |                    |                    | 8                                     |
| Collaborative Filtering   | [LINK](https://papers.nips.cc/paper/7595-probabilistic-matrix-factorization-for-automated-machine-learning.pdf) | Probabilistic Matrix Factorization                   | :heavy_check_mark:  |                     | :heavy_check_mark: | :heavy_check_mark:          |                    | :heavy_check_mark: | 29                                    |

## Neural Architecture Search algorithms, based on performance on the CIFAR-10 dataset
More at https://doi.org/10.1016/j.artmed.2020.101822
| NAS Algorithm           | Work                                                                                                                                             | Search Space            | Search Strategy                             | Performance Estimation Strategy              | Number of Parameters | Search Time (GPU-days) | Test Error (%) |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------------------------------|----------------------------------------------|----------------------|------------------------|----------------|
| Large-scale Evolution   | [LINK](https://arxiv.org/pdf/1703.01041.pdf)                                                                                                      | Feed-Forward Networks   | Evolutionary Algorithm                      | Naive Training and Validation                | 5.4M                 | 2600                   | 5.4            |
| EAS                     | [LINK](https://arxiv.org/pdf/1707.04873.pdf)                                                                                                      | Feed-Forward Networks   | Reinforcement Learning and Network Morphism | Short Training and Validation                | 23.4M                | 10                     | 4.23           |
| Hierarchical Evolution  | [LINK](https://arxiv.org/pdf/1711.00436.pdf)                                                                                                      | Cell Motifs             | Evolutionary Algorithm                      | Training and Validation on proposed CNN Cell | 15.7M                | 300                    | 3.75           |
| NAS v3                  | [LINK](https://arxiv.org/pdf/1611.01578.pdf)                                                                                                      | Multi-branched Networks | Reinforcement Learning                      | Naive Training and Validation                | 37.4M                | 22400                  | 3.65           |
| PNAS                    | [LINK](https://openaccess.thecvf.com/content_ECCV_2018/papers/Chenxi_Liu_Progressive_Neural_Architecture_ECCV_2018_paper.pdf)                     | Cell Motifs             | Sequential Model-Based Optimization (SMBO)  | Performance Prediction                       | 3.2M                 | 225                    | 3.41           |
| ENAS                    | [LINK](https://arxiv.org/pdf/1802.03268.pdf)                                                                                                      | Cell Motifs             | Reinforcement Learning                      | One Shot                                     | 4.6M                 | 0.45                   | 2.89           |
| ResNet + Regularization | [LINK](https://arxiv.org/pdf/1705.07485.pdf)                                                                                                      | HUMAN BASELINE          | HUMAN BASELINE                              | HUMAN BASELINE                               | 26.2M                | -                      | 2.86           |
| DARTS                   | [LINK](https://arxiv.org/pdf/1806.09055.pdf)                                                                                                      | Cell Motifs             | Gradient-Based Optimization                 | Training and Validation on proposed CNN Cell | 3.4M                 | 4                      | 2.83           |
| NASNet-A                | [LINK](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zoph_Learning_Transferable_Architectures_CVPR_2018_paper.pdf)                       | Cell Motifs             | Reinforcement Learning                      | Naive Training and Validation                | 3.3M                 | 2000                   | 2.65           |
| EENA                    | [LINK](https://openaccess.thecvf.com/content_ICCVW_2019/papers/NeurArch/Zhu_EENA_Efficient_Evolution_of_Neural_Architecture_ICCVW_2019_paper.pdf) | Cell Motifs             | Evolutionary Algorithm                      | Performance Prediction                       | 8.5M                 | 0.65                   | 2.56           |
| Path-Level EAS          | [LINK](https://arxiv.org/pdf/1806.02639.pdf)                                                                                                      | Cell Motifs             | Reinforcement Learning                      | Short Training and Validation                | 14.3M                | 200                    | 2.30           |
| NAO                     | [LINK](http://papers.nips.cc/paper/8007-neural-architecture-optimization.pdf)                                                                     | Cell Motifs             | Gradient-Based Optimization                 | Performance Prediction                       | 128M                 | 200                    | 2.11           |
