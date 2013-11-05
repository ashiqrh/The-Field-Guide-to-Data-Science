##Feature Selection Case Study -- Cancer Cell Classification
*Author: Paul Yacci*

On one project, our team was challenged to classify cancer cell profiles. The overarching goal was to classify different types of Leukemia, based on Microarray profiles from 72 samples[15] using a small set of features. We utilized a hybrid Artificial Neural Network (ANN)[16] and Genetic Algorithm[17] to identify subsets of 10 features selected from thousands.[18] We trained the ANN and tested performance using cross-fold validation. The performance measure was used as feedback into the Genetic Algorithm. When a set of features containing no useful information, the model performed poorly and a different feature set would be explored. Over time, this method selected a set of features that performed with high accuracy. The down-selected feature set increased speed and performance as well as allowed for better insight into the factors that may govern the system. This allowed our team to design a diagnostic test for only a few genetic markers instead of thousands, substantially reducing diagnostic test complexity and cost.