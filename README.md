# Machine Learning based Survival Group Prediction in Glioblastoma
Links to data analysis workflows, supplementary research data and results of the study

**Abstract:**/ 
Glioblastoma (GBM) is a very aggressive malignant brain tumor with the vast majority of patients surviving less than 12 months (Short-term survivors [STS]). Only around 2% of patients survive more than 36 months (Long-term survivors [LTS]). Studying these extreme survival groups might help in better understanding GBM biology. This work aims at exploring application of machine learning methods in predicting survival groups(STS, LTS). We used age and gene expression profiles belonging to 249 samples from publicly available datasets. 10 Machine learning methods have been implemented and compared for their performances. Hyperparameter tuned random forest model performed best with accuracy of 80% (AUC of 74% and F1_score of 85%). The performance of this model is validated on external test data of 16 samples. The model predicted the true survival group for 15 samples achieving an accuracy of 93.75%. This classification model is deployed as a web tool GlioSurvML. The top 1500 features which retained classification efficiency (Accuracy of 80%, AUC of 74%) were studied for enriched pathways and disease-causal biomarker associations using the HumanPSDTM database. We identified 199 genes as possible biomarkers of GBM and/or similar diseases (like Glioma, astrocytoma, and others). 57 of these genes are shown to be differentially expressed across survival groups and/or have impact on survival. This work demonstrates the application of machine learning methods in predicting survival groups of GBM. 


The Machine Learning model developed in this article is deployed as a web tool **[here](https://bkltest.genexplain.com/)**

The sample output of the Machine Learning Web tool is given in **Models** folder in this repository 


