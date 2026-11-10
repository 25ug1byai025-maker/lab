# PROBABILITY AND STATISTICS FOR MACHINE LEARNING
## 1BMATAI301 | Discrete & Continuous Probability Distributions

**Academic Project | Artificial Intelligence and Machine Learning | Semester III**

---

## 1. Project Overview

This repository contains interactive web-based applications developed as part of the undergraduate laboratory coursework for Probability and Statistics for Machine Learning.

The project focuses on implementing and understanding probability distributions through mathematical computations, parameter-based calculations, statistical measures, and graphical visualizations.

The applications allow students to modify input parameters, calculate probability values, examine distribution patterns, and interpret the results through practical examples related to quality control, monitoring systems, and engineering applications.

The project covers both **discrete and continuous probability distributions**, connecting theoretical statistical concepts with practical programming implementation.

## 2. Project Objectives

- Understand the mathematical foundations of probability distributions.
- Implement probability models using JavaScript.
- Perform calculations using Probability Mass Functions (PMF) and Cumulative Distribution Functions (CDF).
- Compute statistical measures such as mean, variance, and standard deviation.
- Visualize probability distributions through interactive graphs.
- Study the influence of changing parameters on probability outcomes.
- Apply statistical concepts to practical engineering and machine learning scenarios.

## 3. Modules and Features

### A. Discrete Probability Distributions

Implemented in `index1.html`.

This application provides interactive calculators for three discrete probability distributions.

**1. Binomial Distribution**

Models the number of successes in a fixed number of independent trials.

Features:
- Input parameters: Number of trials (n), success probability (p), and required outcome (k).
- Calculation of PMF and CDF.
- Calculation of complementary probability P(X > k).
- Statistical measures: Mean, variance, standard deviation, second moment, and skewness.
- Graphical representation of the probability distribution.
- Visualization of the mean using a reference line.

**2. Poisson Distribution**

Models the number of events occurring within a specified interval at a known average rate.

Features:
- Input parameter: Average event rate (λ).
- Calculation of exact and cumulative probabilities.
- Calculation of complementary probability.
- Statistical measures and probability distribution visualization.
- Comparison of distributions for different λ values.

**3. Geometric Distribution**

Models the number of independent trials required to obtain the first success.

Features:
- Input parameters: Success probability (p) and trial number (k).
- Calculation of exact probability P(X = k).
- Calculation of cumulative and upper-tail probabilities.
- Statistical measures including mean, variance, standard deviation, second moment, and skewness.
- Comparison of probabilities for the first, second, and third attempts.

### B. Continuous Probability Distributions

Implemented in `probability_distributions_interactive_app.html`.

This application focuses on continuous probability models and their engineering applications.

**1. Normal Distribution**

Provides an interactive probability solver using the mean (μ) and standard deviation (σ).

Features:
- Calculation of probabilities between two values.
- Calculation of probabilities below or above a specified value.
- Calculation of probabilities outside a given interval.
- Conversion of observations into Z-scores.
- Step-by-step solutions using the Z-table method.
- Graphical representation of the normal curve and probability regions.

**2. Exponential Distribution**

Models the waiting time between consecutive events under a constant-rate Poisson process.

Features:
- Input of arrival rate (λ) and time intervals.
- Calculation of cumulative and survival probabilities.
- Calculation of mean and variance.
- Conditional probability calculations.
- Visualization of the exponential probability density curve.

**3. Manufacturing Quality Control**

Applies the normal distribution to a shaft-diameter quality-control problem.

Features:
- Input of target diameter and process mean.
- Input of process variance and specification limits.
- Calculation of standard deviation.
- Probability of products falling within acceptable limits.
- Probability of measurements falling below or above specification limits.
- Estimation of the expected defective percentage.
- Graphical visualization of acceptable and defective regions.

## 4. Mathematical Concepts

The applications demonstrate the following probability models.

### Discrete Distributions

**Binomial Distribution**

For X ~ Binomial(n, p):

- PMF: P(X = k) = C(n,k) pᵏ (1-p)ⁿ⁻ᵏ
- Mean: E[X] = np
- Variance: Var(X) = np(1-p)
- Standard deviation: σ = √(np(1-p))

**Poisson Distribution**

For X ~ Poisson(λ):

- PMF: P(X = k) = (e⁻λ λᵏ) / k!
- Mean: E[X] = λ
- Variance: Var(X) = λ

**Geometric Distribution**

For X representing the trial number on which the first success occurs:

- PMF: P(X = k) = (1-p)ᵏ⁻¹ p
- Mean: E[X] = 1/p
- Variance: Var(X) = (1-p)/p²

### Continuous Distributions

**Normal Distribution**

For X ~ N(μ, σ²):

- Standardization: Z = (X-μ)/σ
- Probability between two values: P(a ≤ X ≤ b) = Φ(zᵦ) - Φ(zₐ)

