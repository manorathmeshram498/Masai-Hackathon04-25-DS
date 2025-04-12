# 📊 Masai-Hackathon04-25-DS

## 🚀 Model Comparison and Hyperparameter Tuning in Machine Learning

This repository demonstrates a process of training and comparing multiple machine learning classification models on a synthetic dataset. The project includes:

1. **Data Preparation**  
   - Dataset generation, preprocessing, and feature engineering.

2. **Model Training**  
   - Training of various models like Logistic Regression, SVM, Random Forest, Decision Trees, and Gradient Boosting.

3. **Hyperparameter Tuning**  
   - Utilizing `GridSearchCV` to find the best model hyperparameters.

4. **Model Evaluation**  
   - Comparing models based on **Accuracy**, **Precision**, **Recall**, and **F1 Score**.

5. **Visualization**  
   - Visualizing model performance using bar charts for better understanding of each model’s capabilities.

---

## 🧩 Key Features

- **Synthetic Dataset**  
  A dataset with `age`, `income`, and `count` features, and a binary `target` for classification.

- **Model Training**  
  Trains at least five different models:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - Support Vector Machine (SVM)
  - Gradient Boosting

- **Hyperparameter Tuning**  
  Uses `GridSearchCV` to find optimal hyperparameters for each model.

- **Model Comparison**  
  Visualizes performance metrics like **Accuracy**, **Precision**, **Recall**, and **F1 Score**.

- **Results**  
  Includes `.csv` files with model performances before and after tuning.

---

## 🤖 Models Trained

- **Logistic Regression**  
  A linear model for binary classification.

- **Decision Tree**  
  A model that splits data into decision nodes.

- **Random Forest**  
  An ensemble of decision trees for improved accuracy.

- **Support Vector Machine (SVM)**  
  Finds the optimal hyperplane to separate classes.

- **Gradient Boosting**  
  Combines weak learners to form a strong model.

---

## 🛠️ Hyperparameter Tuning

`GridSearchCV` is used to fine-tune the following hyperparameters:

- **Logistic Regression**: `C`, `solver`  
- **Decision Tree**: `max_depth`, `min_samples_split`  
- **Random Forest**: `n_estimators`, `max_depth`, `min_samples_split`  
- **SVM**: `C`, `kernel`  
- **Gradient Boosting**: `n_estimators`, `learning_rate`, `max_depth`  

---

## 📏 Evaluation Metrics

Each model is evaluated using:

- **Accuracy**: Proportion of correct predictions.  
- **Precision**: Proportion of true positives among predicted positives.  
- **Recall**: Proportion of true positives among actual positives.  
- **F1 Score**: Harmonic mean of Precision and Recall.

---

## 📈 Results

After hyperparameter tuning, models are compared based on their **F1 Score** and other metrics. The best-performing models can be identified via visualizations provided in the project.

---

## 📊 Visualizations

The project includes bar chart visualizations comparing model performances side-by-side on:

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

Feel free to fork, contribute, or suggest improvements! 🚀

## Drive link for video explanation
https://drive.google.com/file/d/1_ISq2pt7WfumOBdBezulYxMZByN_0so1/view?usp=sharing
