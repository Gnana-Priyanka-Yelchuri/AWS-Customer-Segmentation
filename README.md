# Customer Segmentation Using AWS

## Overview

This project implements a cloud-native customer segmentation pipeline using AWS services and machine learning techniques.

The Online Retail II dataset was processed using Amazon SageMaker, stored in Amazon S3, secured through IAM roles, and analyzed using RFM (Recency, Frequency, Monetary) feature engineering and K-Means clustering.

The resulting customer segments were visualized in Power BI to support business decision-making and targeted marketing strategies.

## Technologies Used

- AWS S3
- AWS IAM
- Amazon SageMaker
- Python
- Pandas
- Scikit-Learn
- K-Means Clustering
- Power BI

## Project Workflow

1. Upload raw dataset to Amazon S3
2. Configure IAM roles and permissions
3. Perform data preprocessing in SageMaker
4. Build RFM features
5. Scale features using StandardScaler
6. Determine optimal clusters using Elbow Method
7. Apply K-Means clustering
8. Export results to S3
9. Visualize customer segments in Power BI

## Key Features

- Cloud-native implementation
- Secure AWS architecture
- Customer segmentation using machine learning
- RFM analysis
- K-Means clustering
- Power BI dashboarding

## Business Value

The project identifies customer groups such as high-value customers, frequent buyers, occasional buyers, and at-risk customers, helping businesses improve marketing efficiency and customer retention.
