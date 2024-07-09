# Dry-Bean-Classification-using-Machine-Learning-Project

**Introduction:**
Dry beans are a staple food worldwide, and accurate classification of bean types is crucial for quality control and market assessment in agriculture and food processing industries. Machine learning offers robust methods to classify dry beans based on various physical attributes. This project aims to leverage machine learning techniques to classify different types of dry beans accurately using features extracted from images or measurements of bean characteristics.

**Problem Statement:**
The objective of this project is to develop a machine learning model that can classify different types of dry beans based on physical attributes such as size, shape, color, and texture. The model will use a dataset containing features derived from images or measurements of beans, including area, perimeter, length, width, and various shape factors. 

**Dataset:**
The dataset used for this Project has 13,611 records and has the following features:

•	Area (A): The area of a bean zone and the number of pixels within its boundaries.

•	Perimeter (P): Bean circumference is defined as the length of its border.

•	Major axis length (L): The distance between the ends of the longest line that can be drawn from a bean.

•	Minor axis length (l): The longest line that can be drawn from the bean while standing perpendicular to the main axis.

•	Aspect ratio (K): Defines the relationship between L and l.

•	Eccentricity (Ec): Eccentricity of the ellipse having the same moments as the region.

•	Convex area (C): Number of pixels in the smallest convex polygon that can contain the area of a bean seed.

•	Equivalent diameter (Ed): The diameter of a circle having the same area as a bean seed area.

•	Extent (Ex): The ratio of the pixels in the bounding box to the bean area.

•	Solidity (S): Also known as convexity. The ratio of the pixels in the convex shell to those found in beans.

•	Roundness (R): Calculated with the following formula: (4piA)/(P^2)

•	Compactness (CO): Measures the roundness of an object: Ed/L

•	ShapeFactor1 (SF1)

•	ShapeFactor2 (SF2)

•	ShapeFactor3 (SF3)

•	ShapeFactor4 (SF4)

•	Class (the type of bean: Seker, Barbunya, Bombay, Cali, Dermosan, Horoz, and Sira) [Target Variable]

**Project Description:**

• Conducted Exploratory Data Analysis (EDA) to analyze insights and patterns

• Performed Data Pre-processing steps to prepare data for modelling.

• Developed Machine Learning Models such as Logistic Regression with Ridge (L2) Regularization, Random Forest, and AdaBoost to classify bean type.

• Employed stacked ensemble models to significantly boost predictive capabilities.

• Implemented hyperparameter tuning to optimize model accuracy.

• Analyzed feature importance across models, revealing key predictors for enhanced accuracy.

• Employed F1 score as the evaluation metric.

**Observation:**

• Perimeter is an important feature for Random Forest and AdaBoost Model

• ShapeFactor3 is an next important feature for Random Forest and MajorAxisLength is an second important feature for AdaBoost

• Features are highly correlated with the Target Variable in Logistic Regression Model

• Random Forest Model performs better when compared to other models.

• Achieved an F1 score of 0.91 with the stacked model.

**Skills:** Cross Validation · Logistic Regression · AdaBoost · Model Stacking · Feature Importance Analysis · Data Pre-Processing · Random Forest · Hyper-Parameter Tuning · Exploratory Data Analysis · Machine Learning
