# Causal Model Learning with Non-Commutative Polynomial Optimization

Welcome to the repository for causal learning benchmark funded by CoDiet(https://www.codiet.eu/)! This codebase encompasses notebooks and test results associated with each figure in the paper Causal Learning Benchmarking Dataset Based on Krebs Cycle(https://arxiv.org/html/2406.15189).
    
## Causal Learning Process ##
1. **Generate Data:** Use the `IIDSimulation` function in `Generate Data.py` to create artificial true causal graphs and observation data.
2. **Learn Structure:** Uncover the causal structure beneath the observation data.
3. **Visualize Comparison:** Generate heat maps to compare estimated and true graphs.
4. **Calculate Metrics:** Assess the performance metrics.
5. **Demonstrate in Heatmap:** Illustrate results in a heatmap for multiple datasets.

![ANM-NCPOP](/images/Picture-anmncpop.png)

## Test data


## Methods
This variety enables a comprehensive comparison of different causal discovery algorithms from GCastle package, ExDBN, ExMAG and ANM-NCPOLR. 

## Plots
To systematically compare the performance of causal discovery algorithms on biochemical pathway data, we evaluated 14 representative methods across four major methodological categories in Figure Circle_Barplot. Performance was evaluated on both the original and normalised versions of the \textit{Krebs3} dataset. This comprehensive benchmarking highlights variability in method robustness to data normalisation and facilitates category-level insights into algorithmic behaviour.

For the \textit{Krebs3} dataset, Figure Barplot illustrates the comparison of different representative causal discovery algorithms using the percentage error across various performance measures. 

## Running Notebooks
- **ANCPOP_test.ipynb:** Execute this notebook for all experiments on Krebs3 and KrebN data using the 21 approach. Upload datasets and the notebook to [Colab](https://colab.research.google.com/) for seamless execution.

## Installation
To run experiments locally, ensure you have the dependencies in the requirements.txt installed.


