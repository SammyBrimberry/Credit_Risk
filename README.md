# Credit_Risk

## Abstract
The SIFMA estimates $105.9T of debt outstanding across the globe (CAGR of 2.89% over 2017-2019). Market volitiality has been unprecedented (i.e. the S&P 500 dropping 30% in 4 weeks) in 2020, out performing the historic market-crashes of 1929, 1987 and 2007. Government bond yields decresed from a record high in late 2018, eventually hitting a record low in March 2020 (i.e. investors anxious and prioritizing liquid assets). Major takeaway: it is probable that investors will prioritize less volitile investment vehicicles until the economy stabalized.

Peer-to-peer lending institutions are growing in popularity and market size, accordingly. Due to the global shelter-in-place orrders, consumers have grown more relliant to digital based products and services. Peer-to-peer lending companies typically opperate online, resulting in lower overhead (i.e. services are more convinent and cheaper than incumbent financial institutions).

## Objective
There is a need for all lending institutions to mitigate credit risk, in times of crisis and prosperity. There is a need for mechanisms that easily and accuratley predict whether a loan applicant is high or low risk.

## Introduction to Analysis
I will be using a logistic regression model to solve this bianrary classification problem.

This is innatly an imbalanced classification problem; there are more people who pay back their loans than not. And similarly there will be more applicants marked as low risk compaired to high risk. In order to combat this I will be using imbalanced oversampling and undersampling methods (ClusterCentroids, SMOTE and Naive Random Oversampling). 
