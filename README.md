# Graduation-Project

Abstract

The main goal of this project is to figure out what really is important for multi-class text
classification. Normally, there are many steps that are assumed to be important to solve this
problem, such as text pre-processing, feature engineering, choosing proper algorithms, and
hyper-parameters tuning. So, I have tried to make clear the importance of each step for the
modeling performance. To achieve this goal, I collected the raw review data from the web,
which contains 250K reviews from 5,000 TV-series, and sub-sampled 38,000 reviews. The
tasks are mainly two parts. The first one is a feature-based approach that includes detailed
feature engineering, such as extracting features from the texts. The other one is to simply run
a latest deep learning model with basic pre-processing and the fine tuning of the algorithm.
And I compared the performance of those two different ways to figure out a reliable method
for text multi-classification. In addition, Bayesian Optimization was deployed for hyperparameters
tuning, which was meaningful for the Support Vector Machine. As a result, both
approaches gave very similar results whose accuracies are all about 48%. But a noticeable
result is that their predictions are very different from each other, and when ensembling these
models, the accuracy increased from 48% to 53%. This implies that ensembling both ways can
result in much better result than simply using one approach.

