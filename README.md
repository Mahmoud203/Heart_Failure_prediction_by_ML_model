
# Heart Failure Clinical Records Dataset Analysis



## Introduction
Cardiovascular diseases are a leading cause of death globally, responsible for approximately 17 million deaths annually. This project focuses on heart failure, a severe condition where the heart cannot pump sufficient blood to sustain the body's organs. The primary goal of this project is to utilize machine learning algorithms to predict the survival of heart failure patients, tackling challenges such as imbalanced datasets and implementing feature selection strategies to enhance prediction accuracy.
## Dataset
The dataset used in this project is the Heart Failure Clinical Records Dataset from the UCI repository. It contains medical records of 299 heart failure patients collected from the Faisalabad Institute of Cardiology and Allied Hospital in Faisalabad (Punjab, Pakistan) in 2015. The dataset includes 13 features, representing clinical, body, and lifestyle information.
## Data Description
Age: Age of the patient

Anaemia: Decrease of red blood cells or hemoglobin (boolean)

High blood pressure: If a patient has hypertension (boolean)

Creatinine phosphokinase (CPK): Level of the CPK enzyme in the blood (mcg/L)

Diabetes: If the patient has diabetes (boolean)

Ejection fraction: Percentage of blood leaving the heart at each contraction (percentage)

Platelets: Platelets in the blood (kiloplatelets/mL)

Serum creatinine: Level of serum creatinine in the blood (mg/dL)

Serum sodium: Level of serum sodium in the blood (mEq/L)

Sex: Female or Male (boolean)

Smoking: If the patient smokes (boolean)

Time: Follow-up period (days)

Death event: If the patient died during the follow-up period (boolean)
## Data Preprocessing
1-Detection and handling of null values.

2-Min-max normalization of the dataset.

3-Splitting the dataset into training (70%) and testing (30%) subsets.
## Data Visualization
Various visualizations were created to gain insights into the dataset, including histograms, scatter plots, and box plots, to understand the distribution and relationships of different features.

## Modeling
We applied several classification algorithms to predict the survival of heart failure patients:

1-K-Nearest Neighbors (KNN): Achieved an accuracy of 81.11% with an optimal K value of 6.

2-Naive Bayes (NB): Achieved an accuracy of 77%.

3-Decision Tree (DT): Achieved an accuracy of 86%.

4-Random Forest (RF): Achieved the highest accuracy of 88%.
## Results
Our models were compared with results from three other research studies using the same dataset. The Random Forest algorithm achieved the best performance in our study with an accuracy of 88%.
## Conclusion
Machine learning and data mining techniques can significantly enhance the early detection and prediction of heart failure, potentially saving lives through timely and effective treatment and counseling. While our models showed promising results, further improvements can be made by addressing the challenges of imbalanced datasets and feature selection.
