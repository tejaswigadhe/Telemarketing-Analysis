#Telemarketing Analysis

This project focuses on analyzing data from a bank marketing campaign using a Random Forest Classifier. The dataset (bank-full.csv) undergoes initial exploration, including displaying the first few rows, inspecting dataset properties, and summarizing missing values. Categorical features are transformed into numerical values using LabelEncoder for compatibility with machine learning models. Additionally, a correlation heatmap is used to visualize relationships among variables.

The target variable (y) is separated, and the dataset is divided into training and testing subsets with an 80-20 split. Stratification ensures that class distribution is maintained. Standardization of the features is performed using StandardScaler to enhance model performance.

The Random Forest Classifier, set with 100 estimators, is trained on the scaled training data. Predictions (y_pred) and probabilities (y_prob) are generated for the test set. Model performance is assessed through metrics such as precision, recall, and F1-score, along with visualizations like a confusion matrix heatmap and an ROC curve (Area Under the Curve).

Feature importance values, calculated by the Random Forest model, are plotted to identify the most impactful predictors of the target outcome. Graphical representations, such as bar charts and heatmaps, help in interpreting the results effectively.

This comprehensive analysis provides actionable insights into factors influencing successful marketing campaigns.
