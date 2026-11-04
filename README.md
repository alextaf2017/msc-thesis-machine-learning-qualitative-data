# Machine Learning Techniques for the Analysis of Qualitative Data: A Case Study

## Master's Thesis

**Author:** Alessio Tafuni  
**MSc in Statistics and Methods for Economics and Finance**  
University of Bari Aldo Moro  
Final Grade: 110/110 cum laude

---

## Overview

This Master's Thesis investigates the relationship between young people and Artificial Intelligence, focusing on how students perceive, use and evaluate AI technologies in educational and everyday contexts.

The main objective of the research is to identify the factors associated with positive attitudes toward AI and with perceptions of autonomy and dependency through an integrated framework combining statistical modelling, Structural Equation Modelling (SEM), Machine Learning and Bayesian Networks. 【1-08942b】

---

## Dataset

The study is based on data collected within the Italian Scientific Degrees Project (PLS), involving secondary school students from the provinces of Bari and Taranto.

### Sample Characteristics

- 1,804 students surveyed
- 64 variables
- 9 thematic sections
- AI usage patterns
- Benefits and risks perception
- Privacy and governance
- Human-AI substitution scenarios
- School-related applications of AI

【1-08942b】

---

## Methodology

The research adopts a multi-method quantitative approach integrating:

### Statistical Analysis
- Descriptive statistics
- Inferential statistics
- Non-parametric hypothesis testing

### Exploratory Factor Analysis (EFA)
Used to identify latent dimensions related to:
- Perceived benefits
- Perceived risks
- Human substitutability

### Structural Equation Modelling (SEM)
Path analysis to investigate relationships between:
- AI usage behaviours
- Perceived benefits
- Perceived risks
- Attitudes toward AI
- Autonomy/dependency perceptions

### Machine Learning Models
Several predictive models were developed and compared:

- Logistic Regression
- Random Forest
- Gradient Boosting Machine
- XGBoost
- Multi-Layer Perceptron (MLP)

### Bayesian Networks
Probabilistic modelling to evaluate how combinations of perceived benefits and risks modify the probability of positive attitudes toward AI.

### Text Mining
Qualitative analysis of open-ended responses regarding parental restrictions on AI usage.

【1-08942b】【2-beabc2】

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Statistical Modelling
- Machine Learning
- SEM / Path Analysis
- Bayesian Networks
- Data Visualization

---

## Main Findings

### AI Adoption is Widespread

- Students use approximately four AI tools on average.
- ChatGPT emerged as the most widely used tool.
- Nearly 70% of students verify AI-generated information only occasionally or never.

【1-08942b】

### Perceived Benefits Drive Positive Attitudes

The strongest predictors of positive attitudes toward AI were:

- Practical-functional benefits
- Practical-informative AI usage
- Transformative benefits

Conversely, perceived risks significantly reduced positive attitudes.

【1-08942b】

### Machine Learning Results

For attitude classification, multiple models were evaluated and compared.

Key results include:

- MLP Accuracy: 70.3%
- MLP Balanced Accuracy: 68.9%
- MLP F1 Score: 62.5%
- MLP ROC-AUC: 75.9%

Despite its strong predictive performance, the neural network did not significantly outperform the Logistic Regression model, which offered superior interpretability.

【2-beabc2】【1-08942b】

### Autonomy and Dependency are Distinct Constructs

Results showed that higher AI usage does not automatically correspond to stronger perceptions of autonomy.

Autonomy and dependency appear to be influenced primarily by:

- Transformative benefits
- Perceived risks
- Individual characteristics

rather than usage frequency itself.

【1-08942b】【2-beabc2】

### Bayesian Network Analysis

The probability of a positive attitude toward AI changed significantly according to perceived benefits and risks:

- Baseline probability: 39.8%
- High practical benefits: 57.2%
- High benefits + low risks: 64.6%
- Low benefits + high risks: 19.6%

These results confirmed the consistency between statistical and machine learning findings.

【2-beabc2】【1-08942b】

---

## Key Contributions

- Integration of statistical and machine learning techniques within a single analytical framework.
- Application of SEM and Bayesian Networks to explain attitudes toward Artificial Intelligence.
- Large-scale empirical analysis on more than 1,800 students.
- Comparative evaluation of interpretable and non-interpretable predictive models.
- Investigation of sociotechnical aspects related to AI adoption among young people.

---

## Repository Contents

- Thesis presentation
- Project overview and documentation

The source code and datasets are intentionally not publicly available.

---

## Author

**Alessio Tafuni**

LinkedIn: https://www.linkedin.com/in/alessio-tafuni-9544a4264

GitHub: https://github.com/alextaf2017
