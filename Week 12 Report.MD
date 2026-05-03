# Week 12: Statistical Validation & Supply Chain Insights  

In this Week 12 project, my learning advanced from exploratory analysis into a **complete statistical validation study**. 
The focus was on testing hypotheses with formal statistical methods, confirming which patterns from Week 11’s EDA 
were truly significant, and translating results into actionable business recommendations.  

Where Week 11 emphasized discovery and visualization, Week 12 was about **rigor and confirmation**: hypothesis testing, 
effect sizes, confidence intervals, and practical significance, all documented in a polished report for management.  

---

## Key Skills Practiced  
- Applying structured **hypothesis testing** (chi-square, ANOVA, correlation, regression)  
- Calculating **effect sizes** (Cramér’s V, eta-squared) and confidence intervals  
- Performing **post-hoc Tukey tests** for regional differences  
- Linking statistical results to **business recommendations**  
- Documenting findings in clear, executive-ready language  

---

## What I Implemented  

### 1️⃣ Supplier Reliability  
- Chi-square test comparing Supplier A vs Supplier B on-time delivery  
- Found Supplier A significantly more reliable (~95% vs ~89%)  
- Recommendation: Prefer Supplier A for critical orders 

![My Image Description](https://github.com/R887645/TDI-Python-Learning-Week-12-Project-/blob/main/Task%201A.png?raw=true)

![My Image Description](https://github.com/R887645/TDI-Python-Learning-Week-12-Project-/blob/main/Task%201B.png?raw=true)


### 2️⃣ Regional Cost Analysis  
- ANOVA comparing costs across supplier regions  
- Significant differences found; Tukey HSD identified high vs low-cost regions  
- Recommendation: Shift sourcing toward lower-cost regions to optimize expenses  

![My Image Description](https://github.com/R887645/TDI-Python-Learning-Week-12-Project-/blob/main/Task%202A.png?raw=true)

![My Image Description](https://github.com/R887645/TDI-Python-Learning-Week-12-Project-/blob/main/Task%202c.png?raw=true)

### 3️⃣ Correlation Analysis  
- Distance vs shipping cost: Positive correlation (r≈0.45, p<0.01)  
- Lead time variability vs on-time rate: Negative correlation (r≈–0.30, p<0.05)  
- Recommendation: Factor distance into logistics planning; monitor suppliers with high variability  

![My Image Description](https://github.com/R887645/TDI-Python-Learning-Week-12-Project-/blob/main/Part%203a.png?raw=true)

### 4️⃣ Demand Seasonality  
- ANOVA across months showed weak evidence (p≈0.07)  
- Recommendation: Demand is relatively stable; avoid heavy seasonal stockpiling  

### 5️⃣ Inventory vs Stockouts  
- Correlation analysis showed no significant relationship (r≈–0.05, p>0.05)  
- Recommendation: Inventory buffers alone do not prevent stockouts; focus on supplier reliability  

### 6️⃣ Defects and Returns  
- Chi-square test confirmed that defects significantly increase return rates  
- Recommendation: Negotiate quality improvements with suppliers showing high defect/return rates  

---

## Reflection  
This project showed me how **statistical validation transforms exploratory insights into evidence-based decisions**:  
- Hypothesis testing confirmed which Week 11 findings were reliable  
- Effect sizes clarified the magnitude of differences  
- Confidence intervals provided precision around estimates  
- Business recommendations were grounded in statistical proof, not just descriptive patterns  

## Brief Challenge  
One challenge I faced was handling the **SettingWithCopyWarning** in pandas when creating new columns from subsets.  
At first, this confused my workflow, but I resolved it by explicitly using `.copy()` when working with subsets.  
This small fix improved code reliability and ensured clean, warning-free outputs.  

---

## 🔗 View the Full Project  
[View my Week 12 full project](https://github.com/R887645/TDI-Python-Learning-Week-12-Project-/blob/main/Week12_PersonalDataOrganizer.ipynb)
