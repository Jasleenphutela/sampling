# INTRODUCTION
Sampling is the process of selecting a subset of individuals or units from a population to estimate characteristics of the entire population. There are several different types of sampling methods, each with its own advantages and disadvantages. Here are brief explanations of five common sampling methods:

Simple random sampling: In simple random sampling, each member of the population has an equal chance of being selected for the sample. This method is easy to understand and implement, but it may not be representative if the population is not homogeneous.
Stratified sampling: Stratified sampling involves dividing the population into strata (subgroups) and then selecting a random sample from each stratum. This method ensures that each subgroup is represented in the sample, and it can improve the representativeness of the sample.
Systematic sampling: In systematic sampling, the population is ordered, and then every nth member of the population is selected for the sample. This method is easy to use and is more efficient than simple random sampling, but it may introduce bias if there is a pattern in the population.
Cluster sampling: Cluster sampling involves dividing the population into clusters (groups), and then randomly selecting a subset of clusters for the sample. This method is efficient and cost-effective, but it may introduce bias if the clusters are not representative of the population.
Convenience sampling: Convenience sampling involves selecting individuals who are easy to access or who volunteer to participate in the study. This method is quick and easy, but it may not be representative of the population, as those who participate may differ from those who do not.

# Comparison Table

The table below shows the accuracies of each sampling technique on five different machine learning models. The dataset used for all models is a balanced version of the original unbalanced dataset using random over-sampling and under-sampling techniques.

| Sampling Technique | Decision Tree | SVM | Logistic Resgression | KNN | Naive Bayes |
|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Simple Random Sampling | 0.9778 | 0.8954 | 0.8917 | 0.8915 | 0.7275 |
| Systematic Sampling | 0.9813 | 0.8989 | 0.9213 | 0.9493 | 0.6854 |
| Stratified Sampling | 0.9851 | 0.8937 | 0.9217 | 0.9498 | 0.6890 |
| Cluster Sampling | **0.9868** | 0.9000 | 0.9088 | 0.9691 | 0.9235 |
| Convenience Sampling | 0.9849 | 0.9190 | 0.9322 | 0.9623 | 0.7740 |
AS WE CAN SEE,CLUSTER SAMPLING IS GIVING BETTER RESULTS AMONG THESE SAMPLING TECHNIQUES
