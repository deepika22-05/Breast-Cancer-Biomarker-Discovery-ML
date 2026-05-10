# Integrated Machine Learning and Survival-Based Biomarker Discovery in Breast Cancer

## Objective

This project aims to identify prognostic breast cancer biomarkers using machine learning, differential gene expression analysis, functional enrichment, and survival analysis.

## Dataset

- GEO Dataset: GSE45827
- Platform: GPL570
- Source: NCBI GEO

## Methods

- Data preprocessing
- Differential gene expression analysis
- Volcano plot visualization
- Heatmap analysis
- PCA analysis
- Machine learning classification
  - Random Forest
  - Logistic Regression
  - SVM
- Feature importance analysis
- Functional enrichment analysis
  - GO analysis
  - KEGG pathway analysis
  - Enrichr
- STRING protein interaction network
- Kaplan-Meier survival analysis
- ROC curve analysis

## Results

- Random Forest achieved high classification accuracy (~96%)
- Significant prognostic biomarkers identified:
  - RFC3
  - MASP2
  - PROM2
- Kaplan-Meier analysis demonstrated significant survival association
- Functional enrichment identified cancer-related pathways and biological processes

## Visualizations

### Volcano Plot
![Volcano Plot](images/volcano.png)

### Heatmap
![Heatmap](images/heatmap.png)

### PCA Plot
![PCA](images/PCA_plot.png)

### ROC Curve
![ROC](images/ROC_curve(2).png)

### STRING Network
![STRING](images/string network.jpeg)

### Kaplan-Meier Analysis
![RFC3](images/RFC3_KM.png)
![MASP2](images/MASP2_KM.png)
![PROM2](images/PROM2_KM.png)

## Complete Analysis Notebook

The complete workflow including preprocessing, machine learning, enrichment analysis, and survival analysis is available here:

[Open Notebook](notebooks/Breast_Cancer_Biomarker_Discovery.ipynb)

## Conclusion

This study demonstrates an integrated bioinformatics and machine learning framework for identifying prognostic biomarkers in breast cancer. The identified genes may contribute to improved diagnosis and therapeutic targeting.

## Skills Used

Python, Pandas, Scikit-learn, Bioinformatics, Machine Learning, Functional Genomics, Survival Analysis, Data Visualization
