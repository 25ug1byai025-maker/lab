# Discrete Probability Distributions

**AIML Laboratory Project | Interactive Probability Calculators and Visualizations**

## 1. Project Overview

This project is a web-based application developed to explore discrete probability distributions through interactive calculators and visualizations.

It focuses on applying probability concepts using HTML, CSS, and JavaScript. The repository contains individual web pages for calculating binomial probabilities, visualizing probability distributions, exploring cumulative probabilities, and experimenting with Poisson distribution concepts.

## 2. Project Objectives

- Understand and implement discrete probability distributions.
- Calculate probabilities using mathematical formulas.
- Visualize probability values through interactive graphs.
- Develop user-friendly web interfaces for mathematical applications.
- Connect theoretical probability concepts with practical programming.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structures the web pages |
| CSS3 | Provides styling and layouts |
| JavaScript | Handles calculations and interactivity |
| Chart.js | Creates charts on pages where it is used |
| Jupyter Notebook | Supports laboratory programming exercises |

## 4. Features

- **Binomial Parameter Studio:** Enter distribution parameters such as the number of trials and probability of success.
- **PMF Calculator:** Calculate the probability of exactly a specified number of successes.
- **CDF Calculator:** Calculate cumulative probability and complementary probability.
- **PMF Visualizer:** Explore the probability distribution through graphs.
- **Poisson Lab:** Provides a separate interface for Poisson distribution experiments.
- **Interactive Inputs:** Update parameters and observe the corresponding results on supported pages.

## 5. Repository Structure and File Descriptions

The repository contains the following files, each serving a different purpose.

### Main application and HTML pages

| File | Description |
|---|---|
| `index.html` | Main landing page for the Discrete Probability Distributions project. Introduces the application and provides the main interface for exploring distributions. Poisson and Geometric sections are presented as upcoming features here. |
| `index1.html` | **Binomial Parameter Studio.** Provides an interface to enter the number of trials (\(n\)) and probability of success (\(p\)). Uses default values of \(n=20\) and \(p=0.35\), with live parameter updates. |
| `index2.html` | **Binomial Distribution Lab.** Provides another interface for configuring and exploring binomial distribution parameters. |
| `index3.html` | **Binomial PMF Calculator.** Calculates the probability of obtaining exactly \(k\) successes in \(n\) independent trials and presents the calculation steps. |
| `index4.html` | **Binomial PMF Calculator.** A separate page for calculating the probability of exactly a specified number of successes in a binomial distribution. |
| `index5.html` | **Binomial CDF Calculator.** Calculates cumulative probability \(P(X\leq k)\) and complementary probability \(P(X>k)\), with a bar-chart visualization. |
| `index6.html` | **Binomial PMF Visualizer.** Displays an interactive graph of binomial probabilities and allows the user to change distribution parameters. |
| `ex1.html` | **Binomial Distribution Experiment.** A laboratory-style visualization of the binomial probability mass function, including a mean indicator on the graph. |
| `ex2.html` | **Poisson Distribution Experiment.** A separate laboratory interface for exploring Poisson distribution concepts and visualizing probability values. |

### Jupyter Notebook files

| File | Description |
|---|---|
| `Lab_Pgm_1_Exercise_Qs.ipynb` | Jupyter Notebook containing laboratory programming exercises and questions. |
| `Untitled1.ipynb` | Additional Jupyter Notebook file. Its specific contents should be documented after reviewing the notebook. |

### Documentation

| File | Description |
|---|---|
| `README.md` | Explains the project, its objectives, technologies, file structure, and instructions for running the application. |

**Note:** The HTML pages are separate implementations or experiments. The repository should not be described as one fully integrated application unless those pages have been connected through a common interface.

## 6. Mathematical Concepts

### Binomial Distribution

The binomial distribution calculates the probability of obtaining exactly \(k\) successes in \(n\) independent trials, where each trial has the same probability of success \(p\).

The probability mass function is:

\[
P(X=k)=\binom{n}{k}p^k(1-p)^{n-k}
\]

Where:

- \(n\) = Number of trials
- \(k\) = Number of successes
- \(p\) = Probability of success
- \(1-p\) = Probability of failure

### Poisson Distribution

The Poisson distribution models the number of times an event occurs within a specified interval, given an average event rate.

### Geometric Distribution

The geometric distribution models the number of independent trials required to obtain the first success.

*The repository's main page presents Poisson and Geometric distributions as upcoming features; the separate Poisson experiment is available in `ex2.html`.*

## 7. How to Run the Project

1. Clone or download the repository from GitHub.
2. Extract the downloaded files, if necessary.
3. Open the project folder in Visual Studio Code or another code editor.
4. Open `index.html` in a web browser to view the main page.
5. Open individual HTML files to explore their respective calculators and experiments.

No build process is required for the standalone HTML pages. Pages that use external libraries or fonts through CDNs may require an internet connection.

## 8. Learning Outcomes

Through this project, students can gain experience in:

- Implementing probability formulas using JavaScript.
- Designing interactive web pages using HTML and CSS.
- Visualizing mathematical data through charts.
- Understanding binomial and Poisson probability concepts.
- Applying programming skills to mathematical laboratory exercises.

## 9. Future Enhancements

- Integrate the individual calculators into a single application.
- Complete the Poisson and Geometric modules in the main interface.
- Add more probability distributions.
- Include worked examples and step-by-step solutions.
- Improve navigation and provide a consistent user interface across all pages.

## 10. Conclusion

This project demonstrates the practical application of web development and mathematical concepts in the study of discrete probability distributions. It provides a foundation for building interactive educational tools that help students understand probability calculations and graphical representations.

---

**Project Type:** Academic Laboratory Project  
**Domain:** Artificial Intelligence and Machine Learning / Mathematics  
**Application:** Web-Based Educational Tool
