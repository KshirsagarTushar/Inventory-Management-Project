# Predictive and Prescriptive Statistical Models for Inventory Management in Health Care (Updated 2024)
The project aims to develop and implement predictive and prescriptive statistical models to optimize inventory management in healthcare settings. Efficient inventory management in healthcare is crucial to ensure the availability of necessary medical supplies and medications while minimizing costs and waste. The project focuses on using advanced analytics to prescribe optimal inventory policies.

# Sections
- Overvview
- Dataset Information
- Methodology
- Installation
- How to run
- Authors
- Relevant Links

# Overview
An essential aspect in healthcare, effective inventory management is important to make sure that the necessary medical supplies and medicines do not go out of stock and at the same time, the need for ensuring minimum costs and minimum wastage in the process. Many of these traditional inventory methods have difficulty in the dynamic health care demand environment and can lead to either the high costs of overstocking or the high costs of stockouts. Health care facilities can streamline their inventory processes considerably by using predictive analytics to predict demand and prescriptive analytics to optimize inventory decisions. Having predictive and prescriptive statistical models can also improve decision making such as forecasting, optimal inventory levels, and optimal ordering strategies. This project will develop and apply predictive and prescriptive models in order to better manage inventory in healthcare, thereby resulting in better allocation of resources, reduced costs and improved patient care.

# Dataset Information
The study uses and compares different machine learning algorithms for predictive modelling in Inventory Management in Health Care (Classification Problem). The dataset is in the csv file of type consisting ID, Age, Age Group, Gender, Blood Pressure, Hemoglobin, Blood Glucose, Sugar Level, Arthritis, Breathing Problem, Diagnosis, Type of Disease, Medicine, Type of Medicine, Locality and Recovery Time where the ID is an unique integer identifying the record of patient, patient's medical history consist of Age, Gender, Blood Pressure, Hemoglobin, Blood Glucose, Sugar Level, Arthritis, Breathing Problem. Diagnosis is nothing but the disease from which the patient is suffering and Type of Disease is the category of disease. Medicine refers to the Injection, Capsules, and other kind of drugs used for the treatment of patient, with Type of Medicine refers to the category of drug. Locality comes from where the patient's current residence. Recovery Time of patient has three classes as patient might recover within 48 hours, patient might recover in between 48 to 72 hours and patient might take more than 72 hours to recover. Please note that, csv headers are not expected and should be removed from the dataset.

# Methodology
- Data Collection:
  The project initiated by collecting the data from a multi-speciality hospital. Ensured that data sources are reliable, and the dataset encompasses a wide range of features, including patient's medical history, information related to diagnosis and treatment, and recovery time of patient.

- Data Preprocessing:
  Started with data preprocessing to enhance quality and suitability of data for analysis. This phase includes addressing missing data, handling outliers, and removing duplicate records. Standardize data formats, encode categorical variables, and ensure consistency in data representations.

- Exploratory Data Analysis (EDA):
  Conducted an exploratory data analysis to gain initial insights into the dataset's characteristics. Generated summary statistics, visualized data through bar plots, pie chart, tree map, word cloud, and created correlation plot to identify potential correlations and trends.

- Descriptive Statistical Model:
  Performed a detailed descriptive statistical analysis to further understand the dataset. Calculated central tendency measures (mean, median), measures of dispersion (standard deviation, range), and correlation coefficients. Summarize findings in tables and charts for clarity.

- Diagnostic Statistical Model:
  Diagnosed potential issues in the dataset that might affect subsequent analyses. Used correlation plot matrices to detect multicollinearity among variables.

- Statistical Testing:
  Employed a specific statistical test to assess the data:
  - Chi-squared Test: Assessed the dependency of features, particularly in categorical data, to identify significant relationships.

- Predictive Statistical Model (Machine Learning):
  Developed a predictive statistical model using machine learning techniques. Chose appropriate algorithms, such as Decision Tree, Random Forest, Gradient Boosting, Ada Boost based on the project's objectives. Split the dataset into training and testing subsets for model validation.

- Model Comparison:
Trained and evaluated multiple predictive models, assessing their performance using key metrics, including accuracy, precision, recall, and F1 score.

- Best-Fitted Model Selection:
  Selected the best-fitted model based on the model comparison results. Chose the model that demonstrates the highest predictive accuracy and aligns with the project's goals.

- Prescriptive Statistical Model:
  Utilized the selected predictive model to conduct prescriptive analysis. Generated actionable recommendations and strategies based on the model's predictions. These recommendations aim to optimize operational efficiency, enhance customer satisfaction, or drive revenue growth for the insurance company.

- Documentation and Reporting:
  Compiled a comprehensive project report that documents all phases of the analysis. Included detailed explanations of the methodology, data preprocessing steps, EDA findings, descriptive and diagnostic statistical analyses, results of statistical tests, model comparison details, and prescriptive recommendations. Utilized visualizations, tables, and charts to aid in data interpretation and presentation.

Throughout the project, utilized statistical software tools like Python, or specialized machine learning libraries to execute the analysis and generate visualizations. This methodical approach ensures a 
rigorous analysis of the complex Inventory Management Dataset, delivering valuable insights and actionable recommendations to address specific business challenges.

# Installation
There is a general requirement of libraries for the project and some of which are specific to individual methods. The required libraries are as follows:
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn

These libraries can be installed by using the pip installer.

# How to run
For the sake of simplicity I have added everything in a single Python Notebook file. Follow the Notebook, each cell in the notebook is well commented which will help to understand the project steps.

# Author
[Tushar Kshirsagar](https://github.com/KshirsagarTushar)

# Relevant Links
LinkedIn : www.linkedin.com/in/tushar-kshirsagar-8459bb245

NovyPro : https://www.novypro.com/profile_about/tusharkshirsagar

Tableau Public : https://public.tableau.com/app/profile/tushar.kshirsagar2148/vizzes