**Exponential Distribution**

For an exponential random variable with rate λ:

- Probability density: f(t) = λe⁻λᵗ, t ≥ 0
- Cumulative probability: P(T ≤ t) = 1-e⁻λᵗ
- Survival probability: P(T > t) = e⁻λᵗ
- Mean: E[T] = 1/λ
- Variance: Var(T) = 1/λ²

## 5. Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure and content of the applications |
| CSS3 | Styling, layouts, and responsive design |
| JavaScript | Probability calculations, input validation, and interactive functionality |
| HTML Canvas API | Graphical representation of discrete distributions |
| SVG | Rendering continuous probability curves |
| Jupyter Notebook | Laboratory exercises and programming practice |
| Git and GitHub | Version control and source-code management |
| Visual Studio Code | Development environment |

## 6. Repository Structure

The repository contains the following files:

```text
lab/
│
├── index1.html(Binomial,Posson,Geometric distributions)
│
├── index2.html(Normal and exponential distributions)
│
├── Lab_Pgm_1_Exercise_Qs.ipynb
│
├── Untitled0.ipynb
│
├── Untitled1.ipynb
│
├── PROBABILITY AND STATISTICS FOR MACHINE LEARNING.docx
│
└── README.md
```

### File Description

| File | Description |
|---|---|
| `index1.html` | Interactive application for Binomial, Poisson, and Geometric distributions. |
| `index2.html` | Application for Normal and Exponential distributions and manufacturing quality control. |
| `Lab_Pgm_1_Exercise_Qs.ipynb` | Jupyter Notebook for laboratory exercise questions. |
| `Untitled0.ipynb` | Additional Jupyter Notebook included in the repository. |
| `Untitled1.ipynb` | Additional Jupyter Notebook included in the repository. |
| `PROBABILITY AND STATISTICS FOR MACHINE LEARNING.docx` | Subject-related academic document. |
| `README.md` | Project documentation and usage instructions. |

## 7. Installation and Execution

The web applications are standalone HTML files and do not require a backend server or package installation.

**Prerequisites**

- A modern web browser (Google Chrome, Microsoft Edge, or Firefox).
- Visual Studio Code (recommended).
- Live Server extension (optional).

**Steps to run the project**

1. Clone the repository:

```bash
git clone https://github.com/25ug1byai025-maker/lab.git
```

2. Navigate to the project directory:

```bash
cd lab
```

3. Open the project folder in Visual Studio Code.

4. Select the required HTML application:
   - `index1.html` for discrete distributions.
   - `probability_distributions_interactive_app.html` for continuous distributions.

5. Open the selected file in a web browser or use the Live Server extension.

6. Enter the required parameters and explore the calculations, results, and graphical representations.

## 8. Laboratory Applications

The project demonstrates the use of probability distributions through practical examples.

| Application | Probability Model | Practical Context |
|---|---|---|
| Defect-count analysis | Binomial | Product quality inspection |
| Event-count analysis | Poisson | Alert and monitoring systems |
| First-success analysis | Geometric | Defect detection and repeated attempts |
| Measurement analysis | Normal | Manufacturing and dimensional quality control |
| Waiting-time analysis | Exponential | Cloud request inter-arrival times |

These examples help demonstrate how different probability models can be selected according to the nature of a random experiment.

## 9. Learning Outcomes

Through the development and use of these applications, the project provides practical exposure to:

- Understanding discrete and continuous random variables.
- Implementing mathematical probability formulas programmatically.
- Applying statistical concepts to real-world engineering examples.
- Developing interactive web applications using HTML, CSS, and JavaScript.
- Validating input parameters and handling calculation constraints.
- Interpreting probability graphs and statistical results.
- Connecting probability and statistics with applications in Artificial Intelligence and Machine Learning.

## 10. Limitations and Future Enhancements

The project is developed primarily for academic learning and experimentation.

Potential future improvements include:

- Adding more probability distributions and statistical models.
- Providing additional worked examples with detailed mathematical explanations.
- Improving graph interaction and visualization.
- Adding downloadable calculation reports.
- Expanding laboratory exercises and practical case studies.
- Improving accessibility and responsive functionality.

## 11. Academic Information

| Particular | Details |
|---|---|
| Subject | Probability and Statistics for Machine Learning |
| Subject Code | 1BMATAI301 |
| Project Title | Discrete and Continuous Probability Distributions |
| Department | Artificial Intelligence and Machine Learning |
| Semester | III |
| Project Type | Undergraduate Laboratory Project |
| Implementation | Web-Based Interactive Applications |
| Repository | [GitHub – lab](https://github.com/25ug1byai025-maker/lab) |

---

**Academic Project**

Developed as part of the undergraduate laboratory coursework to explore the mathematical and computational aspects of probability distributions.

*Learning through mathematical implementation, interactive experimentation, and graphical analysis.*
