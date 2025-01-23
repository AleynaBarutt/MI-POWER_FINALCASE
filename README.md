# Water Quality Analysis

![1](https://github.com/AleynaBarutt/MI-POWER_FINALCASE/assets/63070084/6a449d4a-e3d7-43a3-9c66-9fa77d344afe)

## **Motivation and Background**
Analyzing the impact of water quality on drinkability is critically important in the real world. Water is a fundamental resource for human health, but its drinkability, safety, and suitability for consumption depend on various factors.

Through this analysis, it becomes possible to understand and evaluate the factors that affect water quality. For example, the effects of water characteristics like pH value, hardness level, and chemical composition on drinkability can be explored. This information provides critical data for improving water source management and water supply processes.

Moreover, determining the pollution levels of water sources and assessing their compliance with drinkability standards is essential for health institutions, organizations responsible for water supply, and decision-makers. Understanding the drinkability status of water sources allows for measures to be taken to minimize health risks and protect public health.

Ultimately, evaluating the impact of water quality on drinkability provides valuable insights for preserving water sources, ensuring water supply safety, and maintaining health standards. This analysis supports the sustainable use of water resources and has a positive impact on human health and the environment.

## **Dataset Information**
This dataset includes features related to water quality and drinkability status. Some details about the dataset are as follows:
- The dataset contains 3,276 observations and 10 variables.
- Variables include physical and chemical properties of water such as pH value, hardness level, chlorides, sulfates, and temperature.
- The drinkability status represents whether the water is drinkable or not. A value of 1 indicates drinkable water, while a value of 0 indicates non-drinkable water. Therefore, there are two classes: (Drinkable: 1 and Non-Drinkable: 0).
- The dataset has missing values in some variables that need to be considered during analysis.
- Statistical analyses, visualizations, and machine learning algorithms can be applied to investigate the effects and relationships between water quality and drinkability.
- This dataset can be used to understand the drinkability status of water sources, improve water quality, and take measures to ensure safe drinking water.
- The dataset contains 491 missing values in the pH column, 781 in the sulfate column, and 162 in the trihalomethanes column, with a total of 1,434 missing values.

**Dataset:** [Water Potability Dataset on Kaggle](https://www.kaggle.com/datasets/adityakadiwal/water-potability)


## **Used Algorithms** 
- Logistic Regression
- Support Vector Machines (SVM Classification)
- Random Forest
- AdaBoost
- XGBoost
- CatBoost
- LightGBM

## **Libraries Used**
The following libraries were used to build and analyze the model:
- Flask for the web application
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib for plotting
- Plotly for interactive visualizations

## **Data Analysis Steps**
The following steps were carried out during the analysis:
- Data Loading: Import the dataset.
- Summary Statistics: Generate descriptive statistics to understand the data.
- Missing Data Analysis: Handle missing values.
- Outlier Detection: Identify and manage outliers in the dataset.
- Data Visualization: Visualize the data and insights through plots.

## **Algorithm Performance**

- Logistic Regression: 63.1% accuracy
- SVC: 63.3% accuracy
- Random Forest: 76.3% accuracy
- AdaBoost: 75.9% accuracy
- XGBoost: 76.9% accuracy
- CatBoost: 77.7% accuracy
- LightGBM: 77.8% accuracy

## **Training and Testing: (overfitting)**

- LightGBM Accuracy: 77.8%
- LightGBM Training Accuracy: 99.4%
- Random Forest Accuracy: 76.3%
-Random Forest Training Accuracy: 100%
-CatBoost Accuracy: 77.7%
- CatBoost Training Accuracy: 94.8%

## **Parameter Optimization**

- XGBoost: Best Score: 79.4%
- LightGBM: Best Score: 79.5%
- CatBoost: Best Score: 80.1%
- Random Forest: 80.4%

## **Algorithm Performance (After changes such as outliers, missing values, and categorization)**

- Logistic Regression: 57.7%
- SVC: 57.7%
- Random Forest: 69.5%
- XGBoost: 66.2%
- LightGBM: 69.1%
- CatBoost: 72.6%
- AdaBoost: 58.0%

## **Prediction**
The web application allows users to make predictions. The prediction results are displayed to the user. When tested with sample inputs from the dataset, the prediction results were accurate. This demonstrates that the model is capable of generating correct results with example inputs from the dataset.

![2](https://github.com/AleynaBarutt/MI-POWER_FINALCASE/assets/63070084/5dccbdf5-f978-4757-b3ba-123604f4316c)
