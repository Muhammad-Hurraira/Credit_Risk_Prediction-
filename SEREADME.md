# Credit Risk Prediction

This project focuses on predicting credit risk using supervised machine learning techniques. The goal is to classify whether a loan applicant is likely to default or repay a loan, enabling financial institutions to make data-driven lending decisions.

## 📌 Features

- Preprocessing of raw loan applicant data
- Handling of missing values with mode/median imputation
- Encoding categorical variables using `LabelEncoder`
- Splitting the data into training and test sets
- Training a **Logistic Regression** model
- Evaluation using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- Visualizing results with Seaborn and Matplotlib
- Exporting the trained model using `joblib`

## 📊 Model Performance

- **Model Used**: Logistic Regression  
- **Test Accuracy**: **78%**

## 📁 File Structure

- `Credit_Risk_Prediction.ipynb`: Jupyter notebook with the full ML pipeline
- `model.pkl`: Saved model (generated after training)
- `train.csv`: Dataset used for training (not included here)

## 🚀 How to Run

1. Clone this repository
2. Add your `train.csv` file to the root directory
3. Open the notebook in Jupyter or VS Code
4. Run all cells to train the model and view results
5. The trained model will be saved as `model.pkl`

## 🧠 Future Improvements

- Hyperparameter tuning with GridSearchCV
- Try ensemble models like Random Forest or XGBoost
- Deploy the model as a web API
