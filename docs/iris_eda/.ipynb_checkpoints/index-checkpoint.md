
# 🌸  Iris Dataset – Exploratory Data Analysis

This was my first data analysis project, using the classic Iris dataset. It helped me explore the fundamentals of working with data in Python — especially using Pandas for data manipulation and Seaborn for visualization. Looking back at it now, I clearly see how much I’ve grown in terms of understanding data structures, building insight, and communicating findings. This project laid the foundation for my later work in machine learning and full data science pipelines.


## Problem

Before diving into machine learning, I wanted to develop a feel for how to explore and understand data. This project allowed me to study real-world structure in a small, clean dataset, and to start thinking analytically about features and targets.

---

## My Role

- Led all steps of the analysis, from data loading and cleaning to visualization and interpretation.
- Designed visualizations to explore species-level patterns and feature relationships.
- Documented the workflow as a structured EDA report (now presented as slides).

---

## Key Features

- Summary statistics and feature distributions
- Correlation matrix
- Feature comparison across classes
- Class separation in feature space
- Created domain-inspired feature: petal area (length × width)

---

## Tools & Technologies

Python, Pandas, Matplotlib, Jupyter Notebook, nbconvert (slides)

---

## Key Insights

- Petal-related features (length, width, area) are the strongest indicators of species.
- Clear class separation is visible between Setosa and the other two species.
- High correlations were observed between several features, especially:
  - Petal length & Petal width: **r = 0.96**
  - Sepal length & Petal length: **r = 0.87**
- Dataset was clean (no missing values), with 3 duplicates and a few mild outliers in Setosa group.
- Created a derived feature: **petal area**, which enhanced visual comparison across classes.

## Limitations & Future Work

- **Static dataset, no generalization**: The Iris dataset is small, well-behaved, and often used for educational purposes. While ideal for early-stage exploration, its simplicity limits generalization to more complex, noisy real-world datasets.

- **No modeling step included**: This project focused strictly on EDA and feature understanding. A natural next step would be applying classification models (e.g., logistic regression) to evaluate how well patterns translate into predictive performance.

- **No interactivity or dashboarding**: All outputs were static (PDF/slides). Future iterations could include interactive dashboards (e.g., Streamlit, Plotly Dash) for deeper user-driven exploration and presentation.

- **Minimal feature engineering**: Only a single derived feature (petal area) was created. This leaves room for experimenting with domain-inspired transformations, dimensionality reduction, or clustering approaches to uncover deeper patterns.



# [View slides (HTML)](../assets/irysy.slides.html)  


# [Download slides (PDF)](../assets/irysy.slides.pdf)
