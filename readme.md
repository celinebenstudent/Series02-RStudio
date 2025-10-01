# README – Series02: Correlation and Statistical Tests

This series of exercises introduces the basics of **statistical analysis in experimental and clinical data**, with a focus on exploring relationships between measures of **upper-limb non-use** in patients after stroke.  

The dataset used (`NonUse.csv`) contains three main variables:  

- **PANU**: Proximal Arm Non-Use  
- **SANU**: Shoulder Antepulsion Non-Use  
- **EENU**: Elbow Extension Non-Use  

---

## Objectives of the Series
1. Learn how to **explore data** (loading, summarizing, visualizing).  
2. Understand and compute **correlations** between clinical variables.  
3. Apply and interpret **statistical tests** (parametric and non-parametric).  
4. Discuss the **limits of statistical inference** and common **stereotypes/misconceptions** about significance testing.  

---

## Major Steps

### 1. Data exploration
- Import the dataset.  
- Generate summaries (mean, median, variance).  
- Visualize distributions and scatterplots to see patterns.  

### 2. Correlation analysis
- Compute correlations between PANU and SANU (and EENU).  
- Use **Spearman correlation** (non-parametric, rank-based) because clinical data often deviate from normality.  
- Interpret the strength and significance of correlations.  

### 3. Linear regression
- Test whether one variable can **predict** another (e.g., SANU → PANU).  
- Interpret regression coefficients, R², and p-values.  
- Compare regression vs correlation results.  

### 4. Statistical tests
- Distinguish between **parametric tests** (t-test, ANOVA) and **non-parametric tests** (Mann-Whitney, Wilcoxon).  
- Review assumptions (normality, variance homogeneity, independence).  
- Discuss when to choose one over the other.  

### 5. Stereotypes and misconceptions
- The **p-value** is not the probability that the null hypothesis is true.  
- A “significant” result does not mean “important” or “large effect”.  
- “Non-significant” does not prove absence of effect (could be sample size issue).  
- Correlation does not imply causation.  

---

## Key Takeaway
This series shows that:  
- **Correlation ≠ causation**.  
- **Statistical tests** require assumptions and careful interpretation.  
- Clinical data are often noisy, incomplete, and complex → results must be interpreted cautiously, avoiding simplistic stereotypes.  


