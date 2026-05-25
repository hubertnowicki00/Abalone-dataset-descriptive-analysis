# Abalone Data Analysis and Regression Modeling

## 1. Project Description

This project presents an exploratory data analysis and statistical modeling study performed on the Abalone dataset. The primary goal of the analysis was to investigate relationships between the physical dimensions of abalones, particularly focusing on the relationship between `Length` and `Whole Weight`.

The project includes:

- Exploratory Data Analysis (EDA)
- Distribution analysis using histograms and boxplots
- Descriptive and moment-based statistics
- Outlier detection and removal using the IQR method
- Data transformation techniques
- Linear regression modeling
- Residual diagnostics and statistical validation
- Correlation analysis
- Group segmentation by sex

## 2. Data Source

The analysis was conducted using the **Abalone Dataset**, a widely used dataset for predictive modeling and statistical analysis tasks.

Dataset source:

- UCI Machine Learning Repository  
- https://archive.ics.uci.edu/ml/datasets/abalone

The dataset contains physical measurements of abalones, including:

- Sex
- Length
- Diameter
- Height
- Whole Weight
- Shucked Weight
- Viscera Weight
- Shell Weight
- Rings

## 3. Tech Stack and Methodology

### Tech Stack

- **Python**
- **Pandas** — data manipulation
- **NumPy** — numerical operations
- **Matplotlib** — plotting and visualization
- **Seaborn** — statistical visualizations
- **SciPy** — statistical analysis
- **Statsmodels / Scikit-learn** — regression modeling

### Methodology

The workflow followed these main steps:

1. Initial exploratory data analysis
2. Visualization of distributions and relationships
3. Statistical characterization of variables
4. Detection and removal of outliers using the IQR method
5. Variable transformation for regression suitability
6. Linear regression modeling
7. Residual diagnostics:
   - Residual plots
   - Normality checks
   - QQ plots
   - Independence testing
8. Correlation analysis
9. Group segmentation analysis based on categorical variables

The final model used the cube root transformation of the `Whole Weight` variable to achieve linearity and improve regression performance.

## 4. Repository Contents

```text
├── plots/
│   ├── 2.png
│   ├── 3.png
│   ├── 4.png
│   ├── 5.png
│   ├── 6.png
│   ├── 7.png
│   ├── 8.png
│   ├── 9.png
│   ├── 10.png
│   ├── 11.png
│   ├── 12.png
│   ├── 13.png
│   ├── 14.png
│   ├── 15.png
│   ├── 16.png
│   └── 17.png
│
├── abalone_da.ipynb
│
├── report.pdf
│
└── README.md
```

---

## 5. Plots

### Index Plots

#### Length Index Plot
![Plot 2](plots/2.png)

#### Whole Weight Index Plot
![Plot 3](plots/3.png)

---

### Distribution Analysis

#### Length Boxplot and Histogram
![Plot 4](plots/4.png)

#### Whole Weight Boxplot and Histogram
![Plot 5](plots/5.png)

---

### Scatterplot Analysis

#### Whole Weight vs Length
![Plot 6](plots/6.png)

---

### Outlier Analysis

#### Outlier Detection
![Plot 7](plots/7.png)

#### Dataset After Outlier Removal
![Plot 8](plots/8.png)

---

### Data Transformation

#### Cube Root Transformation
![Plot 9](plots/9.png)

#### Logarithmic Transformation
![Plot 10](plots/10.png)

---

### Regression Modeling

#### Linear Regression Model
![Plot 11](plots/11.png)

---

### Residual Diagnostics

#### Residual Plot
![Plot 12](plots/12.png)

#### Residual Histogram
![Plot 13](plots/13.png)

#### QQ Plot
![Plot 14](plots/14.png)

#### Autocorrelation Plot
![Plot 15](plots/15.png)

---

### Group Segmentation

#### Segmentation by Sex
![Plot 16](plots/16.png)

---

### Correlation Analysis

#### Correlation Heatmap
![Plot 17](plots/17.png)
