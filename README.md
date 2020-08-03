

# Awesome-RecSys-Fairness (in progress)

Collect some papers and dataset related to fairness research in recommendation systems.

## Paper

### Fairness

Notation: `G` - Group Fairness, `I` - Individual Fairness

| Title                                                        | Published   | Side     | Fairness                 | Approach        | Resources                                                    |
| ------------------------------------------------------------ | ----------- | -------- | ------------------------ | --------------- | ------------------------------------------------------------ |
| Beyond Parity: Fairness Objectives for Collaborative Filtering | NIPS 2017   | Customer | G - Equal Opportunity    | In-processing   | [[pdf](http://papers.nips.cc/paper/6885-beyond-parity-fairness-objectives-for-collaborative-filtering.pdf)] |
| Balanced Neighborhoods for Multi-sided Fairness in Recommendation | FACCT ’2018 | Multi    | G - Neighborhood balance | In-processing   | [[pdf](http://proceedings.mlr.press/v81/burke18a/burke18a.pdf)] |
| Equity of Attention: Amortizing Individual Fairness in Rankings | SIGIR ’18   | Producer | I - Equity of attention  | Post-processing | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3209978.3210063)]  |
| Fairness of Exposure in Rankings                             | KDD ’18     | Producer | G                        | Post-processing | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3219819.3220088)]  |
| Personalizing Fairness-aware Re-ranking                      | FATREC ’18  | Producer | I - diversity            | Post-processing | [[pdf](https://arxiv.org/pdf/1809.02921)]                    |
| Fairness-Aware Ranking in Search & Recommendation Systems with Application to LinkedIn Talent Search | KDD ’19     | Producer | G - Desired Distribution | Post-processing | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3292500.3330691)]  |
| Addressing the Target Customer Distortion Problem in Recommender Systems | WWW ’20     | Customer | G - Desired Distribution | Post-processing | [[pdf](https://pdfs.semanticscholar.org/595c/f88b30953170e8c58edd746afa7cdc976e93.pdf)] |
| FairRec: Two-Sided Fairness for Personalized Recommendations in Two-Sided Platforms | WWW ’20     | Multi    | I - EF, MMS              | Post-processing | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3366423.3380196)] [[code](https://github.com/gourabkumarpatro/FairRec_www_2020)] |
| Controlling Fairness and Bias in Dynamic Learning-to-Rank    | SIGIR ’20   | Producer | G - Equity of attention  | Post-processing | [[pdf](https://arxiv.org/pdf/2005.14713.pdf)] [[code](https://github.com/MarcoMorik/Dynamic-Fairness)] |

### Bias

| Title                                                        | Published | Bias     | Resources                                                   |
| ------------------------------------------------------------ | --------- | -------- | ----------------------------------------------------------- |
| Unbiased Learning-to-Rank with Biased Feedback               | WSDM ’17  | Position | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3018661.3018699)] |
| Estimating Position Bias without Intrusive Interventions     | WSDM ’19  | Position | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3289600.3291017)] |
| Intervention Harvesting for Context-Dependent Examination-Bias Estimation | SIGIR ’19 | Position | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3331184.3331238)] |

### Survey

- A Survey on Bias and Fairness in Machine Learning, 2019 [[pdf](https://arxiv.org/pdf/1908.09635)]

## Dataset

- https://github.com/caserec/Datasets-for-Recommender-Systems
- https://github.com/daicoolb/RecommenderSystem-DataSet
- https://cseweb.ucsd.edu/~jmcauley/datasets.html
- https://lionbridge.ai/datasets/24-best-ecommerce-retail-datasets-for-machine-learning/
- https://shuaizhang.tech/posts/2019/08/blog-post-3/