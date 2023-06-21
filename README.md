# Cardiovascular-Risk-Prediction

![shutterstock_1803082342](https://github.com/shubham19nijwala/Cardiovascular_Risk_Prediction-Classification/assets/130289158/a586cacc-68e4-4ad7-a447-6dd0e1c09260)

# PROBLEM STATEMENT:

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients' information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.

# PROJECT SUMMARY:

The objective of this project was to utilize machine learning methods to predict the likelihood of coronary heart disease (CHD) in patients over a span of 10 years. The project utilized data from an ongoing cardiovascular study conducted in Framingham, Massachusetts, which provided information on more than 4,000 patients and included 15 attributes representing potential risk factors for CHD. These factors encompassed demographics, behavior, and medical aspects.

To ensure the data was suitable for analysis, extensive preprocessing was carried out. This involved addressing missing values using techniques such as median, mode, and K-nearest neighbors (KNN) imputation. Outliers were detected and eliminated using the Interquartile Range (IQR) method. Skewed continuous variables were transformed using square root transformations to improve symmetry and enhance model performance.

Feature selection was performed by assessing the variance inflation factor to identify and remove multicollinearity. Additionally, a new feature called pulse pressure was created to capture the relationship between systolic and diastolic blood pressure. Redundant columns were eliminated to simplify the dataset. The most influential features for predicting CHD risk were identified as 'age,' 'sex', 'cigs_per_day,' 'bp_meds,' 'prevalent_stroke,' 'prevalent_hyp,' 'diabetes,' 'total_cholesterol,' 'bmi,' 'heart_rate,' 'glucose,' and 'pulse_pressure.'

To address the imbalanced nature of the dataset, the SMOTE combined with Tomek links undersampling technique was employed to balance the class distribution and enhance model performance. The data was standardized using the standard scalar method to ensure that all features were on a comparable scale.

Multiple machine learning models were evaluated based on their performance using recall as the primary evaluation metric. After thorough analysis, the Neural Network was selected as the final prediction model due to its highest recall score among the models evaluated. Choosing a model with a high recall score aimed to accurately identify as many patients at risk of CHD as possible, even at the cost of some false positives.

In summary, this project showcased the potential of machine learning techniques in accurately predicting CHD risk in patients using data from a cardiovascular study. By meticulously preprocessing and transforming the data, selecting relevant features, and opting for an appropriate model based on its performance on a relevant evaluation metric, it was possible to make significant strides in accurately predicting CHD risk in patients, thus yielding a positive impact in the field.

# CONCLUSION:

In conclusion, this project effectively utilized machine learning techniques to predict the risk of coronary heart disease (CHD) in patients over a 10-year period. The following key findings emerged:

1. Thorough data preprocessing and transformation greatly enhanced the performance of the machine learning models, resulting in more precise predictions.
2. The selection of relevant features played a critical role in identifying the most significant factors contributing to CHD risk.
3. The Neural Network model stood out as the optimal choice for prediction due to its exceptional recall score.
4. Various techniques, including SMOTE combined with Tomek links undersampling and standard scalar scaling, were employed to handle imbalanced data and improve the models' performance.
5. This project serves as a compelling example of how machine learning can be effectively applied to real-world scenarios, delivering tangible business benefits.

Ultimately, this project underscores the importance of meticulous data preparation and analysis in the realm of machine learning. By investing effort into data cleaning, feature selection, and model selection, accurate predictions can be achieved, empowering informed decision-making across diverse domains.

