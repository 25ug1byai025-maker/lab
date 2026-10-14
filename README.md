#Satistical lab
# Discrete Probability Distributions — AIML Laboratory

An interactive web-based learning application developed as part of an undergraduate Artificial Intelligence and Machine Learning (AIML) laboratory. The project helps students understand discrete probability distributions through mathematical calculations, interactive inputs, and graphical visualization.

## 📌 Project Overview

Probability distributions are important in statistics, machine learning, and data analysis. This project provides a simple and user-friendly interface for exploring discrete probability distributions and understanding how changes in input parameters affect probability values.

The application is designed to support laboratory exercises, numerical problem-solving, and visual interpretation of probability distributions.

## 🎯 Objectives

- Understand the fundamentals of discrete probability distributions.
- Calculate important statistical measures using mathematical formulas.
- Evaluate exact and cumulative probabilities.
- Visualize probability distributions using graphs.
- Develop practical programming and problem-solving skills.

## ✨ Features

### 1. Binomial Distribution
- Input the number of trials (\(n\)) and probability of success (\(p\)).
- Calculate mean, variance, standard deviation, second moment, and skewness.
- Calculate the probability mass function (PMF), \(P(X=k)\).
- Calculate cumulative probabilities, \(P(X\leq k)\), and \(P(X>k)\).
- Visualize the distribution using a probability bar chart.

### 2. Poisson Distribution
- Set the average event rate (\(\lambda\)).
- Calculate mean and variance.
- Calculate exact and cumulative probabilities.
- Visualize the probability mass function.
- Compare distributions for different values of \(\lambda\).

### 3. Geometric Distribution
- Included in the project navigation as a planned module for future development.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the web application |
| CSS3 | Styling, layout, and responsive design |
| JavaScript | Probability calculations, validation, and interactivity |
| Jupyter Notebook | Laboratory exercises and programming practice |
| Git & GitHub | Version control and project hosting |

## 📐 Mathematical Concepts

**Binomial Distribution**

For \(X\sim\operatorname{Binomial}(n,p)\):

- Mean: \(E[X]=np\)
- Variance: \(\operatorname{Var}(X)=np(1-p)\)
- Standard deviation: \(\sqrt{np(1-p)}\)
- Second moment: \(E[X^2]=\operatorname{Var}(X)+(E[X])^2\)
- PMF: \(P(X=k)=\binom{n}{k}p^k(1-p)^{n-k}\)

**Poisson Distribution**

For \(X\sim\operatorname{Poisson}(\lambda)\):

- Mean: \(E[X]=\lambda\)
- Variance: \(\operatorname{Var}(X)=\lambda\)
- PMF: \(P(X=k)=\frac{e^{-\lambda}\lambda^k}{k!}\)

## 🚀 Getting Started

### Prerequisites

- A modern web browser such as Google Chrome, Microsoft Edge, or Firefox.
- Visual Studio Code (recommended for editing the source code).
- Live Server extension for convenient local development (optional).

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/25ug1byai025-maker/lab.git
   ```

2. Navigate to the project folder:

   ```bash
   cd lab
   ```

3. Open the folder in Visual Studio Code.

4. Open `index.html` and launch it using Live Server, or open the HTML file directly in your browser.

5. Use the navigation and input fields to explore the available distribution modules.

**Note:** This is a client-side web application. A backend server or database is not required for the basic HTML, CSS, and JavaScript implementation.

## 🧪 Laboratory Exercises

### Exercise 1 — Binomial Distribution

Configure the application with:

- Number of trials: \(n=15\)
- Probability of success: \(p=0.6\)

Determine the mean, variance, \(P(X=9)\), and \(P(X\leq10)\). Observe the probability mass function graph and write an inference about the most likely number of successes.

### Exercise 2 — Poisson Distribution

Consider an AI-based monitoring system with an average event rate of \(\lambda=6\).

Determine the mean, variance, \(P(X=8)\), and \(P(X\leq5)\). Compare the graphs for \(\lambda=2\), \(6\), and \(10\), and explain how the distribution changes as the average event rate increases.

## 📂 Repository Structure

```text
lab/
├── index.html
├── index1.html
├── index2.html
├── index3.html
├── index4.html
├── index5.html
├── index6.html
├── ex1.html
├── ex2.html
├── Lab_Pgm_1_Exercise_Qs.ipynb
├── Untitled1.ipynb
└── README.md
```

The repository contains multiple HTML versions and Jupyter notebooks created during development and laboratory practice.

## 📚 Learning Outcomes

By completing this project, students can:

- Apply probability distribution formulas to numerical problems.
- Implement mathematical calculations using JavaScript.
- Validate user inputs and display computed results.
- Interpret probability graphs and identify distribution patterns.
- Connect theoretical probability concepts with practical applications in AIML.

## 🔮 Future Enhancements

- Implement a complete Geometric Distribution module.
- Add more discrete probability distributions.
- Improve graph interaction and numerical result presentation.
- Organize the different HTML versions into a cleaner project structure.
- Add additional laboratory exercises and worked examples.

## 👩‍💻 Project Information

**Project Type:** Undergraduate Laboratory Project  
**Domain:** Artificial Intelligence and Machine Learning (AIML)  
**Application Type:** Interactive Educational Web Application  
**Repository:** [GitHub — lab](https://github.com/25ug1byai025-maker/lab)

---

*Developed for academic learning and practical exploration of discrete probability distributions.*
