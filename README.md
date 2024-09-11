# Customer Segmentation Using Hierarchical Clustering | Politecnico di Milano, Italy

This project focuses on **customer segmentation** using a mix of clustering techniques to uncover distinct customer profiles from a dataset with **17 covariates** (11 numerical and 6 categorical).

## Table of Contents
- [Project Overview](#project-overview)
- [Techniques Used](#techniques-used)
- [Customer Segments](#customer-segments)
- [Results](#results)
- [Conclusion](#conclusion)

## Project Overview
In this project, we conducted an exploratory analysis on customer data to identify meaningful clusters. The key focus was to analyze both numerical and categorical data to segment customers into distinct groups. We used **Hierarchical Clustering** for primary segmentation and **Self-Organizing Maps (SOM)** as a validation step to ensure consistency in the groupings.

## Techniques Used
- **Exploratory Data Analysis (EDA)**:
  - Investigated numerical and categorical features such as 'Income' and 'Wealth'.
  - Detected and handled outliers using **Isolation Forest**, hypothesizing that 1% of data points may be outliers.

- **Hierarchical Clustering**:
  - **Gower Distance** was used for mixed data types.
  - **Ward Linkage** was employed for clustering.
  - Clusters were cut at 5 groups to capture distinctive customer behaviors.

- **Self-Organizing Maps (SOM)**:
  - A basic 2x2 lattice grid was used as a final check to verify if SOM could capture patterns similar to hierarchical clustering.

## Customer Segments
### Group 1 & 4: Office Workers with Families
- **Average Age**: 60 years
- **Key Traits**: Standard income, wealth, and larger family sizes. Groups 1 and 4 differ mainly in investment approaches.

### Group 2: Retired Couples
- **Average Age**: 78 years
- **Key Traits**: Low debt, retired individuals with stable financial profiles.

### Group 3: Wealthy Managers
- **Average Age**: 50 years
- **Key Traits**: High income, high financial education, and higher debts, likely manageable due to their wealth.

### Group 5: Young Nurses
- **Average Age**: 32 years
- **Key Traits**: Mostly female, young professionals with decent incomes.

## Results
- **Hierarchical Clustering** identified 5 clear customer groups based on income, wealth, family size, and investment tendencies.
- **SOM Validation** showed similar groupings to the hierarchical method, reinforcing the robustness of the clusters.

## Conclusion
This project demonstrates how businesses can leverage advanced clustering techniques to segment their customers into meaningful profiles. By understanding customer behavior, companies can tailor their strategies to target specific customer needs and improve overall engagement.
