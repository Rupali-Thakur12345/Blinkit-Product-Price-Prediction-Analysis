# Blinkit-Product-Price-Prediction-Analysis
This project focuses on analyzing Blinkit product data and building machine learning regression models to predict product prices. Multiple regression algorithms were trained and evaluated to identify the best-performing model using R² Score and Mean Squared Error (MSE).
This project demonstrates end-to-end data analytics + machine learning skills, including data preprocessing, feature engineering, model comparison, and evaluation.

**🎯 Objectives**

* Perform exploratory data analysis (EDA) on Blinkit product data
* Encode categorical features for machine learning
* Train multiple regression models
* Compare models using R² Score and MSE
* Identify the best-performing model for price prediction

**🧩 Dataset**
Source: Blinkit product dataset

*Features include:*
* Product name
* Category
* Brand
* MRP
* Margin percentage
* Shelf life
* Stock levels
* Target variable:
* Price

**⚙️ Technologies Used**

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Jupyter Notebook

**🛠 Data Preprocessing**

* Handled categorical variables using Label Encoding
* Performed feature scaling using StandardScaler
* Split data into training and testing sets (75% / 25%)

**🤖 Machine Learning Models Used**

The following regression models were trained and evaluated:
*Linear Regression
* Ridge Regression
* Lasso Regression
* ElasticNet Regression
* Bayesian Ridge Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* AdaBoost Regressor
* Bagging Regressor
* Extra Trees Regressor
* K-Nearest Neighbors Regressor

**📊 Model Evaluation Metrics**

* Since this is a regression problem, the models were evaluated using:
* R² Score – Measures how well the model explains variance in price
* Mean Squared Error (MSE) – Measures prediction error

**🏆 Results**

* Ensemble models like Gradient Boosting, Extra Trees, and Random Forest achieved the highest R² scores.
* The best-performing model explained ~99% variance in product price.
* Ensemble methods significantly outperformed linear models.

**📈 Visualizations**

* Correlation heatmap for feature relationships
* Actual vs Predicted price plots
* Model performance comparison table

**🧠 Key Learnings**

* Importance of feature scaling in distance-based models
* Why R² is preferred over accuracy for regression problems
* How ensemble models improve prediction performance
* End-to-end ML workflow used in real-world analytics projects

**🚀 Future Improvements**

* Hyperparameter tuning using GridSearchCV
* Feature importance analysis
* Model deployment using Streamlit
* Cross-validation for robust evaluation
