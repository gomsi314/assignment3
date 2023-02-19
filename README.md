# assignment3

# Comparing Sampling Techniques for 5 Machine Learning Models

## Introduction

This project aims to investigate the efficacy of various sampling techniques for generating a balanced dataset to train a machine learning model. The original dataset is imbalanced, thus, random over-sampling and under-sampling methods are employed to balance it. After achieving a balanced dataset, five distinct sampling techniques are implemented and the resulting samples are evaluated for accuracy using five different machine learning models.

## Sampling Techniques

1.Simple Random Sampling: A statistical technique where a sample is selected randomly from a given population, with each element in the population having an equal chance of being selected.

2.Stratified Sampling: A method of sampling where a population is divided into mutually exclusive strata based on a specific characteristic, and a random sample is drawn from each stratum in proportion to the size of the stratum.

3.Systematic Sampling: A type of sampling where a sample is selected by following a specific pattern, such as selecting every nth element in the population, where n is a fixed interval.

4.Cluster Sampling: A sampling technique where the population is divided into clusters or groups, and a random sample of the clusters is selected. All members of the selected clusters are included in the sample.

5.Convenience Sampling: A non-probability sampling technique where participants are selected based on their accessibility and availability to the researcher. This method is often considered less rigorous than probability sampling methods, as it may introduce bias and limit generalizability.

## Comparison Table

The table below shows the accuracies of each sampling technique on five different machine learning models. The dataset used for all models is a balanced version of the original unbalanced dataset using random over-sampling and under-sampling techniques.

| Sampling Technique | Decision Tree | SVM | Logistic Resgression | KNN | Naive Bayes |
|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Simple Random Sampling | **0.9778** | 0.8954 | 0.8917 | 0.8915 | 0.7275 |
| Systematic Sampling | 0.9813 | 0.8989 | 0.9213 | 0.9493 | 0.6855 |
| Stratified Sampling | 0.9851 | 0.8937 | 0.9217 | 0.9497 | 0.6891 |
| Cluster Sampling | **0.9868** | 0.9000 | 0.9081 | 0.9691 | 0.9234 |
| Convenience Sampling | 0.9849 | 0.9190 | 0.9322 | 0.9623 | 0.7740 |

Based on these results, it can be concluded that Cluster Sampling performs the best on all five models. Simple random sampling performs the worst on all five models. The other sampling techniques have varying performance depending on the model. The model which gives the best accuracy for all 5 samples is Decision Tree.

## Conclusion

It is recommended to use cluster sampling for this dataset, as it consistently gives the best performance across all models. However, other sampling techniques may be worth considering for different datasets or models.
 
