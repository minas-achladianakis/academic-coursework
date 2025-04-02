# 🧮 Computational Statistics – Graduate Coursework

This section contains structured assignments from a graduate-level course on **Computational Statistics**. Topics covered include Monte Carlo estimation techniques, resampling methods, cross-validation, and practical tools for simulation-based inference.

---

## 📘 Assignment Summaries

### 📄 Assignment 1 – Monte Carlo Estimation (Uploaded as PDF)
📎 [View PDF](./M.C.S.Assignment_1.pdf)

**Topics Covered:**
- **Estimation of expectations** using Monte Carlo simulation
- Simple Monte Carlo vs. **importance sampling** approaches
- Bias–variance decomposition and interpretation
- Convergence behavior of stochastic estimators
- **Bootstrapping** for estimator variability and confidence intervals
- **Bagging** (bootstrap aggregation) to reduce prediction variance
- **10-fold cross-validation** for performance evaluation of predictive models

---

### 📄 Assignment 2 – Model Diagnostics & Variable Selection
📎 [View PDF](./M.C.S.Assignment_2.pdf)

**Topics Covered:**
- **Residual diagnostics** and **regression assumption checking**
- **Box-Cox** transformations for response normalization
- Simulation of **multicollinearity** via noise-injected predictors
- Variable selection via stepwise selection **(F-test, AIC, BIC)**
- Penalized regression methods: **LASSO and Ridge**
- **Prediction error metrics**: RMSE, MAE, MAPE
- **20-fold cross-validation** for robust model comparison
- **Tofallis criterion** for accuracy assessment
- Statistical evaluation via **Wilcoxon** paired tests

---

### 📄 Assignment 3 – Adaptive LAD LASSO and Model Comparison
📎 [View PDF](./M.C.S.Assignment_3.pdf)

This assignment builds on earlier work using the airquality dataset, focusing on adaptive LASSO methods, quantile regression, and robust model comparison strategies. It deeply explores model selection, performance metrics, and confidence interval estimation using bootstrapping, offering insight into both practical model implementation and theoretical robustness.

**Topics Covered:**
- Adaptive **LAD LASSO** via rqPen, hqreg, and glmnet R packages
- **Coefficient stability** analysis across lambda sequences
- Use of **AIC-based backward selection** in quantile regression
- In-depth **bootstrapping** for coefficient and interval estimation
- Implementation of **10-fold Cross-Validation** for MAE comparison

---

### 📄 Assignment 4 – MSE Comparison & Bootstrap Confidence Intervals (Uploaded as PDF)
📎 [View PDF](./M.C.S.Assignment_4.pdf)

**Topics Covered:**
- Definition and implementation of test **MSE as a performance measure**
- Construction of **confidence intervals** using the **non-parametric bootstrap**
- Design of a **Monte Carlo experiment** to compare model robustness
- Implementation of **quantile regression** (LAD) and OLS under heteroskedasticity
- Evaluation of bias, variance, and RMSE in predictive modeling
- Use of robust regression metrics under noise-induced model distortion
- Visualization of model performance distributions across replicates

---

## 🧠 Core Techniques Across All Assignments

- Monte Carlo simulation and approximation
- Importance sampling
- Bootstrapping (non-parametric resampling for CIs and error estimation)
- Bagging (ensemble method)
- Cross-validation (10-fold, 20-fold, and custom splits)
- Adaptive and penalized regression (LASSO, LASSO variants, Ridge, Ridge variants)
- Quantile regression (LAD models)
- Model selection and diagnostics
- Posterior expectation and predictive distribution estimation
- Bias–variance trade-offs in estimators
- Variable transformation (e.g., Box-Cox)
- Model diagnostics: AIC, BIC, CV error, MAE, LCH, MAPE, MSE
- Confidence interval estimation using bootstrap methods
- Predictive accuracy evaluation (Tofallis criterion, RMSE, MAE, MAPE)
- Statistical comparison of models (Wilcoxon signed-rank test, error distribution plots)
- Noise simulation and robustness testing in regression models

> ⚠️ *Note:* Some assignments build on earlier ones but remain individually self-contained.

---


📌 **Disclaimer & Sharing Policy**

This work has been uploaded as a protected PDF due to its close alignment with ongoing coursework at the University of Crete. It is intended to support understanding, peer learning, and academic growth for fellow students and readers — not for direct reuse or copy-paste into active assignments.

If you are a researcher, educator, or student interested in the underlying LaTeX source code, R/Python scripts, or extended materials for non-evaluative or collaborative purposes, feel free to reach out. I’d be happy to share the raw files upon reasonable and specific request.
