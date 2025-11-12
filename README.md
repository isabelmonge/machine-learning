# Machine Learning Projects in R

Projects completed as part of the **UC3M Master's in Computational Social Science (CSS)**.  
This repository includes supervised and unsupervised machine learning projects written in R, covering regression, classification, clustering, and dimensionality reduction.

You can open the `.Rmd` files to view and run the code, or the corresponding `.html` files to read the rendered analysis.

---

## Unsupervised Learning: Flights

**Research question:**  
Commercial airports in the United States vary in size, infrastructure, passenger volume, environmental conditions, and the types and frequency of delays they experience. These differences affect how airports operate and the challenges they face. This project explores how airports can be grouped based on these shared characteristics.

**Goal:**  
Use Principal Component Analysis (PCA) and clustering techniques to identify key dimensions of variation among airports and classify them into meaningful groups.

**Methods:**  
Principal Component Analysis (PCA), K-means clustering, and hierarchical clustering.

**Focus:**  
Reducing dimensionality to highlight key features, visualizing clusters to interpret natural groupings, and exploring how airport characteristics align with delay patterns and operational factors.

**Applications:**  
Findings provide a data-driven framework for understanding airport differences. Policymakers and airport authorities can use this classification to guide infrastructure investments and operational planning, while airlines can apply these insights to optimize scheduling and route planning.

---

## Supervised Learning: Airbnb

**Goal:**  
Apply a range of supervised learning models to predict **superhost status** (classification) and **nightly price** (regression) using Airbnb listing data.

**Methods:**  
Linear and logistic regression, decision trees, random forests, gradient boosting (GBM), and XGBoost.

**Focus:**  
Comparing model performance across regression and classification tasks, tuning hyperparameters for optimal predictive accuracy, and evaluating results with metrics such as RMSE, accuracy, and confusion matrices.

**Applications:**  
Demonstrates how supervised learning can be used to understand drivers of host performance and pricing dynamics in online rental markets.

---

## How to Use

- To **run the code**, open the `.Rmd` files in RStudio and knit them.  
- To **read the results only**, open the `.html` files directly in your browser.
