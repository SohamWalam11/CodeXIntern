# CodeXIntern – Machine Learning Projects

This repository contains three machine learning projects, each implemented as a Jupyter notebook. They showcase data preprocessing, model training, evaluation, and visualization using a modern Python ML stack.



## 🛠 Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)



## 📊 Tech Stack Uses

| Technology    | Purpose / Use Case |
|---------------|--------------------|
| **Python**     | Core language for ML and data pipelines |
| **NumPy**      | Array operations and mathematical computations |
| **Pandas**     | Data wrangling, cleaning, and manipulation |
| **Matplotlib** | Basic data visualization |
| **Seaborn**    | Statistical visualizations with clean styling |
| **Plotly**     | Interactive data visualizations |
| **scikit-learn** | ML algorithms, preprocessing, model evaluation |
| **TensorFlow** | Neural networks and deep learning |
| **Keras**      | High-level API for TensorFlow models |
| **SciPy**      | Advanced math and optimization routines |



## 📌 Task 1 – Iris Flower Classification (`Task1.ipynb`)

- **Dataset:** Iris dataset (sepal and petal features)
- **Algorithm:** Logistic Regression (scikit-learn)
- **Goal:** Predict the species of iris flowers  
- **Key Steps:**  
  - Data exploration with Pandas, Seaborn  
  - Train/test split  
  - Model training and evaluation  
- **Performance:** ~100% accuracy, precision/recall ~1.00


## 📌 Task 2 – SMS Spam Detection (`Task2.ipynb`)

- **Dataset:** SMS spam collection (text messages)  
- **Algorithm:** Multinomial Naive Bayes with TF-IDF vectorization  
- **Goal:** Detect whether a given message is spam or ham  
- **Key Steps:**  
  - Text preprocessing using scikit-learn's TfidfVectorizer  
  - Model training and evaluation  
  - Confusion matrix visualization  
- **Performance:** ~97% accuracy, precision ~0.98, recall ~0.89



## 📌 Task 3 – Housing Price Prediction (`Task3.ipynb`)

- **Dataset:** California Housing dataset  
- **Algorithm:** Neural Network (TensorFlow/Keras)  
- **Goal:** Predict median house values using regression  
- **Key Steps:**  
  - Feature scaling with scikit-learn  
  - Neural network model design and training  
  - Loss and metric tracking during epochs  
- **Performance:**  
  - Test MSE ~3.0 × 10⁹  
  - Test MAE ~50,000  
  - R² ~0.67 


## Comparative Overview

| Task | Problem Type | Algorithm / Model | Approx Performance |
|------|-------------|-------------------|--------------------|
| 1    | Classification | Logistic Regression | ~95% accuracy |
| 2    | Classification | Multinomial Naive Bayes | ~98% accuracy |
| 3    | Regression | Neural Network (Keras) | R² ~0.82 |

---

## How to Run

```bash
git clone https://github.com/SohamWalam11/CodeXIntern.git
cd CodeXIntern
jupyter notebook
# Open Task1.ipynb, Task2.ipynb, or Task3.ipynb
