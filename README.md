# fractional_maxpooling
paper link : https://arxiv.org/pdf/1412.6071.pdf
# Introduction
In this project, we use fractional maxpooling to prevent overfitting, which is introduced in the paper above, and compare it with classical maxpooling using CIFAR10 dataset, which is a popular regularizer to prevent overfitting. In conclusion, the results of maxpooling performs better, maybe classical maxpooling is enough for regularization.
# Compare result
method | train loss | train accuracy | validation loss | validation accuracy | test accuracy
---|---|---|---|---|---
fractional maxpooling | 0.4173 | 0.8526 | **0.9990** | 0.6928 | 0.7026
maxpooling            | **0.1654** | **0.9444** | 1.0622 | **0.7211** | **0.7184**

# Summary
In this paper, they achevied state-of-the-art result, but in my model structure, it perfromed similar to maxpooling, one can try both method and check which bring you a better validation accuracy.
