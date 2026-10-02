# Practical Statistics for Data Scientists

Code reproduction and chapter summaries from the book **"Practical Statistics for Data Scientists"** by Peter Bruce, Andrew Bruce, and Peter Gedeck (O'Reilly Media), covering.

---

## Student Information
- **Nama**: Aidil Fadhli Awaludin
- **NIM**: 101032300087
- **Kelas**: TK-47-01
---

## Repository Structure

```text
├── PracticalStatisticsChapter1.ipynb
├── PracticalStatisticsChapter2.ipynb
├── PracticalStatisticsChapter3.ipynb
├── PracticalStatisticsChapter4.ipynb
├── requirements.txt
└── README.md
```

---

## Chapter Summaries

1. **[Chapter 1: Exploratory Data Analysis](PracticalStatisticsChapter1.ipynb)**  
   Covers estimates of location (mean, trimmed/weighted mean, median), variability (standard deviation, IQR, MAD), and visual exploration techniques such as boxplots, histograms, correlation matrices, and addressing overplotting using hexagonal binning and 2D KDE.

2. **[Chapter 2: Data and Sampling Distributions](PracticalStatisticsChapter2.ipynb)**  
   Explores random sampling, the Central Limit Theorem (CLT), non-parametric bootstrap resampling for confidence intervals, normality assessment via QQ-plots, and standard distributions (Student's t, Binomial, Poisson, and Exponential).

3. **[Chapter 3: Statistical Experiments and Significance Testing](PracticalStatisticsChapter3.ipynb)**  
   Focuses on A/B testing design, hypothesis testing using iterative permutation tests (resampling), two-sample t-tests, ANOVA for multiple comparisons, Chi-Square test for categorical independence, and multi-arm bandit algorithms.

4. **[Chapter 4: Regression and Prediction](PracticalStatisticsChapter4.ipynb)**  
   Implements simple and multiple linear regression, performance evaluation (RMSE, $R^2$), cross-validation, regression diagnostics (residuals, Cook's distance, heteroskedasticity, VIF), and non-linear modeling using polynomial and spline regression.

---

## How to Run

### Google Colab
Each notebook can be executed directly in Google Colab by clicking the **Open in Colab** badge at the top of each `.ipynb` file. Datasets are automatically fetched if executed in the cloud.

### Local Setup
```bash
git clone https://github.com/aidilfadhli/Practical-Statistics-for-Data-Scientists.git
cd Practical-Statistics-for-Data-Scientists
pip install -r requirements.txt
jupyter lab
```

---

## References
- Bruce, P., Bruce, A., & Gedeck, P. (2020). *Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python* (2nd ed.). O'Reilly Media.
- Official Repository: [gedeck/practical-statistics-for-data-scientists](https://github.com/gedeck/practical-statistics-for-data-scientists)
- Course Reference: [farrelrassya/Practical-Statistics-for-Data-Scientist-Books](https://github.com/farrelrassya/Practical-Statistics-for-Data-Scientist-Books)
