# Practical Statistics for Data Scientists

Repository ini dibuat untuk memenuhi tugas mata kuliah **Deep Learning** dengan melakukan reproduksi kode dan pembahasan materi dari buku:

**Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python**  
Second Edition — Peter Bruce, Andrew Bruce, dan Peter Gedeck

Repository ini berisi notebook Python untuk setiap chapter yang dikerjakan. Setiap notebook mencakup reproduksi kode, penjelasan konsep, serta rangkuman materi dari chapter yang dibahas.

---

## 📚 Tujuan

Tujuan pengerjaan repository ini adalah untuk memahami konsep-konsep statistik yang digunakan dalam data science melalui:

- Reproduksi kode Python dari buku.
- Pemahaman teori dan konsep statistik.
- Eksplorasi dan visualisasi data.
- Penerapan metode statistik menggunakan Python.
- Interpretasi hasil analisis.
- Dokumentasi pembelajaran dalam bentuk Jupyter Notebook.

---

## 📂 Struktur Repository

```text
Practical-Statistics-for-Data-Scientists
│
├── README.md
├── Chapter 1 - Exploratory Data Analysis.ipynb
├── Chapter 2 - Data and Sampling Distributions.ipynb
├── Chapter 3 - Statistical Experiments and Significance Testing.ipynb
└── Chapter 4 - Regression and Prediction.ipynb
```

---

# 📖 Ringkasan Chapter

## Chapter 1 — Exploratory Data Analysis

Chapter pertama membahas **Exploratory Data Analysis (EDA)**, yaitu proses awal dalam analisis data untuk memahami karakteristik, pola, distribusi, dan hubungan yang terdapat pada data.

Materi yang dibahas meliputi:

- Elements of Structured Data
- Rectangular Data
- Data Frames and Indexes
- Nonrectangular Data Structures
- Estimates of Location: mean, median, trimmed mean, weighted mean, dan weighted median
- Estimates of Variability: standard deviation, variance, MAD, range, dan IQR
- Exploring the Data Distribution
- Percentiles and Boxplots
- Frequency Tables and Histograms
- Density Plots and Estimates
- Exploring Binary and Categorical Data
- Correlation
- Scatterplots
- Exploring Two or More Variables
- Hexagonal Binning and Contours
- Two Categorical Variables
- Categorical and Numeric Data
- Visualizing Multiple Variables

### Kesimpulan Chapter 1

Exploratory Data Analysis merupakan tahap penting dalam data science karena membantu memperoleh pemahaman awal terhadap data sebelum dilakukan analisis lebih lanjut. Statistik deskriptif dan visualisasi digunakan untuk memahami lokasi, variasi, distribusi, serta hubungan antarvariabel.

---

## Chapter 2 — Data and Sampling Distributions

Chapter kedua membahas **sampling**, distribusi sampling, serta beberapa distribusi probabilitas yang digunakan dalam analisis statistik.

Materi yang dibahas meliputi:

- Random Sampling and Sample Bias
- Bias dan Self-Selection Sampling Bias
- Random Selection
- Size Versus Quality
- Sample Mean Versus Population Mean
- Selection Bias
- Regression to the Mean
- Sampling Distribution of a Statistic
- Central Limit Theorem
- Standard Error
- The Bootstrap
- Confidence Intervals
- Normal Distribution
- Student's t-Distribution
- Binomial Distribution
- Chi-Square Distribution
- F-Distribution
- Poisson and Related Distributions

### Kesimpulan Chapter 2

Sampling dan distribusi sampling merupakan dasar penting dalam statistik inferensial. Konsep seperti Central Limit Theorem, standard error, bootstrap, dan confidence interval membantu memahami ketidakpastian yang muncul ketika menggunakan sampel untuk menarik kesimpulan mengenai populasi.

---

## Chapter 3 — Statistical Experiments and Significance Testing

Chapter ketiga membahas **statistical experiments dan significance testing**, termasuk A/B testing, permutation tests, p-values, hypothesis testing, ANOVA, chi-square tests, multi-arm bandit, serta statistical power.

Materi yang dibahas meliputi:

