# Diabetic_Readmit_Analysis:

This modules involves analysis of more than 1,00,000 Clinical Database Patient Records aiming to understand the factors that are respondible for early readmission of a patient given his/her clinical information. 

The module makes extensive use of Py-Spark Data Frame framework and Spark Machine Learning Library (MLlib).

The whole analytical model can be found inside the file "DiabeticReadmission-Spark.ipynb". Some of the analysis are also written using R and can be found inside "DiabeticReadmission-R.ipynb"

Advanced machine learning models, including Logistic Regression, Lasso Regression, and Random Forest Classifier, were implemented using PySpark and the Spark MLlib to handle the large-scale data efficiently. 

Feature selection was meticulously performed using statistical methods such as the Chi-Square test and the Akaike Information Criterion, pinpointing the most significant clinical predictors. 

A data processing pipeline was crafted to manage the data effectively, incorporating one-hot encoding for categorical variables and employing VectorAssembler for feature vectorization. 

The project's success was underscored by achieving a Receiver Operating Characteristic (ROC) score of 0.646 with the Random Forest model, demonstrating its superior predictive power over baseline models and providing valuable insights for healthcare professionals to mitigate the risk of early readmission.

Sources of reference:

    1. Research Article: Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records. "https://www.hindawi.com/journals/bmri/2014/781670/"
    2. Dataset available at: "https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008#"

 Code Reference:

 	1. Spark Machine Learning Library (MLlib) Guide, http://spark.apache.org/docs/latest/ml-guide.html
 	2. http://www4.stat.ncsu.edu/~post/josh/LASSO_Ridge_Elastic_Net_-_Examples.html
 	3. https://databricks.com/blog/2015/06/02/statistical-and-mathematical-functions-with-dataframes-in-spark.html
 	4. https://www.codementor.io/jadianes/mllib-basic-statistics-exploratory-data-analysis-du107nxsy
 	5. https://mapr.com/blog/churn-prediction-pyspark-using-mllib-and-ml-packages/
 	6. https://www.analyticsvidhya.com/blog/2016/10/spark-dataframe-and-operations/

