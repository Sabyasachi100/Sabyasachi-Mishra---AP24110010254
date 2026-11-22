# 🤖 Machine Learning — Coursework & Practical Implementations

<p align="center">
  <b>A hands-on collection of Machine Learning experiments, analytical notebooks, algorithm implementations, and practical explorations of data-driven intelligence.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

---

## 📖 About the Repository

This repository contains my Machine Learning coursework, hands-on laboratory exercises, experiments, and model implementations developed throughout my Computer Science and Engineering journey.

It explores the fundamental stages of the Machine Learning pipeline, starting with numerical computing, data manipulation, statistical analysis, and preprocessing, followed by model development, evaluation, optimization, and dimensionality reduction.

The notebooks focus on understanding not only how to implement Machine Learning algorithms, but also **why they work, how their parameters influence performance, and how different models behave when applied to data**.

This repository represents my continuous learning and experimentation with data-driven techniques, building a foundation for more advanced AI/ML applications.

---

## 🎯 Objectives

- Develop a strong foundation in Machine Learning concepts and algorithms.
- Understand how raw data is transformed into meaningful model inputs.
- Explore statistical methods and patterns through data visualization.
- Implement regression and classification algorithms.
- Study the effect of model complexity, distance metrics, and hyperparameters.
- Understand dimensionality reduction and feature representation.
- Evaluate model performance and analyze limitations.
- Develop practical skills through notebook-based experimentation.

---

## 📚 Topics Covered

### 📊 Data Analysis & Preprocessing
Understanding datasets, handling data, exploring statistical properties, preparing features, and transforming data into a suitable format for machine learning models.

### 📈 Regression
Exploring Linear Regression and Polynomial Regression to understand relationships between variables, predictions, model fitting, and non-linear patterns.

### 🎯 Classification
Implementing classification techniques such as K-Nearest Neighbors, Decision Trees, and Naive Bayes to explore how models learn decision boundaries and categorize observations.

### 🔍 Model Evaluation & Optimization
Analyzing model performance, experimenting with hyperparameters, understanding overfitting and underfitting, and evaluating the generalization capability of models.

### 🧬 Dimensionality Reduction
Exploring Principal Component Analysis (PCA) to reduce feature dimensionality while retaining useful information and studying its effect on data representation.

### 🎬 Recommendation Systems
Exploring recommendation approaches through movie-related data and understanding how data-driven systems can generate relevant recommendations.

---

## 🗂️ Repository Structure

```text
Machine-Learning-Coursework/
│
├── Linear_Poly_Regression_Teaching_Notebook_.ipynb
│
├── Movie_Recomendation (1).ipynb
│
├── NumPy_HandsOn_Array_to_Image_Analysis_Student_Lab_v2_(2).ipynb
│
├── Pandas_HandsOn_Student_Lab (1).ipynb
│
├── Preprocessing_HandsOn_Student_Lab (1).ipynb
│
├── Statistics_EDA_HandsOn_Student_Lab (1).ipynb
│
├── Week5_Linear_Regression_Student_Lab (1).ipynb
│
├── Week6_Polynomial_Regularization_Student_Lab (1).ipynb
│
├── Week7_KNN_Distance_Measures_Student_Lab (1).ipynb
│
├── Week8_Decision_Tree_Student_Lab (1).ipynb
│
├── Week9_PCA_Student_Lab (1).ipynb
│
├── naive_bayes_pipeline.ipynb
│
└── README.md
```

---

## 🧪 Notebook Breakdown

| Notebook | Description |
|---|---|
| **Linear & Polynomial Regression** | Exploring regression models, relationships between variables, model fitting, and polynomial feature transformations. |
| **Movie Recommendation System** | Experimenting with movie recommendation approaches and data-driven recommendation logic. |
| **NumPy Hands-on** | Working with arrays, numerical operations, multidimensional data, and image-related array manipulation. |
| **Pandas Hands-on** | Data loading, filtering, manipulation, analysis, and working with structured datasets. |
| **Preprocessing Hands-on** | Preparing datasets for modeling through data transformation and preprocessing techniques. |
| **Statistics & EDA** | Understanding distributions, descriptive statistics, data patterns, and exploratory analysis. |
| **Week 5 – Linear Regression** | Applying Linear Regression, studying prediction behavior, and evaluating regression performance. |
| **Week 6 – Polynomial & Regularization** | Exploring polynomial models, complexity, regularization, and the balance between fitting and generalization. |
| **Week 7 – KNN & Distance Measures** | Implementing KNN and exploring how distance metrics and the choice of K influence model behavior. |
| **Week 8 – Decision Trees** | Understanding tree-based classification, decision rules, feature-based splitting, and model interpretability. |
| **Week 9 – PCA** | Exploring dimensionality reduction, principal components, and feature-space transformation. |
| **Naive Bayes Pipeline** | Implementing probabilistic classification and exploring structured Machine Learning workflows. |

---

# 🏗️ Machine Learning Workflow

