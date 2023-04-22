# Ling Han
## [Home](https://www.linghan.me/)  ~  [CV](https://www.linghan.me/CV)  ~   [Publications](https://www.linghan.me/publications)  ~  Research  ~   [Contact Me](https://www.linghan.me/CM)

![image](https://media.licdn.com/dms/image/D4E16AQE1yfMF2smlXQ/profile-displaybackgroundimage-shrink_350_1400/0/1675223891394?e=1686787200&v=beta&t=FgGDpYDjS6rv2OGMv84hxZu2VUO50I2lFjx47hqY7pc)

## Selected Research Projects

### Online Scheduling of Distributed Machine Learning Jobs for Incentivizing Sharing in Multi-Tenant Systems

To save cost, companies usually train machine learning (ML) models on a shared multi-tenant system. In this cooperative environment, one of the fundamental challenges is how to distribute resources fairly among tenants such that each tenant is satisfied. A satisfactory allocation policy needs to meet the following properties. First, the performance of each tenant in the shared cluster is at least the same as that in its exclusive cluster partition. Second, no tenant can get more benefits by lying about its demands. Third, tenants cannot use the idle resources of others for free. Moreover, the resource allocation for ML workloads should avoid costly migration overhead. To this end, we propose a three-layer scheduling framework Astraea: i) a batch scheduling framework groups unprocessed ML jobs into multiple batches; ii) a round-by-round algorithm enables tenants to reserve their share of resources and schedule ML jobs in a non-preemptive manner; iii) one-round algorithm based on the primal-dual approach and posted pricing framework, which encourages tenants to report truthful demands and computes a schedule with maximal revenue for each ML job. Besides, our algorithm also allows tenants to trade unused resources on a paid basis. Astraea is proven to achieve performance guarantee, polynomial time complexity and some desirable properties of resource sharing, including batch sharing incentive, strategy- proofness, Pareto efficiency and gain-as-you-contribute fairness. Extensive trace-driven simulations show that our algorithm advances in both fairness and cluster efficiency by at least 20% compared to three state-of-the-art baselines. <br>

![Screen Shot 2023-04-22 at 12.59.39 PM.png](https://s2.loli.net/2023/04/23/fpAEHm6DCsdglcx.png)
