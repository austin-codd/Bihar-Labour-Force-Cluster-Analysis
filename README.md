# Bihar Labour Force Cluster Analysis

> An unsupervised machine learning project that identifies distinct labour market segments in Bihar using microdata from the Periodic Labour Force Survey (PLFS). The project combines statistical analysis, feature engineering, dimensionality reduction, clustering, and interactive visualizations to uncover hidden patterns in the state's workforce.

---

## Project Overview

Labour markets are highly heterogeneous. Workers differ in their demographic characteristics, education, employment status, occupation, income, and work conditions. Traditional descriptive statistics often fail to capture these complex relationships.

This project applies **unsupervised machine learning** to identify naturally occurring groups within Bihar's labour force. By clustering individuals with similar socioeconomic characteristics, the analysis provides insights that can support evidence-based labour market policies and targeted employment interventions.

---

## Objectives

- Clean and preprocess PLFS microdata
- Perform exploratory data analysis (EDA)
- Engineer meaningful labour-market features
- Reduce dimensionality using Principal Component Analysis (PCA)
- Identify optimal number of clusters
- Apply K-Means clustering
- Profile and interpret each cluster
- Generate policy-relevant insights through visualization

---

## Dataset

**Source**

- Ministry of Statistics and Programme Implementation (MoSPI)
- Periodic Labour Force Survey (PLFS)

The dataset contains anonymized individual-level information including:

- Age
- Gender
- Education
- Marital Status
- Rural/Urban Residence
- Occupation
- Industry
- Employment Status
- Weekly Hours Worked
- Earnings
- Social Group
- Employment Type
- Skill Training
- Other labour market characteristics

---

## Project Workflow

```
Raw PLFS Data
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Scaling & Encoding
      │
      ▼
Principal Component Analysis
      │
      ▼
Optimal Cluster Selection
(Elbow Method + Silhouette Score)
      │
      ▼
K-Means Clustering
      │
      ▼
Cluster Interpretation
      │
      ▼
Policy Insights
```

---

## Technologies Used

| Category | Tools |
|-----------|------|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Machine Learning | Scikit-learn |
| Dimensionality Reduction | PCA |
| Clustering | K-Means |
| Notebook | Google Colab / Jupyter |

---

## Exploratory Data Analysis

The notebook explores:

- Demographic composition
- Educational attainment
- Employment status distribution
- Income distribution
- Occupation patterns
- Rural vs Urban differences
- Correlation analysis
- Missing value assessment
- Feature distributions

---

## Machine Learning Pipeline

### 1. Data Preprocessing

- Missing value treatment
- Categorical encoding
- Feature scaling
- Outlier handling

### 2. Feature Engineering

Relevant labour market variables are transformed into machine-learning-ready features.

### 3. Principal Component Analysis (PCA)

PCA is used to reduce dimensionality while preserving the majority of information contained in the original variables.

### 4. Cluster Selection

The optimal number of clusters is determined using:

- Elbow Method
- Silhouette Score

### 5. K-Means Clustering

Workers are grouped into distinct labour market segments based on multidimensional similarities.

---

## Key Outputs

The project produces:

- Clean analytical dataset
- PCA visualization
- Elbow Curve
- Silhouette Analysis
- Cluster distribution
- Cluster profiling tables
- Feature importance across clusters
- Policy interpretation of each labour segment

---

## Business / Policy Value

The analysis can help policymakers:

- Identify vulnerable worker groups
- Design targeted employment programs
- Improve skill development initiatives
- Understand labour market segmentation
- Support evidence-based workforce planning
- Monitor socioeconomic inequalities

---

## Repository Structure

```
├── Summer_Project.ipynb        # Complete analysis notebook
├── README.md
└── images/                     # Figures (optional)
```

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Unsupervised Machine Learning
- Principal Component Analysis
- K-Means Clustering
- Cluster Profiling
- Statistical Thinking
- Policy Analytics

---

## Future Improvements

- Hierarchical Clustering
- DBSCAN
- Gaussian Mixture Models
- Cluster Stability Analysis
- Interactive Power BI Dashboard
- Geographic visualization of clusters
- Comparison with other Indian states

---

## Results

The project demonstrates how unsupervised learning can reveal hidden labour market structures that are not immediately visible through conventional descriptive analysis. The identified clusters provide interpretable workforce segments that can inform labour economics research and public policy.

---
## License

This project is intended for educational and research purposes.