- A/B Testing
- Randomization
- Control Group
- Permutation Test
- Statistical Significance and p-Values
- Hypothesis Tests
- One-Sided and Two-Sided Tests
- t-Tests
- Multiple Testing
- Degrees of Freedom
- ANOVA
- Chi-Square Test
- Multi-Arm Bandit Algorithm
- Power and Sample Size

### Kesimpulan Chapter 3

Statistical experiments digunakan untuk menguji apakah perbedaan yang diamati dalam data dapat dijelaskan oleh variasi acak atau memberikan bukti terhadap adanya perbedaan. Berbagai metode seperti permutation test, t-test, ANOVA, dan chi-square test dapat digunakan sesuai dengan karakteristik data dan pertanyaan yang dianalisis.

---

## Chapter 4 — Regression and Prediction

Chapter keempat membahas **regression dan prediction**, mulai dari simple linear regression hingga polynomial regression, spline, dan Generalized Additive Models.

Materi yang dibahas meliputi:

### 1. Simple Linear Regression
- The Regression Equation
- Fitted Values and Residuals
- Least Squares
- Prediction Versus Explanation

### 2. Multiple Linear Regression
- King County Housing Data
- Assessing the Model
- Cross-Validation
- Model Selection and Stepwise Regression
- Weighted Regression

### 3. Prediction Using Regression
- The Dangers of Extrapolation
- Confidence and Prediction Intervals

### 4. Factor Variables in Regression
- Dummy Variables Representation
- Factor Variables with Many Levels
- Ordered Factor Variables

### 5. Interpreting the Regression Equation
- Correlated Predictors
- Multicollinearity
- Confounding Variables
- Interactions and Main Effects

### 6. Regression Diagnostics
- Outliers
- Influential Values
- Heteroskedasticity
- Non-Normality
- Correlated Errors
- Partial Residual Plots and Nonlinearity

### 7. Polynomial and Spline Regression
- Polynomial Regression
- Splines
- Generalized Additive Models (GAM)

### Kesimpulan Chapter 4

Regression dapat digunakan untuk memahami hubungan antara response dan predictor serta melakukan prediction. Selain membangun model, evaluasi dan diagnostics juga diperlukan untuk memahami karakteristik model dan mendeteksi permasalahan seperti outlier, influential observations, heteroskedasticity, dan nonlinearity.

Untuk hubungan yang tidak linear, polynomial regression, splines, dan GAM dapat digunakan untuk memodelkan pola non-linear.

---

# 🛠️ Tools and Libraries

Pengerjaan notebook menggunakan Python dan beberapa library yang digunakan dalam buku, antara lain:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Scikit-learn
- dmba
- PyGAM

---

# 📓 Notebook

| Chapter | Notebook | Status |
|---|---|---|
| Chapter 1 | Exploratory Data Analysis | ✅ Completed |
| Chapter 2 | Data and Sampling Distributions | ✅ Completed |
| Chapter 3 | Statistical Experiments and Significance Testing | ✅ Completed |
| Chapter 4 | Regression and Prediction | ✅ Completed |

---

# 🎯 Learning Outcomes

Setelah menyelesaikan Chapter 1–4, beberapa konsep yang telah dipelajari meliputi:

1. Melakukan Exploratory Data Analysis.
2. Menggunakan statistik deskriptif untuk memahami data.
3. Memahami sampling dan sampling distributions.
4. Memahami Central Limit Theorem.
5. Menggunakan bootstrap dan confidence intervals.
6. Memahami probability distributions.
7. Melakukan statistical experiments.
8. Memahami hypothesis testing dan p-values.
9. Melakukan permutation test.
10. Menggunakan t-test, ANOVA, dan chi-square test.
11. Memahami statistical power dan sample size.
12. Membuat simple dan multiple linear regression.
13. Melakukan prediction menggunakan regression.
14. Menggunakan categorical variables dalam regression.
15. Melakukan regression diagnostics.
16. Memodelkan hubungan non-linear menggunakan polynomial regression, splines, dan GAM.

---

# 📌 Reference

Bruce, P., Bruce, A., & Gedeck, P. (2020). *Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python* (2nd Edition). O'Reilly Media.

Repository pendamping resmi buku digunakan sebagai referensi kode Python.

---

## 👤 Author

**Nama:** Herpratama Rafi Putranto  
**Nim:** 101032300076
**Mata Kuliah:** Deep Learning  
