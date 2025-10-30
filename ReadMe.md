# Analysis of Cancer Disease Using Machine Learning Algorithms

## Overview
This project aims to detect cancer early and accurately by using machine learning algorithms on patient data. It involves collecting, cleaning, and analyzing a dataset of cancer patient records with multiple health and lifestyle features. Several classification models are trained to distinguish between cancerous and non-cancerous cases to aid in early diagnosis.

## Dataset
- The dataset contains 1000 patient records with 25 columns including patient ID, age, gender, air pollution, alcohol use, dust allergy, genetic risk, chronic diseases, smoking habits, symptoms like chest pain and coughing blood, and more.
  
- All records are labeled to indicate whether the patient is suffering from cancer or not.

## Methodology
- Data Cleaning & Feature Selection: Relevant features influencing cancer detection were selected.
- Exploratory Data Analysis performed to understand data distribution and relationships.
- The dataset was split into training and testing subsets.
- Machine Learning Models Used:
  - Support Vector Machine (SVM): Finds the optimal boundary to separate cancerous from non-cancerous cases.
  - Random Forest Classifier: Uses multiple decision trees combined to improve classification accuracy.
  - Additional classifiers include K-Nearest Neighbors (KNN) and Decision Tree Classifier for comparison.

## Model Evaluation
- Models were evaluated using accuracy, precision, and recall metrics.
- Precision formula: True Positives / (True Positives + False Positives)
- Recall formula: True Positives / (True Positives + False Negatives)
- Accuracy formula: Number of correct predictions / Total predictions

## Results
| Classifier                | Precision | Recall | Accuracy |
|---------------------------|-----------|--------|----------|
| Random Forest Classifier   | 1.0       | 1.0    | 1.0      |
| Support Vector Machine     | 0.96      | 0.96    | 0.96     |
| K Nearest Neighbors        | 0.99      | 1.0    | 1.0      |
| Decision Tree Classifier   | 1.0       | 1.0    | 0.99     |

## Conclusion
The machine learning models, particularly Random Forest and SVM, demonstrated high accuracy and reliability in identifying cancerous patients. This system can potentially support clinical decision-making for early detection, with ongoing development focused on enhancing robustness for real-world use.

## Technologies Used
- Python (pandas, numpy, scikit-learn)
- Machine Learning Algorithms: SVM, Random Forest, KNN, Decision Tree
- Data Cleaning and Analysis tools

## References
- Research papers and online resources on cancer detection and machine learning.
- Guidance and support provided by Dr. S Pavan, Assistant Professor.

***
