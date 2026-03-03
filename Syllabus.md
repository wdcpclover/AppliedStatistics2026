# Applied Statistics with Python — Course Outline (2026)

**Format:** 18 weeks × 2 hours/week = 36 hours total | Jupyter Notebook | English

---

## Part I: Python Programming Foundation (Week 1–4)

| Week | Topic | Content |
|------|-------|---------|
| 1 | **Course Introduction & Python Setup** | Course overview, grading policy, Anaconda/Jupyter setup, "Hello World" to first plot |
| 2 | **Python Essentials** | Variables, data types, control flow, functions, list/dict comprehension, exception handling |
| 3 | **NumPy & Pandas** | ndarray, broadcasting, DataFrame, Series, indexing, groupby, merge, missing data handling |
| 4 | **Data Visualization** | Matplotlib fundamentals, Seaborn statistical plots, choosing the right chart, EDA workflow |

---

## Part II: Applied Statistics (Week 5–12)

| Week | Topic | Content |
|------|-------|---------|
| 5 | **Descriptive Statistics & EDA** | Central tendency, dispersion, skewness, kurtosis; `df.describe()`, box plot, histogram, outlier detection |
| 6 | **Probability & Distributions** | Probability rules, conditional probability, Bayes' theorem; Normal, Binomial, Poisson — `scipy.stats` simulation & visualization |
| 7 | **Sampling & Estimation** | Sampling methods, Central Limit Theorem (simulation demo), confidence intervals, bootstrap |
| 8 | **Hypothesis Testing** | z-test, t-test, chi-square, p-value interpretation, Type I/II errors, effect size; real dataset practice |
| 9 | **Correlation & Regression** | Pearson/Spearman correlation, simple & multiple linear regression, residual diagnostics, `statsmodels` OLS |
| 10 | **ANOVA & Non-parametric Methods** | One-way/Two-way ANOVA, post-hoc tests; Mann-Whitney, Kruskal-Wallis; parametric vs non-parametric decision guide |
| 11 | **Time Series Analysis** | Trend, seasonality, stationarity; moving average, exponential smoothing, ARIMA; `statsmodels` tsa, real-world forecasting example |
| 12 | **Bayesian Statistics** | Prior, likelihood, posterior; conjugate priors; Bayesian vs Frequentist comparison; `PyMC` intro, simple Bayesian inference example |

---

## Part III: Data Collection — Web Scraping (Week 13)

| Week | Topic | Content |
|------|-------|---------|
| 13 | **Web Scraping with Python** | HTTP basics, `requests`, `BeautifulSoup`, regular expressions, handling dynamic pages; hands-on: scrape a real dataset for analysis |

---

## Part IV: Machine Learning & AI (Week 14–16)

| Week | Topic | Content |
|------|-------|---------|
| 14 | **ML Fundamentals & Supervised Learning** | Train/test split, cross-validation, bias-variance tradeoff; Logistic regression, Decision tree, Random forest — `scikit-learn` pipeline |
| 15 | **Unsupervised Learning & Model Evaluation** | K-means, hierarchical clustering, PCA; evaluation metrics (accuracy, precision, recall, F1, ROC-AUC, silhouette score) |
| 16 | **Deep Learning & LLMs** | Neural network intuition, PyTorch basics; what are LLMs, prompt engineering, calling AI APIs from Python; the future of statistics + AI |

---

## Part V: Paper Replication & Presentation (Week 17–18)

| Week | Topic | Content |
|------|-------|---------|
| 17 | **Student Presentations — Group A** | Paper replication reports: research background, methodology, code walkthrough, results reproduction, critical analysis |
| 18 | **Student Presentations — Group B + Wrap-up** | Remaining presentations, peer review, course summary, Q&A |

---

## Paper Replication Project

### Timeline

- **Week 6** — Publish candidate paper list (by research domain)
- **Week 8** — Students form teams (2–3 per group), select paper
- **Week 13** — Mid-term check: data acquired, methodology understood
- **Week 16** — Submit replication code + report draft
- **Week 17–18** — In-class presentation (15 min talk + 5 min Q&A)

### Presentation Requirements

1. Paper summary (problem, data, method)
2. Replication process (data collection, code implementation)
3. Results comparison (original vs replication)
4. Reflection (difficulties, limitations, improvements)

### Candidate Paper Domains

- Regression/classification on public datasets (UCI, Kaggle)
- Time series forecasting (stock, weather, COVID)
- Bayesian inference applications (A/B testing, clinical trials)
- NLP/sentiment analysis with statistical methods
- Clustering & dimensionality reduction case studies

---

## Grading Structure

| Component | Weight |
|-----------|--------|
| Attendance & participation | 10% |
| Weekly Jupyter exercises (5–6 assignments) | 30% |
| Paper replication report + code | 30% |
| Presentation + Q&A | 20% |
| Peer review | 10% |

---

## Recommended Books & Resources

1. *An Introduction to Statistics with Python* — Thomas Haslwanter
2. *An Introduction to Statistical Learning* — James, Witten, Hastie, Tibshirani
3. *Python for Data Analysis* — Wes McKinney
4. *Business Statistics: A First Course* — Levine, Stephan, Szabat

## Python Libraries

| Stage | Libraries |
|-------|-----------|
| Python basics | NumPy, Pandas, Matplotlib, Seaborn |
| Statistics | scipy.stats, statsmodels, pingouin, PyMC, ArviZ |
| Web scraping | requests, BeautifulSoup, re, Selenium |
| Machine learning | scikit-learn, PyTorch |
| AI / LLMs | openai, anthropic |
