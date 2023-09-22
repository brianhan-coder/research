# Ling Han
## [Home](https://www.linghan.me/)  ~  [CV](https://www.linghan.me/CV)  ~   [Publications](https://www.linghan.me/publications)  ~  Research  ~   [Contact Me](https://www.linghan.me/CM)

![image](https://media.licdn.com/dms/image/D4E16AQE1yfMF2smlXQ/profile-displaybackgroundimage-shrink_200_800/0/1675223891394?e=2147483647&v=beta&t=tLcv_ZBtOCTg1dWgEMtLO69RGPGF7ZGLJw6d7HZlYfk)

## Selected Research Projects

### Online Scheduling of Distributed Machine Learning Jobs for Incentivizing Sharing in Multi-Tenant Systems

To save cost, companies usually train machine learning (ML) models on a shared multi-tenant system. In this cooperative environment, one of the fundamental challenges is how to distribute resources fairly among tenants such that each tenant is satisfied. A satisfactory allocation policy needs to meet the following properties. First, the performance of each tenant in the shared cluster is at least the same as that in its exclusive cluster partition. Second, no tenant can get more benefits by lying about its demands. Third, tenants cannot use the idle resources of others for free. Moreover, the resource allocation for ML workloads should avoid costly migration overhead. To this end, we propose a three-layer scheduling framework Astraea: i) a batch scheduling framework groups unprocessed ML jobs into multiple batches; ii) a round-by-round algorithm enables tenants to reserve their share of resources and schedule ML jobs in a non-preemptive manner; iii) one-round algorithm based on the primal-dual approach and posted pricing framework, which encourages tenants to report truthful demands and computes a schedule with maximal revenue for each ML job. Besides, our algorithm also allows tenants to trade unused resources on a paid basis. Astraea is proven to achieve performance guarantee, polynomial time complexity and some desirable properties of resource sharing, including batch sharing incentive, strategy- proofness, Pareto efficiency and gain-as-you-contribute fairness. Extensive trace-driven simulations show that our algorithm advances in both fairness and cluster efficiency by at least 20% compared to three state-of-the-art baselines. <br>

<img src="https://s2.loli.net/2023/04/23/CUx9pVfG4dqnlsi.png" width='610px'><img src="https://s2.loli.net/2023/04/23/fpAEHm6DCsdglcx.png" width='355px'> 

### Statistical Estimation of Diffusion Network Topologies

Reconstructing the topology of a diffusion network based on observed diffusion results is an open challenge in data mining. Existing approaches mostly assume that the observed diffusion results are available and consist of not only the final infection statuses of nodes, but also the exact timestamps that pinpoint when infections occur. Nonetheless, the exact infection timestamps are often unavailable in practice, due to a high cost and uncertainties in the monitoring of node infections. In this work, we investigate the problem of how to infer the topology of a diffusion network from only the final infection statuses of nodes. To this end, we propose a new scoring criterion for diffusion network reconstruction, which is able to estimate the likelihood of potential topologies of the objective diffusion network based on infection status results with a relatively low statistical error. As the proposed scoring criterion is decomposable, our problem is transformed into finding for each node in the network a set of most probable parent nodes that maximizes the value of a local score. Furthermore, to eliminate redundant computations during the search of most probable parent nodes, we identify insignificant candidate parent nodes by checking whether their infections have negative or extremely low positive correlations with the infections of a corresponding child node, and exclude them from the search space. Extensive experiments on both synthetic and real-world networks are conducted, and the results verify the effectiveness and efficiency of our approach.

<img src="https://s2.loli.net/2023/04/23/1gDGJlsqe93vEC8.png" width='265px'> <img src="https://s2.loli.net/2023/04/23/xQydWVA1wfkBrZn.png" width='690px'>
