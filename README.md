# 🧠 Breast Cancer Classification Project

This project aims to classify tumors as Malignant (M) or Benign (B) using a variety of machine learning models. The dataset used comes from the popular Breast Cancer Wisconsin (Diagnostic) dataset.

##📊 Exploratory Data Analysis (EDA)

   - Basic statistics and structure: `.shape,` `.describe()`, `.dtypes`

   - Class distribution visualization: identified **imbalanced classes** (Malignant ≈ 37.3%)

   - Visualized feature distributions and overlaid class distributions on the same plots to analyze separability

   - Correlation heatmap to identify strongly correlated features

   - Retained features with correlation > 0.2 with the target variable for modeling


## 🧪 Model Training & Evaluation

Applied the following models on both original and standardized datasets:

	- **Logistic Regression**

	- **Linear Discriminant Analysis**

	- **K-Nearest Neighbors**

	- **Decision Tree**

	- **Naive Bayes**

	- **Support Vector Machine**

	- **AdaBoost**

	- **Gradient Boosting**

	- **Random Forest**

	- **Extra Trees Classifier**


Each model was evaluated using:

	- **Accuracy**

	- **Precision**

	- **Recall**

	- **F1-score**

	- **Balanced Accuracy**

## 📈 Results & Comparison

   - Top 7 models were selected for each metric separately

   - Performance was compared using both tables and bar chart visualizations

   - Balanced accuracy was used to account for class imbalance, providing more reliable insights than accuracy alone


## 📝 Conclusion

The project highlights the importance of:

	- **Using multiple metrics when working with imbalanced datasets**

	- **Standardizing data to improve model performance**

	- **Comparing multiple models to identify the best performer for each evaluation aspect**