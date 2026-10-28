# SML-2-LAB

Lab work for **ED408: Statistical Machine Learning II Lab**.

**Name:** Priyanshi Agarwal  
**Roll No:** IED/10006/23  

---

## Repository Contents

### Module I: Overview of Machine Learning Techniques

| File | Question | Description |
|------|----------|-------------|
| [`Module_1/q1 (2).ipynb`](Module_1/q1%20(2).ipynb) | Q1 | k-Nearest Neighbours (k-NN) classifier implemented from scratch (NumPy), tested for k = 1, 3, 5, 7, 9 |
| [`Module_1/q2.ipynb`](Module_1/q2.ipynb) | Q2 | Decision Tree classifier using scikit-learn, with tree visualization |
| [`Module_1/q3.ipynb`](Module_1/q3.ipynb) | Q3 | Naive Bayes classifier for spam vs. ham detection |
| [`Module_1/q4.ipynb`](Module_1/q4.ipynb) | Q4 | Logistic Regression from scratch using gradient descent |
| [`Module_1/Q5.py`](Module_1/Q5.py) | Q5 | PCA and t-SNE to reduce image data to 2D and visualize clusters |
| [`Module_1/q6.ipynb`](Module_1/q6.ipynb) | Q6 | Outlier detection and treatment using z-score and IQR methods |
| [`Module_1/q7.ipynb`](Module_1/q7.ipynb) | Q7 | Comparison of Logistic Regression and SVM using accuracy, precision, recall, F1-score and ROC-AUC |

---

### Module II: Metaheuristic Optimization & Machine Learning Algorithms

All algorithms are implemented **100% from scratch** (pure Python & NumPy, without high-level optimization/ML libraries) using **real-world empirical economic datasets** (USMacroG real quarterly macroeconomic database from the Federal Reserve & Greene Econometric Analysis, and real Indian commercial logistics networks). Each experiment includes a fully executed Jupyter Notebook (`.ipynb`), complete File Keeping documentation (`.docx`) adhering strictly to the lab format, and raw real data in `data/`.

| Experiment Folder | Question | Notebook | Documentation | Dataset (`data/`) | Description |
|-------------------|----------|----------|---------------|-------------------|-------------|
| `Module_2/Experiment_08_Simulated_Annealing` | Q8 | [`Simulated_Annealing_Economic.ipynb`](Module_2/Experiment_08_Simulated_Annealing/Simulated_Annealing_Economic.ipynb) | [`Documentation_Experiment_08.docx`](Module_2/Experiment_08_Simulated_Annealing/Documentation_Experiment_08.docx) | [`real_macro_asset_returns.csv`](Module_2/Experiment_08_Simulated_Annealing/data/real_macro_asset_returns.csv) | Simulated Annealing from scratch for non-convex function optimization ($f(x) = x^2 + 10\sin(x)$) and real macroeconomic capital asset allocation (Investment, Consumption, Govt, M1, T-Bills) under transaction friction. |
| `Module_2/Experiment_09_Genetic_Algorithm_TSP` | Q9 | [`Genetic_Algorithm_TSP.ipynb`](Module_2/Experiment_09_Genetic_Algorithm_TSP/Genetic_Algorithm_TSP.ipynb) | [`Documentation_Experiment_09.docx`](Module_2/Experiment_09_Genetic_Algorithm_TSP/Documentation_Experiment_09.docx) | [`real_economic_trade_hubs.csv`](Module_2/Experiment_09_Genetic_Algorithm_TSP/data/real_economic_trade_hubs.csv) | Genetic Algorithm from scratch using Order Crossover (OX), Swap Mutation, and Elitism for solving the Traveling Salesman Problem across 10 real major Indian commercial trade capitals with full pairwise distance matrix. |
| `Module_2/Experiment_10_Particle_Swarm_Optimization` | Q10 | [`Particle_Swarm_Optimization.ipynb`](Module_2/Experiment_10_Particle_Swarm_Optimization/Particle_Swarm_Optimization.ipynb) | [`Documentation_Experiment_10.docx`](Module_2/Experiment_10_Particle_Swarm_Optimization/Documentation_Experiment_10.docx) | [`real_macro_production_data.csv`](Module_2/Experiment_10_Particle_Swarm_Optimization/data/real_macro_production_data.csv) | Particle Swarm Optimization (PSO) from scratch for minimizing the Rosenbrock banana function and fitting non-linear capital-labor macroeconomic production cost frontiers. |
| `Module_2/Experiment_11_Regularization_L1_L2_ElasticNet` | Q11 | [`Regularization_L1_L2_ElasticNet.ipynb`](Module_2/Experiment_11_Regularization_L1_L2_ElasticNet/Regularization_L1_L2_ElasticNet.ipynb) | [`Documentation_Experiment_11.docx`](Module_2/Experiment_11_Regularization_L1_L2_ElasticNet/Documentation_Experiment_11.docx) | [`real_macroeconomic_data.csv`](Module_2/Experiment_11_Regularization_L1_L2_ElasticNet/data/real_macroeconomic_data.csv) | Ridge ($L_2$), Lasso ($L_1$), and Elastic Net regularized regression from scratch using Coordinate Descent and Soft-Thresholding on 203 real quarters of macroeconomic data predicting GDP. |
| `Module_2/Experiment_12_Kernel_PCA` | Q12 | [`Kernel_PCA_Nonlinear.ipynb`](Module_2/Experiment_12_Kernel_PCA/Kernel_PCA_Nonlinear.ipynb) | [`Documentation_Experiment_12.docx`](Module_2/Experiment_12_Kernel_PCA/Documentation_Experiment_12.docx) | [`real_macro_regimes.csv`](Module_2/Experiment_12_Kernel_PCA/data/real_macro_regimes.csv) | Kernel Principal Component Analysis (Kernel PCA) from scratch with RBF Mercer kernel and Gram matrix centering for separating non-linear macroeconomic business cycle regimes (Inflation vs Unemployment). |
| `Module_2/Experiment_13_Ant_Colony_Optimization` | Q13 | [`Ant_Colony_Optimization.ipynb`](Module_2/Experiment_13_Ant_Colony_Optimization/Ant_Colony_Optimization.ipynb) | [`Documentation_Experiment_13.docx`](Module_2/Experiment_13_Ant_Colony_Optimization/Documentation_Experiment_13.docx) | [`real_freight_corridor.csv`](Module_2/Experiment_13_Ant_Colony_Optimization/data/real_freight_corridor.csv) | Ant Colony Optimization (ACO) from scratch for discovering optimal freight corridors and shortest paths across the real national trade logistics corridor connecting Delhi NCR to Mumbai JNPT. |

---

## Requirements

- Python 3.8+
- numpy, pandas, matplotlib
- python-docx
- Jupyter Notebook

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/Priyanshiag1/SML-2-LAB.git
cd SML-2-LAB
```

2. Open any Jupyter Notebook:
```bash
jupyter notebook Module_2/Experiment_11_Regularization_L1_L2_ElasticNet/Regularization_L1_L2_ElasticNet.ipynb
```
Each notebook contains complete mathematical formulations, scratch implementations, real empirical datasets, convergence tracking, and embedded high-resolution visualizations.
