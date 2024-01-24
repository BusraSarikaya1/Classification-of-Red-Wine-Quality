# Final_project

Veri Bilimi ve Makine Öğrenimi eğitimi final projesi

- Source: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009
          
- Ek Bilgi: data processing kısmında yani "analysis2.ipynb" dosyasında değişkenler üzerinde dönüşüm denemeleri yaptığım, normalizasyon grafiklerini incelediğim ve uygun olup olmadığını karar verdiğim dosya methods.ipynb'dir.

### Project Description

### Steps Involved
1. Dataset Examination and Exploratory Data Analysis (https://github.com/BusraSarikaya1/Final_project/blob/main/analysis_file/1_analysis.ipynb)
	 - Get the dataset from the source and read it.
     - View the first few rows of the dataset.
     - Analyze the shape of the dataset (number of rows and columns).
     - Let's check the data types of each column and look at general information about the data.
	 - Examining the general statistical information of the data we work with.
	 - Using a pie chart and bar chart, let's visualize the ranges in which the wine qualities scores are distributed.
	 - Examine the relationship between the target variable quality and other variables.
	 - Examine the relationship of all variables with each other with the heat map.
	 - Visualize the relationship between the variables that we think are most related to each other with regression graphs.
	 - Let's examine the density charts and box plots according to the scores given to the wines. Check it out.


2. Data Preprocessing and Data Preparation:(https://github.com/BusraSarikaya1/Final_project/blob/main/analysis_file/2_analysis.ipynb)
     - The scored quality target variable was classified as our quality and quality and was recorded in the master data.
	 - Bar and pie chart visualization presented.
	 - Box plot images were examined for outlier analysis.
	 - Univariate outlier analysis was performed.
	 - Independent variables that did not appear to be outliers were examined with the help of the Grubbs Test.
	 - Outlier analysis for both Categorical and numerical variables.
	 - Whether or not the quarterly gap method should be applied for all variables was checked one by one. The density graphs were checked before and after application.(https://github.com/BusraSarikaya1/Final_project/blob/main/trials.ipynb)
	 - Duplicating values were removed from the data.
	 - Clean data was created.


5. Model Training and Evaluation:(https://github.com/BusraSarikaya1/Final_project/blob/main/analysis_file/3_analysisd.ipynb)
     - The dependent (target) variable and independent variables were determined.
	 - Data in the independent variables were normalized.
	 - The data were divided into training and test sets.
	 - The model was created using these algorithms: Logistic Regression, Support Vector Classifier, Random Forest, Decision Trees.
	 - The evaluation metrics of the model were examined.





