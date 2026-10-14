# PROBABILITY AND STATISTICS FOR MACHINE LEARNING - 1BMATAI301
# Discrete Probability Distributions

**An Interactive Web Application for AIML Laboratory Learning**

A simple, interactive web application developed as part of an undergraduate Artificial Intelligence and Machine Learning (AIML) laboratory. The application helps students explore discrete probability distributions through mathematical calculations, user inputs, and graphical visualizations.

## 📌 Project Overview

Probability distributions are an important part of statistics, data analysis, and machine learning. This project demonstrates how probability concepts can be implemented using web technologies.

Students can modify distribution parameters, calculate probabilities, observe graphical patterns, and understand how different input values affect the results.

## 🎯 Objectives

- Understand the fundamentals of discrete probability distributions.
- Implement probability formulas using JavaScript.
- Calculate statistical measures and probability values.
- Visualize probability distributions using interactive graphs.
- Connect mathematical concepts with practical programming applications.

## ✨ Features

### 1. Binomial Distribution

- Input the number of trials (\(n\)) and probability of success (\(p\)).
- Calculate mean, variance, standard deviation, second moment, and skewness.
- Calculate exact probability using the Probability Mass Function (PMF).
- Calculate cumulative probability using the Cumulative Distribution Function (CDF).
- Display complementary probability, \(P(X>k)\).
- Visualize the probability distribution using a bar chart.
- View probability values using interactive graph tooltips.

### 2. Poisson Distribution

- Set the average event rate (\(\lambda\)).
- Calculate the mean and variance.
- Calculate exact and cumulative probabilities.
- Visualize the Poisson probability mass function.
- Compare distributions for \(\lambda=2\), \(\lambda=6\), and \(\lambda=10\).

### 3. Geometric Distribution

The Geometric Distribution section is included in the navigation as a placeholder for future development.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structures the web application |
| CSS3 | Provides styling and responsive layouts |
| JavaScript | Performs probability calculations and handles interactions |
| HTML Canvas API | Draws probability distribution graphs |
| Jupyter Notebook | Supports laboratory exercises and programming practice |
| GitHub | Stores and manages the project source code |

## 📐 Mathematical Concepts

### Binomial Distribution

For a random variable \(X\sim\operatorname{Binomial}(n,p)\):

| Measure | Formula |
|---|---|
| Mean | \(E[X]=np\) |
| Variance | \(\operatorname{Var}(X)=np(1-p)\) |
| Standard deviation | \(\sqrt{np(1-p)}\) |
| Second moment | \(E[X^2]=\operatorname{Var}(X)+(E[X])^2\) |
| Skewness | \(\frac{1-2p}{\sqrt{np(1-p)}}\) |
| PMF | \(P(X=k)=\binom{n}{k}p^k(1-p)^{n-k}\) |

### Poisson Distribution

For a random variable \(X\sim\operatorname{Poisson}(\lambda)\):

| Measure | Formula |
|---|---|
| Mean | \(E[X]=\lambda\) |
| Variance | \(\operatorname{Var}(X)=\lambda\) |
| PMF | \(P(X=k)=\frac{e^{-\lambda}\lambda^k}{k!}\) |
| CDF | \(P(X\leq k)=\sum_{i=0}^{k}P(X=i)\) |

## 🚀 Getting Started

### Prerequisites

- A modern web browser, such as Google Chrome, Microsoft Edge, or Firefox.
- Visual Studio Code (recommended).
- Live Server extension (optional).

### Run the Application Locally

**Step 1: Clone the repository**

```bash
git clone https://github.com/25ug1byai025-maker/lab.git
```

**Step 2: Open the project folder**

```bash
cd lab
```

**Step 3: Launch the application**

Open the folder in Visual Studio Code and open `index.html`.

You can either:

- Open `index.html` directly in your web browser, or
- Right-click the file and select **Open with Live Server**.

**Step 4: Explore the application**

Use the navigation menu to open the available sections. Change the input parameters, calculate probabilities, and observe the graphs.

No backend server or database is required to run the standalone web application.

## 🧪 Laboratory Exercises

### Exercise 1 — Interactive Binomial Distribution

Set the following parameters:

- Number of trials: \(n=15\)
- Probability of success: \(p=0.6\)

Determine:

1. Mean and variance.
2. Probability of exactly nine successes, \(P(X=9)\).
3. Probability of at most ten successes, \(P(X\leq10)\).
4. The region with the highest probability in the PMF graph.
5. A brief inference based on the visualization.

### Exercise 2 — Interactive Poisson Distribution

Consider an AI-based monitoring system with an average event rate of \(\lambda=6\).

Determine:

1. Mean and variance.
2. Probability of exactly eight events, \(P(X=8)\).
3. Probability of at most five events, \(P(X\leq5)\).
4. Compare the graphs for \(\lambda=2\), \(6\), and \(10\).
5. Explain how increasing the average event rate affects the distribution.

## 📂 Project Structure

```text
lab/
├── index.html
├── Lab_Pgm_1_Exercise_Qs.ipynb
├── Untitled1.ipynb
└── README.md
```

| File | Description |
|---|---|
| `index.html` | Main web application containing the interface, probability calculators, and visualizations |
| `Lab_Pgm_1_Exercise_Qs.ipynb` | Jupyter Notebook for laboratory programming exercises and questions |
| `Untitled1.ipynb` | Additional Jupyter Notebook for programming practice |
| `README.md` | Project documentation and setup instructions |

## 📚 Learning Outcomes

Through this project, students gain practical experience in:

- Applying mathematical probability formulas.
- Implementing calculations using JavaScript.
- Designing interactive web interfaces with HTML and CSS.
- Representing mathematical data through graphs.
- Interpreting Binomial and Poisson distributions.
- Developing and documenting a small academic software project.

## 🔮 Future Enhancements

- Implement the complete Geometric Distribution module.
- Add step-by-step explanations for probability calculations.
- Include additional discrete probability distributions.
- Improve the collection of worked examples and laboratory exercises.
- Extend graph interaction and visualization options.

## 👩‍💻 Project Details

- **Project:** Discrete Probability Distributions
- **Domain:** Artificial Intelligence and Machine Learning
- **Project Type:** Undergraduate Laboratory Project
- **Application:** Web-Based Educational Tool
- **Repository:** [25ug1byai025-maker/lab](https://github.com/25ug1byai025-maker/lab)

---

*Developed for academic learning and practical exploration of discrete probability distributions.*
