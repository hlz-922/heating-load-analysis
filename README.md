# heating-load-analysis

### **Project Description:**

- The primary goal is to apply machine learning techniques, specifically using the K-Nearest Neighbours (KNN) algorithm, to predict the heating load required.
- The assignment involves several key steps including data preprocessing, feature engineering, splitting the dataset into training and testing sets, and performing hyperparameter tuning with k-fold cross-validation.
- The performance of the model will be evaluated using two metrics: Mean Absolute Error (MAE) and Mean Square Error (MSE). The preliminary study reported an MAE of 1.875 and an MSE of 8.495, with an aim to improve these results through the assignment.

### **Key Steps in the Project**

1. **Setup:** Import necessary libraries for data manipulation (numpy, pandas), visualization (matplotlib, seaborn), statistical functions (scipy stats), and machine learning (sklearn).
2. **Data Loading:** Load the training dataset (**`df`**) and the held-out test dataset (**`df_eval`**) for model evaluation.
3. **Data Preprocessing and Feature Engineering:** Explore and preprocess the data to improve model performance, including scaling, encoding, and possibly feature selection or transformation.
4. **Splitting Dataset:** Divide the data into training and testing sets to prepare for model training and evaluation.
5. **Model Training and Hyperparameter Tuning:** Use k-fold cross-validation to fine-tune the KNN model's parameters.
6. **Model Evaluation:** Assess the trained model using MAE and MSE metrics, aiming to surpass the preliminary study's performance metrics.
