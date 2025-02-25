# Cirrhosis-Disease-Prediction-Disease-s-Stage-Prediction-Drugs-Prediction-
Cirrhosis Disease Prediction, Disease's Stage Prediction &amp; Drugs Prediction using Logistic Regression &amp; Random Forest Classifier

I've done Cirrhosis disease prediction, disease's stage prediction and drug prediction models using Logistic Regression and Random Forest. First I did EDA for visualizing the insights of our data. Then did feature engineering by converting our dataset which includes symptoms and blood tests into categorical values for prediction. Then I use Logistic Regression and Random Forest Classifier Algorithms for making our predictions models. Then I did the models evaluations by using metrics (precision, recall, f1-score & accuracy), confusion matrix & cross validation score. Then I created a prediction machine, in that machine if any patient entry his/her Age, Sex, Symptoms in Y/N and Blood Tests levels then the Machine will predict that if the patient has cirrhosis disease or not. If the patient has cirrhosis disease, it will also predict the stage of cirrhosis and will also recommend a drug for curing the disease.

Overview:

This project involves developing predictive models to diagnose cirrhosis, predict its stage, and recommend appropriate drugs using machine learning techniques. The models are trained on a dataset of 276 patients with primary biliary cirrhosis (PBC), incorporating various clinical and biochemical features.

Key Features:

Dataset: The dataset includes 276 patient records with 18 features, including age, sex, symptoms (ascites, hepatomegaly, spiders, edema), and blood test results (bilirubin, cholesterol, albumin, Alk_Phos, SGOT, triglycerides, platelets, prothrombin).

Models: Two machine learning models are employed:

Logistic Regression: Used for disease prediction and drug recommendation.

Random Forest: Used for disease prediction, stage prediction, and drug recommendation.

Predictions:

Disease Prediction: Models predict whether a patient has cirrhosis, with Logistic Regression achieving an accuracy of up to 80%.

Stage Prediction: Models predict the stage of cirrhosis (1 to 4), with Random Forest showing better stability.

Drug Recommendation: Models recommend either D-penicillamine or Placebo, with both models often suggesting Placebo.

Methodology:

Data Preprocessing: The dataset is cleaned and preprocessed by encoding categorical variables and applying thresholds to numerical variables.

Model Training: Both Logistic Regression and Random Forest models are trained on the preprocessed dataset.

Model Evaluation: Performance metrics include accuracy, precision, recall, and F1-score for disease and stage predictions. Cross-validation is used to assess model stability.

Results:

Disease Prediction: Logistic Regression outperforms Random Forest in terms of accuracy.

Stage Prediction: Random Forest shows better stability but lower accuracy compared to Logistic Regression.

Drug Recommendation: Both models consistently recommend Placebo for most patients.

Future Directions:

Hyperparameter Tuning: Further optimization of model parameters to improve accuracy and consistency.

Feature Engineering: Exploring additional features or transformations to enhance model performance.

Model Ensemble: Combining predictions from multiple models to improve overall robustness.

Code Structure:
The repository includes Python scripts for data preprocessing, model training, and evaluation. Key libraries used are Pandas for data manipulation, Scikit-learn for machine learning models, and Matplotlib/Seaborn for visualization.
