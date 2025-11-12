

***

# 🩺 Medicine Recommendation System using Machine Learning

This project predicts possible diseases based on reported symptoms and provides recommended medications, precautions, and diets using machine learning algorithms. It leverages a public dataset and supports scalable, accurate medical advice for users.

***

## 🚦 What This Project Does

- Loads and preprocesses a medical symptoms dataset from Kaggle
- Trains machine learning models: Support Vector Machine (SVM), Random Forest
- Evaluates models using accuracy, precision, recall, and F1-score
- Provides disease predictions and actionable recommendations on medications, precautions, diets, and workouts for user symptoms
- Visualizes results with confusion matrices, ROC curves, and feature importance plots

***

## ⚙️ Technologies Used

- Python 3.x
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- joblib (for model saving/loading)

***

## 📊 Dataset

- **Name:** Medicine Recommendation System Dataset
- **Source:** [Kaggle - Noor Saeed](https://www.kaggle.com/datasets/noorsaeed/medicine-recommendation-system-dataset)
- **Features:** 132 binary symptom columns and 1 disease target column (`prognosis`)
- **Target:** Disease class (41 possible categories)

***

## 📈 Results

- All tested algorithms (SVM, Random Forest, etc.) achieved 100% accuracy with perfect precision and recall, likely due to clean one-hot encoded data and well-separated disease categories.
- Example visualizations are included for ROC curves and confusion matrices.
- The system provides direct disease prediction as well as suggested medications, lifestyle, and dietary changes for each prediction.

***

## 💡 Future Work

- Deploy as a web application for real-time public use
- Integrate user authentication and symptom tracking over time
- Expand database with real user clinical records for robust validation

***



## 📚 References

- scikit-learn documentation: https://scikit-learn.org/stable/
- Python 3.x documentation: https://docs.python.org/3/
- Imbalanced-learn documentation: https://imbalanced-learn.org/stable/

***









