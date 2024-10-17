# Student Stress Factor Analysis

This project analyzes various factors contributing to student stress levels based on a dataset of 1,100 students. The analysis focuses on psychological, physiological, environmental, academic, and social factors, identifying key stressors and their impact on student well-being.

## Project Overview
The dataset contains 21 attributes representing different factors such as anxiety levels, self-esteem, academic performance, and social interactions. This analysis answers critical questions outlined in the problem statement, providing insights into the main contributors to student stress.

### Key Findings:
- **Psychological Factors**: 52.26% of students report negative psychological experiences, with 56.36% experiencing depression.
- **Physiological Factors**: 550 students reported poor sleep quality, and 129 students frequently experience headaches.
- **Environmental Factors**: 876 students live in high-noise conditions, and 548 students have unmet basic needs.
- **Academic Factors**: 561 students rate their academic performance as below average, with an average study load of 2.62.
- **Social Factors**: 50.82% of students have experienced bullying, but 882 students participate in extracurricular activities.

### Correlation Heatmap:
For the last question in the problem statement, a **correlation heatmap** was generated using the **Python visual in Power BI**. The following Python snippet was executed within Power BI to create the heatmap:

```python
import seaborn as sns
import matplotlib.pyplot as plt
sns.heatmap(dataset.corr(), cmap='Blues', annot=True)
plt.show()
```

This helped visualize the correlations between various factors, such as anxiety levels, academic performance, and depression, directly within the Power BI environment.

### Analytical Methods:
- **Descriptive Statistics**: Basic metrics like averages and percentages.
- **Comparative Analysis**: Correlations between factors like anxiety, academic performance, sleep quality, and depression.
- **Exploration of Key Stressors**: Identification of factors with the most significant impact on stress levels.

## Files:
- `StressLevelDataset.csv`: Contains data on 1,100 students and 21 attributes.
- `Problem_Statement.md`: Outlines the specific questions and goals of the analysis.
- `Soltions_achieved.md`: Outlines the solutions achieved out of the analysis.
- `Student_Stress_Factor_Analysis.pbix`: Power BI Dashbord
- `README.md`: Project documentation.

## How to Run:
1. Open the Power BI file containing the analysis and navigate to the Python visual for the correlation heatmap.
2. Review the key findings and visualizations directly within Power BI.

---
