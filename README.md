# Arden-University-Assignment
This repository contains four analytical tasks completed as part of a numerical investigation project. The project combines linear algebra, calculus, probability, and statistical analysis to model and analyse population-related data.

---

Task 1 – Linear Algebra: Eigenvalues and Eigenvectors

A population transition matrix was analysed using linear algebra methods.

- Constructed the characteristic equation  
- Computed eigenvalues and eigenvectors  
- Interpreted long-term population behaviour  

Result:
- λ₁ ≈ 1.237  
- λ₂ ≈ 1.063  
- The dominant eigenvalue indicates long-term population growth.

---

Task 2 – Calculus: Exponential Population Growth Model

The population of Paris was modelled using an exponential function:

\[
P(t) = 1000e^{0.03t}
\]

Steps included:
- Differentiating the function to find growth rate  
- Evaluating population and growth over 20 years  
- Determining the maximum growth rate  

Result:
- Population at t = 20 ≈ 1822  
- Maximum growth rate ≈ 54.7 per year
  
---

Task 3 – Probability: Poisson Immigration Model

Immigration events were modelled using a Poisson distribution with parameter:

\[
\lambda = 5
\]

Computed:
- Expected value  
- Variance  
- Standard deviation  

Result:
- E[X] = 5  
- Var(X) = 5  
- SD ≈ 2.236  

---

Task 4 – Statistical Analysis: 95% Confidence Interval

Using population data from 8 districts:

- Calculated sample mean  
- Computed sample standard deviation (with Bessel’s correction)  
- Used t-distribution (df = 7)  
- Constructed a 95% confidence interval  

Result:
- Sample mean ≈ 1064.38  
- 95% Confidence Interval: (1054.27, 1074.48)

---

Technologies Used

- Python  
- NumPy  
- SciPy  
- Jupyter Notebook
