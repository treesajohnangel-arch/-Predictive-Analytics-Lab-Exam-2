# -Predictive-Analytics-Lab-Exam-2
This repository contains my submission for a lab exam on binary classification.
The dataset includes two input features (Feature1, Feature2) and a binary target variable (Yes / No).

A Logistic Regression model was implemented to classify the data, along with complete analysis, visualization, and evaluation.

Project Structure
File	Description
Lab_Exam_binary_classification_dataset.csv	Dataset used for the analysis
lab_exam_classification.ipynb	Jupyter Notebook with full implementation
class_distribution.png	Class distribution visualization
feature_distributions.png	Feature distribution plots (histogram + KDE)
boxplots_by_class.png	Boxplots comparing features across classes
scatter_by_class.png	Scatter plot of Feature1 vs Feature2
correlation_heatmap.png	Correlation matrix heatmap
decision_boundary.png	Decision boundary visualization
confusion_matrix.png	Confusion matrix
roc_curve.png	ROC curve
Tasks Performed
1. Exploratory Data Analysis (EDA)

Checked for missing values and handled them

Removed extreme outliers to improve data quality

Analyzed class distribution (class imbalance)

Visualized feature distributions and relationships

Examined correlations between variables

2. Model Building

Implemented Logistic Regression

Applied feature scaling (standardization)

Handled class imbalance using class_weight='balanced'

3. Decision Boundary Visualization

Plotted the decision boundary of the model

Overlayed it on the dataset to show class separation

 4. Model Evaluation

The model was evaluated using:

Accuracy

Precision

Recall

F1-score

ROC-AUC

Additionally:

Confusion matrix was generated and analyzed

⚙️ How to Run
1️Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn
2️Run the notebook
jupyter lab lab_exam_classification.ipynb
Observations

The dataset has a moderate class imbalance (~78% No, ~22% Yes)

Feature-target correlation is relatively low

Logistic Regression, being a linear model, shows limited predictive performance

However, it serves as a strong baseline model

Conclusion

This project demonstrates a complete machine learning workflow:

Data preprocessing

Exploratory analysis

Model building

Visualization

Performance evaluation

While Logistic Regression performs reasonably well, future improvements could include:

Non-linear models (e.g., SVM, Decision Trees)

Feature engineering

Hyperparameter tuning
