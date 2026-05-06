# Adaptive Learning-Based Mutation Prioritization (ALMP)

## Project Overview
Adaptive Learning-Based Mutation Prioritization (ALMP) is a framework that improves mutation testing efficiency in MuTAP-style workflows by using machine learning to prioritize high-value mutants. Instead of treating all mutants equally, ALMP ranks and processes those with higher predicted impact first. This helps improve mutation testing effectiveness while reducing unnecessary computational and token costs.

## Setup Instructions
Install the required Python libraries:

```bash
pip install lizard tiktoken scikit-learn matplotlib pandas
```

## How to Run
1. Open ALMP_Framework.ipynb in Google Colab or Jupyter Lab.
2. Run all cells from top to bottom.

## Key Results
- ALMP achieved a 75% mutation score compared with 25% for the baseline/random strategy in the benchmark scenario.
- This demonstrates the practical benefit of ML-based prioritization in improving test effectiveness under similar processing budgets.

## Key Features
- Feature Importance Analysis using the trained model to explain which mutant characteristics most influence prioritization.
- Efficiency Benchmarks comparing ALMP against a baseline workflow, including mutation score, token usage, and cost-efficiency metrics.
