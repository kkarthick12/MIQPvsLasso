# MIQPvsLasso
Explore the effectiveness of MIQP vs. LASSO in regression variable selection. This project examines precision and computational efficiency, incorporating cross-validation and data analysis to innovate predictive analytics.

# Non-Linear Programming for Variable Selection in Regression Analysis

## Project Overview

This project explores an innovative approach to variable selection in regression analysis by comparing the efficacy of Mixed Integer Quadratic Programming (MIQP) against the established LASSO regression method. With advancements in optimization technologies, this research seeks to evaluate the potential of MIQP to enhance predictive analytics.

## Objectives

- To challenge conventional reliance on LASSO and ridge regression for variable selection.
- To assess the computational and predictive performance of MIQP in regression scenarios.

## Methodology

- **Data Preprocessing:** Initial analysis and preparation of training and test datasets.
- **Tools:** Python (Gurobi, Scikit-learn)
- **Model Development:**
  - Implementation of MIQP for direct variable selection.
  - Application of LASSO regression for comparison.
- **Evaluation:** Utilization of cross-validation techniques to tune hyperparameters and evaluate model performance on unseen data.

## Key Findings

- **MIQP vs. LASSO:**
  - MIQP demonstrates potential for precise variable selection, potentially leading to improved prediction accuracy.
  - LASSO provides computational efficiency and robustness through shrinkage, which can prevent overfitting.
- **Computational Considerations:**
  - Despite higher computational demands, MIQP offers a viable alternative for scenarios where model precision is paramount.
  - The choice between MIQP and LASSO should be guided by project-specific requirements, balancing computational resources against predictive performance.

## Conclusion

This study highlights the importance of considering advanced optimization techniques like MIQP in the realm of predictive analytics. While LASSO remains a valuable tool for its efficiency and simplicity, MIQP offers a complementary strategy that may yield superior outcomes in certain contexts.

## Recommendations

- Further research to explore the scalability of MIQP in larger datasets.
- Development of guidelines for selecting between MIQP and LASSO based on analytical objectives and resource availability.

