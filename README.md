# PROBABILITY AND STATISTICS FOR MACHINE LEARNING - 1BMATAI301
Discrete Probability Distributions Lab
AIML Laboratory Project · Lab Program 2 · Semester III

An interactive, browser-based learning application for exploring discrete probability distributions through mathematical calculations, probability tables, and visualizations. The project is built with HTML, CSS, and JavaScript and is designed to help students connect probability theory with practical laboratory exercises.
Overview
The application demonstrates three commonly used discrete probability distributions:
- Binomial distribution — models the number of successes in a fixed number of independent trials.
- Poisson distribution — models the number of events occurring in a fixed interval when the average event rate is known.
- Geometric distribution — models the number of independent trials required to obtain the first success.
The interface includes parameter inputs, probability calculations, statistical measures, graphs, and guided laboratory exercises. The pages are intended for educational use and experimentation.
Features
Binomial distribution
- Enter the number of trials \(n\), success probability \(p\), and target count \(k\).
- Calculate the probability mass function (PMF), cumulative distribution function (CDF), and upper-tail probability.
- View the mean, variance, standard deviation, second moment, and skewness.
- Visualize the probability mass function and the mean.
Poisson distribution
- Set the average event rate \(\lambda\) and the event count \(k\).
- Calculate PMF, CDF, and upper-tail probability.
- View statistical measures, including mean, variance, standard deviation, second moment, and skewness.
- Compare Poisson distributions for different values of \(\lambda\).
Geometric distribution
- Set the success probability \(p\) and the trial number \(k\).
- Calculate the probability of the first success occurring on a selected trial.
- View cumulative and upper-tail probabilities, along with statistical measures.
- Compare probabilities for the first, second, and third attempts.
Guided laboratory exercises
- Work through quality-control examples involving product defects.
- Explore alert-monitoring examples using Binomial and Poisson models.
- Compare distributions and interpret how changing parameters affects the graph.
- Load the example parameter values directly into the relevant calculator.
Mathematical models
1. Binomial distribution
For \(X\sim\operatorname{Binomial}(n,p)\):
\[
P(X=k)=\binom{n}{k}p^k(1-p)^{n-k}
\]
- Mean: \(E[X]=np\)
- Variance: \(\operatorname{Var}(X)=np(1-p)\)
- Standard deviation: \(\sqrt{np(1-p)}\)
2. Poisson distribution
For \(X\sim\operatorname{Poisson}(\lambda)\):
\[
P(X=k)=\frac{e^{-\lambda}\lambda^k}{k!}
\]
- Mean: \(E[X]=\lambda\)
- Variance: \(\operatorname{Var}(X)=\lambda\)
3. Geometric distribution
This project uses the convention \(X=1,2,3,\ldots\), where \(X\) is the trial number on which the first success occurs:
\[
P(X=k)=(1-p)^{k-1}p
\]
- Mean: \(E[X]=\frac{1}{p}\)
- Variance: \(\operatorname{Var}(X)=\frac{1-p}{p^2}\)
Technology stack
Technology	Purpose
HTML5	Structures the application and its content
CSS3	Provides the layout, responsive styling, and visual theme
JavaScript	Performs probability calculations, validates inputs, updates results, and draws graphs
HTML Canvas	Renders probability distribution graphs
Jupyter Notebook	Supports separate laboratory exercises stored in notebook files


The web application runs in a modern browser. The standalone HTML application does not require a Node.js build step.
Repository structure
The repository currently contains these top-level files:
File	Purpose
index.html	Main web application for exploring the discrete probability distributions.
Lab_Pgm_1_Exercise_Qs.ipynb	Jupyter Notebook containing laboratory programming exercises and questions.
Untitled1.ipynb	Additional Jupyter Notebook; review its contents and rename it to a meaningful title if it is part of the final submission.
README.md	Project overview, features, mathematical models, setup instructions, and documentation.


Note: This file list reflects the repository's visible top-level files. If you add separate HTML pages or screenshots later, update this section to include their exact filenames.

Getting started
Option 1: Run directly in a browser
1. Open the repository.
2. Select index.html.
3. Download the file, or download the repository using Code → Download ZIP.
4. If you downloaded a ZIP, extract it.
5. Open index.html in a modern browser such as Chrome or Edge.
Option 2: Run using Visual Studio Code
1. Clone the repository or download and extract it.
2. Open the project folder in Visual Studio Code.
3. Open index.html.
4. Run it in a browser. If you use the Live Server extension, right-click index.html and select Open with Live Server.
No package installation or build command is required for the standalone HTML application. An internet connection may be needed if any page uses externally hosted resources.
Clone the repository
git clone https://github.com/25ug1byai025-maker/lab.git
cd lab
Then open index.html in your browser.
Suggested laboratory workflow
1. Open the Binomial module and enter the required values of \(n\), \(p\), and \(k\).
2. Record the mean, variance, and requested probability.
3. Examine the PMF graph and observe the effect of changing the success probability.
4. Open the Poisson module, enter the specified \(\lambda\), and calculate the requested event probabilities.
5. Compare Poisson graphs for different average rates.
6. Open the Geometric module and examine the probability that the first success occurs on the first, second, and third attempts.
7. Record the numerical results, graph observations, and an inference relevant to the quality-control or alert-monitoring example.
Use the exact values specified by your laboratory worksheet for each experiment; the examples above describe the workflow rather than a single set of required answers.
Learning outcomes
By working with this project, students can practise:
- Translating probability formulas into JavaScript functions.
- Validating numeric inputs and handling invalid parameter values.
- Calculating PMF, CDF, and complementary probabilities.
- Computing summary statistics for discrete distributions.
- Representing probability distributions graphically.
- Interpreting how parameters affect the distribution of outcomes.
Limitations and assumptions
- The application is an educational calculator, not a production monitoring or quality-control system.
- The results depend on the parameters entered by the user and the assumptions of each probability model.
- Binomial calculations assume a fixed number of independent trials with a constant success probability.
- Poisson calculations assume a specified average event rate for the interval being modelled.
- Geometric calculations assume independent trials with a constant probability of success.
- The application does not verify real-world monitoring data unless such data are explicitly supplied and processed.
Future improvements
- Add screenshots of the application and its distribution graphs.
- Give all notebook files descriptive names and document their contents.
- Add worked examples with expected results for each distribution.
- Provide downloadable results for laboratory records.
- Improve accessibility and add more guided interpretations of the graphs.
Academic context
- Project: Discrete Probability Distributions
- Domain: Artificial Intelligence and Machine Learning / Probability and Statistics
- Purpose: Undergraduate laboratory learning and experimentation
- Implementation: Browser-based educational application
Developed as an academic laboratory project to support the practical study of discrete probability distributions.
