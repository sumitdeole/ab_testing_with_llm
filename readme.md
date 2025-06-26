# A/B Testing Framework for E-commerce

## Overview
Robust experimental framework for Zalando-style conversion rate optimization. The code will test and store important metrics and plots and then use LLM model (Mistral via Ollama) to interprete the results and generate executive report.

Features:
- Bias detection (SRM, duration checks)
- Multiple testing approaches (Frequentist, Bayesian, CUPED)
- Heterogeneous treatment effects
- Business impact simulations
- Executive reporting

## Key Features
✅ _Data Quality Checks_  
✅ _Statistical Robustness Validation_  
✅ _Business Impact Forecasting_  
✅ _Causal Inference Techniques_  
✅ _Automated Executive Reporting using LLM_

## How to Use
# Run analysis
python src/ab_test_analysis.py \
  --data_path data/ab_test.csv \
  --daily_users 75000 \
  --aov 89.99 \
  --alpha 0.05