The notebooks collectively explore the major stages involved in developing a Machine Learning model.

```text
                 MACHINE LEARNING PIPELINE
                           │
                           ▼
               ┌──────────────────────┐
               │   Data Collection   │
               │   & Understanding   │
               └──────────┬─────────┘
                          │
                          ▼
               ┌──────────────────────┐
               │ Statistical Analysis │
               │      & EDA          │
               └──────────┬─────────┘
                          │
                          ▼
               ┌──────────────────────┐
               │ Data Preprocessing   │
               │ & Feature Engineering│
               └──────────┬─────────┘
                          │
                          ▼
               ┌──────────────────────┐
               │   Model Selection   │
               └──────────┬─────────┘
                          │
          ┌───────────────┼────────────────┐
          ▼               ▼                ▼
     Regression      Classification   Dimensionality
                                        Reduction
          │               │                │
          └───────────────┼────────────────┘
                          ▼
               ┌──────────────────────┐
               │ Model Training      │
               │ & Experimentation   │
               └──────────┬─────────┘
                          │
                          ▼
               ┌──────────────────────┐
               │ Evaluation & Tuning │
               └──────────┬─────────┘
                          │
                          ▼
               ┌──────────────────────┐
               │ Analysis & Insights │
               └──────────────────────┘
```

### Workflow Explanation

| Stage | Purpose |
|---|---|
| Data Understanding | Understand the dataset, features, structure, and prediction problem. |
| EDA | Identify patterns, distributions, correlations, and anomalies. |
| Preprocessing | Clean and transform data into a model-ready representation. |
| Model Selection | Choose an algorithm appropriate for the problem. |
| Training | Allow the model to learn patterns from the training dataset. |
| Evaluation | Measure model performance using appropriate metrics. |
| Optimization | Improve performance through parameter tuning and model adjustments. |
| Interpretation | Analyze model behavior, limitations, and results. |

---

## 🧠 Algorithms & Concepts Explored

| Algorithm / Concept | Key Learning |
|---|---|
| Linear Regression | Modeling relationships between independent and dependent variables. |
| Polynomial Regression | Capturing non-linear relationships through transformed features. |
| Regularization | Controlling model complexity and reducing overfitting. |
| K-Nearest Neighbors | Prediction based on nearby observations and distance measures. |
| Decision Trees | Learning decision rules through recursive feature splitting. |
| Naive Bayes | Probabilistic prediction using Bayes' theorem and conditional probabilities. |
| Principal Component Analysis | Transforming features into lower-dimensional representations. |
| Recommendation Systems | Using data and recommendation logic to identify relevant items. |

---

## 🛠️ Technology Stack

| Technology | Role |
|---|---|
| **Python** | Core programming language for ML experimentation. |
| **NumPy** | Numerical computation, arrays, and mathematical operations. |
| **Pandas** | Dataset manipulation, cleaning, and analysis. |
| **Matplotlib** | Visualizing data and model results. |
| **Seaborn** | Statistical visualization and exploratory analysis. |
| **Scikit-learn** | ML models, preprocessing, pipelines, and evaluation tools. |
| **Jupyter Notebook** | Interactive environment for experimentation and documentation. |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- pip
- Jupyter Notebook or JupyterLab

### 1. Clone the Repository

```bash
git clone https://github.com/Sabyasachi100/Sabyasachi-Mishra---AP24110010254.git
```

### 2. Navigate to the Project Directory

```bash
cd Sabyasachi-Mishra---AP24110010254
```

### 3. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any notebook from the repository and execute the cells to explore the implementations, experiments, visualizations, and model outputs.

---

## 📈 Key Learning Outcomes

Through these experiments and implementations, I have developed a deeper understanding of:

- Data manipulation and numerical computing using NumPy and Pandas.
- Statistical analysis and Exploratory Data Analysis.
- Data cleaning and preprocessing techniques.
- Regression and classification model implementation.
- Distance metrics and KNN parameter selection.
- Decision Tree learning and model interpretability.
- Bias–variance trade-offs and regularization.
- Dimensionality reduction using PCA.
- Model evaluation and performance analysis.
- Building structured Machine Learning pipelines.
- Applying theoretical concepts to practical datasets.

---

## 🔮 Future Scope

- Implement additional algorithms such as Random Forest, SVM, and Gradient Boosting.
- Explore feature selection and advanced feature engineering.
- Experiment with hyperparameter optimization techniques.
- Perform cross-validation and systematic model comparison.
- Develop end-to-end ML projects with real-world datasets.
- Explore Deep Learning, NLP, and computer vision.
- Build interactive dashboards for model visualization and analysis.

---

## 👨‍💻 Author

**Sabyasachi Mishra**

Computer Science & Engineering Student  
Interested in Artificial Intelligence, Machine Learning, Data Science, and Full-Stack Development.

🔗 [GitHub Profile](https://github.com/Sabyasachi100)

---

<p align="center">
  <b>Understanding data. Learning algorithms. Building intelligent solutions. 🧠</b>
</p>
