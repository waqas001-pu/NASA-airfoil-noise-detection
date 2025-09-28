# NASA Airfoil Noise Detection with PySpark ML

This project applies **PySpark ML** to the NASA Airfoil Self-Noise dataset to predict aerodynamic noise levels. It demonstrates how to build an **end-to-end machine learning pipeline** using Spark’s distributed framework — covering feature engineering, model training, and evaluation.

## 📂 Project Structure

* `NASA_airfoil_noise_detection.ipynb` – Jupyter Notebook with full PySpark ML workflow
* `requirements.txt` – Python/PySpark dependencies
* `data/` – (optional) dataset files or instructions for download

## 🚀 Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/airfoil-noise-detection.git
   cd airfoil-noise-detection
   ```

2. Install dependencies (make sure Spark is available in your environment):

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook NASA_airfoil_noise_detection.ipynb
   ```

## 📊 Dataset

The dataset comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Airfoil+Self-Noise).
It contains **1,503 samples** with 5 input variables and 1 target variable (scaled sound pressure level).

## 🛠️ Tech Stack

* **PySpark ML** (Pipelines, Transformers, Estimators)
* Python
* Jupyter Notebook
* Pandas (for initial exploration)
* Matplotlib / Seaborn (for visualization)

## ✨ Key Features

* Data loading & preprocessing with PySpark
* Feature scaling and vector assembly using Spark ML
* Regression models (e.g., Linear Regression, Decision Tree Regressor, Random Forest Regressor)
* Evaluation with metrics such as **RMSE** and **R²**
* End-to-end ML pipeline in a distributed environment

## 📈 Results

* Successfully built PySpark ML pipelines for multiple regression models
* Compared performance metrics to identify the best-performing algorithm
* Demonstrated how PySpark ML can handle scalable ML workflows

## 📜 License

This project is licensed under the MIT License.
