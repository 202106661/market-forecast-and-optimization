# S&P 500 Stock Prediction & Portfolio Optimization

## About the Project
This repository contains an academic project focused on predicting stock prices from the S&P 500 index and optimizing an investment portfolio. We utilized various Machine Learning models, ran Monte Carlo simulations to forecast volatility and growth, and implemented a Genetic Algorithm to construct a robust portfolio that balances expected returns and risks.

## Key Features
* **Machine Learning Predictive Models:** Training and evaluation of Random Forest, XGBoost, and Support Vector Regression (SVR) to forecast stock behavior.
* **Hyperparameter Tuning:** Optimization of model performance using `RandomizedSearchCV`.
* **Monte Carlo Simulations:** Forecasting scenarios of market volatility and growth based on the fine-tuned model predictions.
* **Genetic Algorithm for Optimization:** Constructing a diversified portfolio (across 42 companies) that adheres to budget constraints and prioritizes high expected returns with lower risk.
* **Performance Metrics:** Models evaluated using RMSE, MAE, and MASE for both validation and test datasets.

## Repository Structure
* `finalmaybe.ipynb`: The main Jupyter Notebook containing all the code for data processing, model training, simulations, and the genetic algorithm.
* `model_evaluation_results.csv`: Raw evaluation metrics for the baseline models.
* `model_evaluation_with_random_search.csv`: Evaluation metrics and best parameters found after hyperparameter tuning.
* `Implicações Éticas.pdf`: Original document (in Portuguese) detailing the legal and ethical considerations of the project.

## Ethical & Legal Disclaimer
**Educational Purposes Only:** This project was developed strictly for academic and research purposes. The results and predictions presented here **must not** be interpreted as financial advice, investment recommendations, or guarantees of financial return. 

**Data Usage & Market Integrity:** * Data was sourced from public and widely recognized platforms (Yahoo Finance, Alpha Vantage) and is used respecting their non-commercial licensing terms.
* We strongly condemn unethical market practices such as "pump and dump" or "spoofing." This model is designed with transparency and ethical standards in mind, aligning with European guidelines (MiFID II) and local regulations (CMVM).

## Authors
* Ana Catarina Fernandes Ribeiro
* Estefany Andreina Camacho Vasconcelos
* Gabriela Simon de Cenço
* Noa Cajila Fraga dos Santos
