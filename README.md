# Credit_Risk

## Abstract
The SIFMA estimates $105.9T of debt outstanding across the globe (CAGR of 2.89% over 2017-2019). Market volatility has been unprecedented (i.e. the S&P 500 dropping 30% in 4 weeks) in 2020, outperforming the historic market-crashes of 1929, 1987, and 2007. Government bond yields decreased from a record high in late 2018, eventually hitting a record low in March 2020 (i.e. investors anxious and prioritizing liquid assets). Major takeaway: investors will probably prioritize less volatile investment vehicles until the economy stabilized.

Peer-to-peer lending institutions are growing in popularity and market size, accordingly. Due to the global shelter-in-place orders, consumers have grown more reliant on digital-based products and services. Peer-to-peer lending companies typically operate online, resulting in lower overhead (i.e. services are more convenient and cheaper than incumbent financial institutions).

## Objective
There is a need for all lending institutions to mitigate credit risk, in times of crisis and prosperity. There is a need for mechanisms that easily and accurately predict whether a loan applicant is a high or low risk.

## Introduction to Analysis
I will be using a logistic regression model to solve this binary classification problem.

This is innately an imbalanced classification problem; more people pay back their loans than not. And similarly, there will be more applicants marked as low risk compared to high risk. To combat this I will be using imbalanced oversampling and undersampling methods (ClusterCentroids, SMOTE, and Naive Random Oversampling). 
