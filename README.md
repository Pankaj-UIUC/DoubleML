# DoubleML
In this repo, I have shared examples of **Double Machine Learning (DML)**, a modern causal inference method that combines machine learning with econometric theory to estimate causal effects from observational data.

In observational studies, we want to estimate the causal effect of a treatment (D) on an outcome (Y), but we have many confounders (X) that affect both. 

**Traditional approaches struggle when:**
- We have many confounders (high-dimensional X)
- The relationships are non-linear
- We want to use flexible ML methods but still get valid inference

- **DML solves this by:**
- Using ML to flexibly control for confounders
- Maintaining valid statistical inference (confidence intervals, p-values)
- Avoiding regularization bias through orthogonalization

