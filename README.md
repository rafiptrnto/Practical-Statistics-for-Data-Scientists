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
├── Chapter_1_Exploratory_Data_Analysis.ipynb
├── Chapter_2_Data_And_Sampling_Distribution.ipynb
├── Chapter_3_Statistical_Experiments_and_Significance_Testing.ipynb
├── Chapter_4_Regression_and_Prediction.ipynb
├── Chapter_5_Classification.ipynb
├── Chapter_6_Statistical_Machine_Learning.ipynb
└── Chapter_7_Unsupervised_Learning.ipynb
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

## Chapter 5 — Classification

Chapter kelima membahas **klasifikasi**, yaitu memprediksi kategori (misalnya *default* atau *paid off*) dari sekumpulan predictor, menggunakan data pinjaman LendingClub.

Materi yang dibahas meliputi:

- Naive Bayes (conditional probability, Laplace smoothing)
- Discriminant Analysis (LDA, covariance matrix, Fisher's linear discriminant)
- Logistic Regression (logit, odds ratio, GLM, maximum likelihood, deviance)
- Evaluating Classification Models: confusion matrix, precision, recall, specificity, ROC curve, AUC, lift
- Strategies for Imbalanced Data: undersampling, oversampling, weighting, SMOTE, cost-based classification

### Kesimpulan Chapter 5

Klasifikasi memprediksi kategori hasil dengan memperkirakan probabilitas kelas. Model dievaluasi bukan hanya dengan akurasi, tetapi juga precision, recall, specificity, ROC/AUC, dan lift, terutama pada data tidak seimbang di mana strategi resampling, weighting, dan cutoff berbasis biaya diperlukan.

---

## Chapter 6 — Statistical Machine Learning

Chapter keenam membahas metode **statistical machine learning** yang bersifat data-driven dan tidak memaksakan struktur linear pada data.

Materi yang dibahas meliputi:

- K-Nearest Neighbors: distance metrics, one hot encoding, standardization (z-score), memilih K, KNN sebagai feature engine
- Tree Models: recursive partitioning, Gini impurity dan entropy, mengontrol kompleksitas tree
- Bagging dan Random Forest: out-of-bag error, variable importance, hyperparameters
- Boosting: Adaboost, gradient boosting, XGBoost, regularization, hyperparameters dan cross-validation

### Kesimpulan Chapter 6

KNN dan tree model belajar langsung dari data tanpa model struktural. Metode ensemble (random forest dan boosting) mempertajam daya prediksi tree. Random forest relatif kokoh dengan sedikit tuning, sedangkan boosting (XGBoost) sangat kuat tetapi memerlukan regularization dan cross-validation agar tidak overfit.

---

## Chapter 7 — Unsupervised Learning

Chapter ketujuh membahas **unsupervised learning**, yaitu mengekstrak struktur dari data tanpa variabel respons.

Materi yang dibahas meliputi:

- Principal Components Analysis: loadings, screeplot, memilih jumlah komponen
- Correspondence Analysis
- K-Means Clustering: interpretasi cluster, elbow method
- Hierarchical Clustering: dendrogram dan ukuran dissimilarity (complete, single, average, Ward)
- Model-Based Clustering: multivariate normal, mixture of normals, BIC
- Scaling and Categorical Variables: standardisasi, variabel dominan, Gower's distance, masalah clustering data campuran

### Kesimpulan Chapter 7

Unsupervised learning menemukan struktur tanpa label. PCA dan correspondence analysis mereduksi atau memvisualisasikan data, sedangkan K-means, hierarchical, dan model-based clustering mengelompokkan record. Scaling sangat penting, dan untuk data campuran numerik-kategorikal Gower's distance lebih tepat daripada K-means pada dummy variable.

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
- XGBoost
- imbalanced-learn
- prince

---

# 📓 Notebook

| Chapter | Notebook | Status |
|---|---|---|
| Chapter 1 | Exploratory Data Analysis | ✅ Completed |
| Chapter 2 | Data and Sampling Distributions | ✅ Completed |
| Chapter 3 | Statistical Experiments and Significance Testing | ✅ Completed |
| Chapter 4 | Regression and Prediction | ✅ Completed |
| Chapter 5 | Classification | ✅ Completed |
| Chapter 6 | Statistical Machine Learning | ✅ Completed |
| Chapter 7 | Unsupervised Learning | ✅ Completed |

---

# 🎯 Learning Outcomes

Setelah menyelesaikan Chapter 1–7, beberapa konsep yang telah dipelajari meliputi:

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
17. Membangun dan mengevaluasi model klasifikasi (Naive Bayes, LDA, logistic regression) dengan confusion matrix, ROC, AUC, dan lift.
18. Menangani data tidak seimbang dengan resampling, weighting, dan cost-based classification.
19. Menggunakan KNN, decision tree, random forest, dan XGBoost, serta memahami overfitting dan regularization.
20. Melakukan PCA, correspondence analysis, dan clustering (K-means, hierarchical, model-based).
21. Memahami scaling dan Gower's distance untuk data campuran.

---

# 📌 Reference

Bruce, P., Bruce, A., & Gedeck, P. (2020). *Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python* (2nd Edition). O'Reilly Media.

Repository pendamping resmi buku digunakan sebagai referensi kode Python.

---

## 👤 Author

**Nama:** Herpratama Rafi Putranto  
**Nim:** 101032300076
**Mata Kuliah:** Deep Learning  
