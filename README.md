

***

# 🩺 Medicine Recommendation System using Machine Learning

This project predicts possible diseases based on reported symptoms and provides recommended medications, precautions, and diets using machine learning algorithms. It leverages a public dataset and supports scalable, accurate medical advice for users.

***

## 🚦 What This Project Does

- Loads and preprocesses a medical symptoms dataset from Kaggle
- Trains multiple machine learning models: Support Vector Machine (SVM), Random Forest, Gradient Boosting, KNeighbors, and Naive Bayes
- Evaluates models using cross-validation accuracy, precision, recall, and F1-score
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


[1](https://github.com/catiaspsilva/README-template)
[2](https://github.com/anujonthemove/Python-Machine-Learning-Template)
[3](https://realpython.com/readme-python-project/)
[4](https://www.makeareadme.com)
[5](https://github.com/KalyanM45/Data-Science-Project-Readme-Template)
[6](https://deepsense.ai/blog/standard-template-for-machine-learning-projects-deepsense-ais-approach/)
[7](https://medium.datadriveninvestor.com/how-to-write-a-good-readme-for-your-data-science-project-on-github-ebb023d4a50e)
[8](https://packaging.python.org/guides/making-a-pypi-friendly-readme/)
[9](https://www.machinelearningmastery.com/machine-learning-in-python-step-by-step/)



